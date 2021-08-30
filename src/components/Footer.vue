<template>
  <footer>
    <h1>Loopstudios</h1>

    <ul class="menu">
      <li><a href="#">About</a></li>
      <li><a href="#">Careers</a></li>
      <li><a href="#">Events</a></li>
      <li><a href="#">Products</a></li>
      <li><a href="#">Support</a></li>
    </ul>

    <ul class="icon">
      <li> <img src="./../assets/images/icon-facebook.svg" alt="Facebook" /> </li>
      <li> <img src="./../assets/images/icon-twitter.svg" alt="Twitter" /> </li>
      <li> <img src="./../assets/images/icon-pinterest.svg" alt="Pinterest" /> </li>
      <li> <img src="./../assets/images/icon-instagram.svg" alt="Instagram" /> </li>
    </ul>

    <p>© 2021 Loopstudios. All right reserved.</p>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>

  .icon {
    display: flex;
    justify-content: center;
    align-content: center;
    margin: 20px 0;
    li{  margin: 0 10px; }
 
  }

  .menu {
    li {
      margin: 10px 0;
    }

    a {
      text-decoration: none;
      color: #fff;
      font-weight: "Alata";
      cursor: pointer;
    }
  }

  footer {
    padding: 40px 10% 10px 10%;
    background-color: rgb(0, 0, 0);
    height: 55vh;

    h1 {
      font-family: "Alata";
      margin-bottom: 40px;
      font-size: 1.2rem;
    }

    p {
      margin-top: 30px;
      font-size: 0.9rem;
    }
  }

  @media screen and ( min-width: 1000px ){
    footer {
      display: flex;
      height: 20vh;

      .menu {
        position: relative;
        top: 30px;
        right: 125px;
        height: 30px;
        display: inline-flex;
        li {
          margin: 20px;
        }
      }

      .icon {
        position: relative;
         bottom: 20px;
        left: 370px;
      }

      p {
        height: 20px;
        left: 120px;
        position: relative;
        top: 19px;
      }
    }

  }
  
</style>