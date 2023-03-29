<template>
    <div class="buttonContainer">
      <button class="testButton" type="button">{{ msg }}</button>
    </div>
  </template>
  
  <script>
  export default {
    name: 'TestButton',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .buttonContainer {
    display: flex;
    justify-content: center;
  }
  .testButton {
    width: 100px;
    height: 50px;
    background-color: aqua;
    border-radius: 20px;
    cursor: pointer;
  }

  .testButton:hover, .testButton:active {
    background-color: aquamarine;
  }

  </style>
  