<template>
<div class="deffiniton">
  <img src="../../assets/lego/you-all-set.png" class="lego-defenition">
  <div class="container" style="clear: left">
    <div class="row">
      <div class="col-md-6 offset-md-3">
        <p class="title">You’re all set.</p>
        <p class="paragraph">
          The wise man therefore always holds in these matters to this principle of selection.
        </p>
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

.deffiniton {
  background-color: black;
}

.title {
  font-family: 'Work Sans';
  font-size: 32px;
  font-weight: 900;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  letter-spacing: normal;
  text-align: center;
  color: #ffffff;
  margin-top: 127px;
  margin-bottom: 30px;
}

.lego-defenition {
  position: absolute;
  float: left;
  width: 244px;
  height: 325px;
  top: auto;
  bottom: 51px;
}

p {
  font-family: 'Work Sans';
  font-size: 18px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.5;
  letter-spacing: -0.64px;
  text-align: center;
  color: #ffffff;
  margin-bottom: 203px;
}

@media screen and (max-width: 575px) {

  .deffiniton {
    height: 600px;
  }

  p {
    font-size: 16px;
    margin-top: 30px;
  }

  .title {
    margin-top: 67px;
  }

  .lego-defenition {
    position: absolute;
    float: left;
    width: 244px;
    height: 325px;
    bottom: -555px;
  }

}

</style>
