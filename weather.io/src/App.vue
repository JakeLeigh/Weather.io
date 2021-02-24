<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" name="" id="" class="search-bar" placeholder='Search...'/>
        
      </div>
    </main>
  </div>
</template>

<script>

export default {
  name: 'app',
  data(){
    return {
      api_key: '8ad1e82462ca1d4f58d2c7e97620176f'
    }
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-family: 'montserrat', sans-serif
}
#app{
 background-image: url('./assets/cold-bg.jpg'); 
 background-size: cover;
 background-position: bottom;
 transition: .4s;
}
main {
  min-height: 100vh;
  padding: 25px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75));
}
.search-box {
  width: 100%;
  margin-bottom: 30px;
}
.search-box .search-bar {
  display: block;
  width: 100%;
  padding: 15px;
  color: #313131;
  font-size: 20px;
  appearance: none;
  border: none;
  outline: none;
  background: none;
  background-color: rgba(255,255,255,.5);
  border-radius: 0 16px 0 16px;
  transition: .4s;
  box-shadow: 0 0 8px rgba(0,0,0,.25);
}
.search-box .search-bar:focus{
  background-color: rgba(255,255,255,.75);
  box-shadow: 0 0 16px rgba(0,0,0,.25);
  border-radius: 16px 0 16px 0;
}
</style>
