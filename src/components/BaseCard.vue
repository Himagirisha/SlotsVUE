<template>
    <div>
      <slot></slot>
    </div>
    <body>
        <slot name="header"></slot>
    </body>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style scoped>
  div {
    box-shadow: 0 3px 9px rgba(0, 0, 0, 0.3);
    border-radius: 10px;
    max-width: 30rem;
    background-color: rgb(232, 166, 42);
    color: whitesmoke;
  }
body{
    border: 1px solid green;
}
  </style>