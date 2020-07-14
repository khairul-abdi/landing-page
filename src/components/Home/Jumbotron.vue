<template>
  <div class="jumbotron jumbotron-fluid img-responsive center-block">
    <div class="container">
      <h1 class="display-4">
       WEEKEND FROM HOME
      </h1>
      <p class="description">Stay active with a little workout.</p>
      <img src="../../assets/lego/lego-jumbotron.png" class="lego-jumbotron">
      <a href="" class="tombol">Let`s Go</a>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>

.jumbotron {
  background-color: #eebece;
  background-image: url('../../assets/bg/bg-1.png');
  background-size: cover;
  height: 732px;
  text-align: center;
  margin: 0 auto;
}

.jumbotron .container {
  position: relative;
  z-index: 1;
}

.jumbotron .display-4 {
  font-family: 'Work Sans';
  color: white;
  margin-top: 67px;
  font-weight: 200;
  text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.7);
  font-size: 62px;
  margin-bottom: 30px;
  font-weight: 900;
  font-stretch: normal;
  font-style: normal;
  line-height: 0.82;
  letter-spacing: normal;
}

.description {
  font-family: 'Work Sans';
  font-size: 16px;
  font-weight: 600;
  font-stretch: normal;
  font-style: italic;
  line-height: normal;
  letter-spacing: normal;
  text-align: center;
  color: #ffffff;
  margin-top: 20px;
}

.lego-jumbotron {
  margin-top: 67px;
  object-fit: contain;
}

.tombol {
  position: absolute;
  margin-top: 270px;
  margin-left: -205px;
  z-index: 999;
  align-items: center;
  padding: 19px 80px;
  width: 231px;
  height: 58px;
  border-radius: 29px;
  box-shadow: 0 20px 30px 0 rgba(249, 131, 171, 0.5);
  background-color: #ffffff;
  text-decoration: none;
  color: #000000;
  font-family: 'Work Sans';
  font-size: 16px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  letter-spacing: normal;
}

@media screen and (max-width: 575px) {
  .media {
    padding: 0 24px;
  }

  .jumbotron .display-4 {
    font-size: 52px;
  }

}
</style>
