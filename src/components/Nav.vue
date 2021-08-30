<template>
  <div class="navBar">
    <div class="navBar-logo">
      <h1>Loopstudios</h1>
      <button @click=" showNavBar = true " > &#x2630; </button>

      <ul>
        <li> <a href="#">About</a> </li>
        <li> <a href="#">Carrers</a> </li>
        <li> <a href="#">Events</a> </li>
        <li> <a href="#">Products</a> </li>
        <li> <a href="#">Support</a> </li>
      </ul>

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
    margin-top: 20px;   
  }

  .navBarMobile {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: rgb(0, 0, 0);

    .navBar-logo {
      margin-top: 20px;
    }

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
      font-size: 1.5rem;
      margin-right: 10px;
      cursor: pointer;
    }

    ul{
      display: none;
    }

  } 

  @media screen and ( min-width: 1000px ){

    .navBar-logo {
      
      h1 {
        margin-left: 5%;
      }

      button{
        display: none;
      }

      ul {
        display: inherit ;
        margin-right: 5%;

        li {
          margin: 20px;

          a {
            color: #fff;
            text-decoration: none;
            font-size: 1.3rem;
          }

        }

      }

    }

  }

</style>
