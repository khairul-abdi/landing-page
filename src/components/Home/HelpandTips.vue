<template>
  <div class="">
    <p class="title">Help & Tips</p>
    <div class="path"></div>
    <div class="container">
      <div class="row space">

        <div class="col-md-4 my-1">
          <div class="card bg-dark text-white">
            <img src="../../assets/bg/image1.png" class="card-img" alt="...">
            <div class="row card-img-overlay">
              <p class="col-10 card-text">Start quickly with simple steps</p>
              <div class="circle"><span class="arrow">&#9658;</span></div>
            </div>
          </div>
        </div>

        <div class="col-md-4 my-1">
          <div class="card bg-dark text-white">
            <img src="../../assets/bg/image2.png" class="card-img" alt="...">
            <div class="row card-img-overlay">
              <p class="col-10 card-text">Run smoothly at vero eos et accusamus</p>
              <div class="circle"><span class="arrow">&#9658;</span></div>
            </div>
          </div>
        </div>

        <div class="col-md-4 my-1">
          <div class="card bg-dark text-white">
            <img src="../../assets/bg/image3.png" class="card-img" alt="...">
            <div class="row card-img-overlay">
              <p class="col-10 card-text">Denounce with righteous indignation</p>
              <div class="circle"><span class="arrow">&#9658;</span></div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

  .container {
    margin-top: -130px;
  }

  .title {
    margin-top: 100px;
    font-size: 32px;
    font-weight: 900;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: normal;
    text-align: center;
    color: #ffffff;
  }

  .card {
    width: 311px;
    height: 176px;
    border: none;
  }

  .space {
    margin-left: 50px;
    margin-right: 75px;
  }

  .circle {
    cursor: pointer;
    padding-top: 4px;
    padding-left: 8px;
    width: 32px;
    height: 32px;
    border-radius: 50%;
    background-color: #ffffff;
  }

  .arrow {
    color: #0b24fb;
  }

  .card-img-overlay {
    bottom: -1px;
    top: auto;
    width: 311px;
    background-color: rgba(0,0,0, 0.5);
    height: 72px;
    margin-left: 0;
  }

  .col-10 {
    font-family: 'Work Sans';
    font-size: 16px;
    font-weight: bold;
    font-stretch: normal;
    font-style: normal;
    line-height: normal;
    letter-spacing: -0.57px;
    color: rgba(255, 255, 255, 1);
  }

  @media screen and (min-width: 992px) {
    .path {
      width: 159px;
      height: 195px;
      background-image: url("../../assets/bg/path-3.png");
      z-index: 5;
      margin-top: -50px;
      margin-left: 1120px;
    }
  }

  @media screen and (max-width: 575px) {

    .title {
      margin-top: 67px;
      margin-bottom: 170px;
    }

    .space {
      margin-left: 50px;
      margin-right: 75px;
    }

  }

</style>
