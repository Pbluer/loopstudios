<template>
  <header>
    <h1>IMMERSIVE <br> EXPERIENCE <br> THAT <br> DELIVER</h1>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="less" scoped>
  header {
    background-color: black;
    background-image: url('../../assets/images/mobile/image-hero.jpg');
    background-repeat: no-repeat;
    background-size: 100%;
    height: 95vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

    h1 {
      border: 1px solid #fff;
      font-size: 2.5rem;
      font-family: 'Josefin',sans-serif;
      text-align: left;
      padding: 10px;
      font-weight: 300;
      width: 260px;
    }
  }

  @media screen and (min-width: 1000px ){

    header {
      background-image: url('../../assets/images/desktop/image-hero.jpg');
    
      h1{
        font-size: 5rem;
        width: 45%;
        margin-right: 33%;
        padding: 3%;
        br:nth-last-child(1){
          display: none;
        }
      }

    } 
  }

</style>