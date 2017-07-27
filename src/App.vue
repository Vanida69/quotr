<template>
  <div id="app">
    <div>
      <div>
        <img src="./assets/logo.png">
      </div> 
      <div>
        <h1>This title is biggest header </h1>
        <p>The long line message</p>
        <p><a href="https://www.google.com">link to https://www.google.com</a></p>
        <p>The different of<span> span tag </span>is use inline-display while div is block</p> 
        <p>many font style like <strong>bold</strong> or <em>italic</em> but no underline</p>
        <div>
          <p>Div can nested in div, and able to nested a lot</p> 
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Hello from './components/Hello'

export default {
  name: 'app',
  components: {
    Hello
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
span {
  color: #f00;
}
div {
  border: 1px solid #ccc;
  padding: 7px;
  margin: 7px;
}
</style>
