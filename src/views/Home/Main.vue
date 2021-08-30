<template>
  <main>
    <div class="info">

      <img src="../../assets/images/mobile/image-interactive.jpg" alt="VR" />
      <div class="info-text">
        <h2>THE LEADER IN INTERACTIVE VR</h2>
        <p>
          Founded in 2011, Loopstudios has been producing world-class virtual
          reality projects for some of the best companies around the globe. Our
          award-winning creations have transformed businesses through digital
          experiences that bind to their brand.
        </p>
      </div>

      <div class="creations">
        <h2>OUR CREATIONS  <a href="#">SEE ALL</a> </h2>

        <div class="images">
          <div id="earth">
            <h3>DEEP EARTH</h3>
          </div>

          <div id="arcade">
            <h3>DEEP EARTH</h3>
          </div>

          <div id="soccer">
            <h3>SOCCER TEAM VR</h3>
          </div>

          <div id="grid">
            <h3>THE GRID</h3>
          </div>

          <div id="above">
            <h3>FROM UP ABOVE VR</h3>
          </div>

          <div id="borealis">
            <h3>POCKET BOREALIS</h3>
          </div>

          <div id="curiosity">
            <h3>THE CURIOSITY</h3>
          </div>

          <div id="fisheye">
            <h3>MAKE IT FISHEYE</h3>
          </div>        
        </div>
      </div>

      <a href="#">SEE ALL</a>
    </div>
  </main>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
  .info {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 50px;

    img {
      max-width: 340px;
      margin-top: 30%;
    }

    .info-text {
      color: rgb(0, 0, 0);

      h2 {
        font-family: "Josefin", sans-serif;
        font-size: 2rem;
        margin-top: 10%;
        margin-bottom: 5%;
      }

      p {
        color: rgb(146, 144, 144);
        font-family: "Alata", sans-serif;
        font-size: 0.9rem;
        letter-spacing: 2px;
        width: 80vw;
        margin: 10px auto;
      }
    }

    .creations {
      h2 {
        font-size: 2rem;
        color: black;
        margin: 100px 0 20px 0 ;
      }
    }

    .images {
      display: grid;
      text-align: left;
      color: white;
      font-weight: "Alata";

      div {
        margin: 35px 0;
      }

      

      #earth {
        box-sizing: border-box;
        padding: 53px 30px;
        height: 130px;
        width: 350px;
        box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
        background-color: rgb(0, 0, 0);
        background-repeat: no-repeat;
        background-image: url("../../assets/images/mobile/image-deep-earth.jpg");

        h3 {
          width: 20px;
          font-size: 1.5rem;
        }
      }

      #arcade {
        box-sizing: border-box;
        padding: 53px 30px;
        height: 130px;
        width: 350px;
        box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
        background-color: rgba(0, 0, 0, 0.308);
        background-image: url("../../assets/images/mobile/image-night-arcade.jpg");
        background-repeat: no-repeat;

        h3 {
          width: 20px;
          font-size: 1.5rem;
        }
      }

      #soccer {
        box-sizing: border-box;
        padding: 53px 30px;
        height: 130px;
        width: 350px;
        box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
        background-color: rgba(0, 0, 0, 0.308);
        background-image: url("../../assets/images/mobile/image-soccer-team.jpg");
        background-size: 100%;
        background-repeat: no-repeat;

        h3 {
          width: 130px;
          font-size: 1.5rem;
        }
      }

      #grid {
        box-sizing: border-box;
        padding: 53px 30px;
        height: 130px;
        width: 350px;
        box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
        background-color: rgba(0, 0, 0, 0.308);
        background-image: url("../../assets/images/mobile/image-grid.jpg");
        background-size: 100%;
        background-repeat: no-repeat;

        h3 {
          width: 20px;
          font-size: 1.5rem;
        }
      }

      #above {
        box-sizing: border-box;
        padding: 53px 30px;
        height: 130px;
        width: 350px;
        box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
        background-color: rgba(0, 0, 0, 0.308);
        background-image: url("../../assets/images/mobile/image-from-above.jpg");
        background-size: 100%;
        background-repeat: no-repeat;

        h3 {
          width: 130px;
          font-size: 1.5rem;
        }
      }

      #borealis {
        box-sizing: border-box;
        padding: 53px 30px;
        height: 130px;
        width: 350px;
        box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
        background-color: rgba(0, 0, 0, 0.308);
        background-image: url("../../assets/images/mobile/image-pocket-borealis.jpg");
        background-size: 100%;
        background-repeat: no-repeat;

        h3 {
          width: 107px;
          font-size: 1.5rem;
        }
      }

      #curiosity {
        box-sizing: border-box;
        padding: 53px 30px;
        height: 130px;
        width: 350px;
        box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
        background-color: rgba(0, 0, 0, 0.308);
        background-image: url("../../assets/images/mobile/image-curiosity.jpg");
        background-size: 100%;
        background-repeat: no-repeat;

        h3 {
          width: 107px;
          font-size: 1.5rem;
        }
      }

      #fisheye {
        box-sizing: border-box;
        padding: 53px 30px;
        height: 130px;
        width: 350px;
        box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
        background-color: rgba(0, 0, 0, 0.308);
        background-image: url("../../assets/images/mobile/image-fisheye.jpg");
        background-size: 100%;
        background-repeat: no-repeat;

        h3 {
          width: 107px;
          font-size: 1.5rem;
        }
      }
    }

    a {
      border: 2px solid black;      
      padding: 20px 50px;
      background-color: #fff;
      font-weight: 700;
      text-decoration: none;
      font-size: 1.2rem;
      letter-spacing: 1px;
      color: black;
    }

    a:nth-child(1) {
        display: none;
    }
  }

  @media screen and ( min-width: 1000px ){
    
    .info {

      margin-bottom: 0;

      img{
        background-image: url('../../assets/images/desktop/image-interactive.jpg');
        max-width: 100%;
        margin-top: 10%;
        margin-bottom: 0;
        margin-right: 20%;
      }

      .info-text {
        background-color: #fff;
        width: 40vw;
        height: 256px;
        text-align: left;
        padding-left: 80px;
        position: relative;
        text-align: center;
        bottom: 256px;
        left: 350px;    
        
        h2 {
          font-size: 2.5rem;
          width: 80%;
        }

        p {
          margin: 0;
          width: 450px;
        }
        
      }

      .creations {
        position: relative;
        bottom: 120px;
        width: 90vw;

        h2{
          display: flex;
          width: 80vw;
          justify-content: space-between; 
          margin: 20px auto;
          letter-spacing: 2px;

          a {
            padding: 6px 27px;
            font-size: 1rem;

            &:hover {
              background-color: black;
              color: #fff;
            }

          }

        }

      }

      .images {
        display: grid;
        grid-template-columns: 26% 26% 26% auto;
        text-align: left;
        color: white;
        font-weight: "Alata";

        div {
          margin: 35px 0;

          &:hover {
            box-shadow: 0 2px 15px black;

          }
        }    

        #earth {
          box-sizing: border-box;
          padding: 375px 0 0 30px;
          height: 450px;
          width: 256px;
          box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
          background-color: rgb(0, 0, 0);
          background-repeat: no-repeat;
          background-image: url("../../assets/images/desktop/image-deep-earth.jpg");

          h3 {
            width: 20px;
            font-size: 1.5rem;
          }

          &:hover {
            box-shadow: 0 3px 26px rgba(0, 0, 0, 0.40);
          }
        }

        #arcade {
          box-sizing: border-box;
          padding: 375px 0 0 30px;
          height: 450px;
          width: 256px;
          box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
          background-color: rgba(0, 0, 0, 0.308);
          background-image: url("../../assets/images/desktop/image-night-arcade.jpg");
          background-repeat: no-repeat;

          &:hover {
            box-shadow: 0 3px 26px rgba(0, 0, 0, 0.40);
          }

          h3 {
            width: 20px;
            font-size: 1.5rem;
          }
        }

        #soccer {
          box-sizing: border-box;
          padding: 375px 0 0 30px;
          height: 450px;
          width: 256px;
          box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
          background-color: rgba(0, 0, 0, 0.308);
          background-image: url("../../assets/images/desktop/image-soccer-team.jpg");
          background-size: 100%;
          background-repeat: no-repeat;

          &:hover {
            box-shadow: 0 3px 26px rgba(0, 0, 0, 0.40);
          }

          h3 {
            width: 130px;
            font-size: 1.5rem;
          }
        }

        #grid {
          box-sizing: border-box;
          padding: 375px 0 0 30px;
          height: 450px;
          width: 256px;
          box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
          background-color: rgba(0, 0, 0, 0.308);
          background-image: url("../../assets/images/desktop/image-grid.jpg");
          background-size: 100%;
          background-repeat: no-repeat;

          &:hover {
            box-shadow: 0 3px 26px rgba(0, 0, 0, 0.40);
          }

          h3 {
            width: 20px;
            font-size: 1.5rem;
          }
        }

        #above {
          box-sizing: border-box;
          padding: 375px 0 0 30px;
          height: 450px;
          width: 256px;
          box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
          background-color: rgba(0, 0, 0, 0.308);
          background-image: url("../../assets/images/desktop/image-from-above.jpg");
          background-size: 100%;
          background-repeat: no-repeat;

          &:hover {
            box-shadow: 0 3px 26px rgba(0, 0, 0, 0.40);
          }

          h3 {
            width: 130px;
            font-size: 1.5rem;
          }
        }

        #borealis {
          box-sizing: border-box;
          padding: 375px 0 0 30px;
          height: 450px;
          width: 256px;
          box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
          background-color: rgba(0, 0, 0, 0.308);
          background-image: url("../../assets/images/desktop/image-pocket-borealis.jpg");
          background-size: 100%;
          background-repeat: no-repeat;

          &:hover {
            box-shadow: 0 3px 26px rgba(0, 0, 0, 0.40);
          }

          h3 {
            width: 107px;
            font-size: 1.5rem;
          }
        }

        #curiosity {
          box-sizing: border-box;
          padding: 375px 0 0 30px;;
          height: 450px;
          width: 256px;
          box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
          background-color: rgba(0, 0, 0, 0.308);
          background-image: url("../../assets/images/desktop/image-curiosity.jpg");
          background-size: 100%;
          background-repeat: no-repeat;

          &:hover {
            box-shadow: 0 3px 26px rgba(0, 0, 0, 0.40);
          }

          h3 {
            width: 107px;
            font-size: 1.5rem;
          }
          
        }

        #fisheye {
          box-sizing: border-box;
          padding: 375px 0 0 30px;;
          height: 450px;
          width: 256px;
          box-shadow: inset 40em 0 rgba(0, 0, 0, 0.4);
          background-color: rgba(0, 0, 0, 0.308);
          background-image: url("../../assets/images/desktop/image-fisheye.jpg");
          background-size: 100%;
          background-repeat: no-repeat;

          &:hover {
            box-shadow: 0 3px 26px rgba(0, 0, 0, 0.40);
          }

          h3 {
            width: 107px;
            font-size: 1.5rem;
          }
        }
      }

      a:nth-child(4) {
        display: none;
      }

    }

  }

</style>