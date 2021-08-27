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
        <h2>OUR CREATIONS</h2>

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
}
</style>