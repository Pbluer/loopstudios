<template>
  <div class="navBar">
    <div class="navBar-logo">
      <h1>Loopstudios</h1>
      <button @click=" showNavBar = true " > &#x2630; </button>
    </div>
  </div>


  <div class="navBarMobile animate__animated animate__fadeInRight" v-show="showNavBar">
     <div class="navBar-logo">
      <h1>Loopstudios</h1>
      <button @click=" showNavBar = false "> X </button>
    </div>
    
    <ul>
      <li> <a href="#">ABOUT</a> </li>
      <li> <a href="#">CAREERS</a> </li>
      <li> <a href="#">EVENTS</a> </li>
      <li> <a href="#">PRODUCTS</a> </li>
      <li> <a href="#">SUPPORT</a> </li>
    </ul>

  </div>

</template>

<script>
export default {
  name: 'navBar',
  props: {
    msg: String
  },
  data(){
    return{
      showNavBar: false
    }
  }
}
</script>

<style scoped lang="less">

  .navBar {
    position: absolute;
    width: 100%;
    height: 50px;
    background-color: rgb(0, 0, 0);
  }

  .navBarMobile {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: rgb(0, 0, 0);

    ul{
      text-align: left;
      margin-top: 20%;
      padding: 0 20px;

      li{
        margin: 20px 0;

        a {
          font-size: 2rem;
          text-decoration: none;
          color: #ffff;
          font-weight: 'Atala';
          font-weight: 300;
        }
      }

    }

  }

  .navBar-logo {
    position: relative;
    top: 10px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 0;

    h1 {
      font-family: 'Alata',sans-serif;
      font-size: 1.5rem;
      margin-left: 20px;
    }

    button {
      background-color: transparent;
      border: none;
      color: #ffff;
      font-size: 1.3rem;
      margin-right: 10px;
    }
  }

  

</style>
