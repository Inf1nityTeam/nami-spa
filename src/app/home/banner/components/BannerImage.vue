<template>
  <div class="banner-image">
    <h2>японская еда</h2>
    <img src="@/assets/images/main/banner/banner-image.png" alt="">
  </div>
</template>

<script>
export default {
  name: 'banner-image'
}
</script>

<style scoped lang="scss">
.banner-image {
  margin-top: 100px;
  @media screen and (max-width: 770px) {
    margin-top: 0;
  }

  h2 {
    margin-bottom: 0;
    font-family: Neucha, sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 40px;
    line-height: 44px;

    letter-spacing: 0.08em;
    text-transform: uppercase;

    color: #FFFFFF;

    @media screen and (max-width: 1060px) {
      font-size: 36px;
    }

  }

  h3 {
    position: absolute;
    top: 50px;
    left: 130px;

    font-family: Kalam, sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 95px;
    line-height: 151px;
    text-align: center;
    text-transform: uppercase;

    color: #F4F4F4;

    text-shadow: 15px 12px 37px #000000;

    @media screen and (min-height: 836px) {
      top: 75px;
    }
    @media screen and (min-height: 900px) {
      top: 100px;
    }
    @media screen and (min-height: 936px) {
      top: 120px;
    }
    @media screen and (min-height: 975px) {
      top: 160px;
    }
    @media screen and (min-height: 1050px) {
      top: 180px;
    }

    @media screen and (min-width: 1250px) and (max-height: 820px) {
      font-size: 75px;
    }
    @media screen and (max-width: 1250px) {
      font-size: 90px;
    }
    @media screen and (max-width: 1100px) {
      top: 70px;
      left: 110px;
      font-size: 74px;
    }
    @media screen and (max-width: 920px) {
      top: 70px;
      left: 100px;
      font-size: 65px;
    }
    @media screen and (max-width: 768px) {
      top: -20px;
      left: 340px;
      font-size: 10vw;
    }
    @media screen and (max-width: 650px) {
      left: 320px;
    }
    @media screen and (max-width: 620px) {
      top: -40px;
      left: 310px;
    }
    @media screen and (max-width: 600px) {
      left: 0;
      right: 0;
    }

  }

  img {
    @media screen and (min-width: 1250px) and (max-height: 820px) {
      width: 550px;
      object-fit: contain;
    }
    @media screen and (max-width: 1250px) {
      width: 600px;
      object-fit: contain;
    }
    @media screen and (max-width: 1100px) {
      width: 550px;
      object-fit: contain;
    }
    @media screen and (max-width: 1100px) {
      //margin-top: 30px;
      width: 500px;
      object-fit: contain;
    }
    @media screen and (max-width: 920px) {
      width: 450px;
      object-fit: contain;
    }
    @media screen and (max-width: 840px) {
      width: 420px!important;
      object-fit: contain;
    }

    @media screen and (max-width: 770px) {
      width: 500px!important;
    }
    @media screen and (max-width: 480px) {
      width: 400px!important;
    }
    @media screen and (max-width: 420px) {
      width: 360px!important;
    }
    @media screen and (max-width: 360px) {
      width: 340px!important;
    }

    @media screen and (max-width: 1250px) and (max-height: 820px) {
      margin-top: -20px;
      width: 550px;
      @media screen and (max-width: 980px) {
        width: 450px;
      }
    }
    @media screen and (max-width: 1000px) and (max-height: 700px) {
      margin-top: -20px;
      width: 500px;
      @media screen and (max-width: 770px) {
        width: 450px!important;
      }
      @media screen and (max-width: 480px) {
        width: 400px!important;
      }
      @media screen and (max-width: 420px) {
        width: 360px!important;
      }
      @media screen and (max-width: 360px) {
        width: 340px!important;
      }
    }
  }
}
</style>
