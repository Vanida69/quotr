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

      <div>
        <h1>List</h1>
      </div>
      <div>
        <h2>Animals</h2> 
      <ul>
        <li>Dog</li>
        <li>Fish</li>
        <li>Cat</li>
        <li>Bear</li>
        <li>Tiger</li>
      </ul>
        <h2>Animals sort by size</h2> 
      <ol>
        <li>Whale</li>
        <li>Elephant</li>
        <li>Rhino</li>
        <li>Tiger</li>
        <li>Dog</li>
        <li>Cat</li>
      </ol>
      </div>
      <div>
        <h1>Input</h1>
      <div>
        <form>
        Username:  <input type="text" name="username">  Password:  <input type="text" name="password">
        </form>
      <div>   
        <form action="/action_page.php"><input type="checkbox" name="vehicle1" value="Accept terms and condition">Accept terms and condition<input type="checkbox" name="vehicle2" value="Remember me">Remember me
        </form>
      </div>
      <div>
        <form action="/action_page.php"><input type="radio" name="gender" value="Classic theme"> Classic theme<input type="radio" name="gender" value="Modern theme"> Modern theme
        </form> 
      </div>
      <div>
        <input type="button" onclick="alert('Login')" value="Login">
      </div>
      </div>
      </div>
    </div>   
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
