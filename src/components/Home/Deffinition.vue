<template>
<div class="deffiniton">
  <img src="../../assets/lego/definition.png" class="lego-defenition">
  <div class="container" style="clear: right">
    <div class="row">
      <div class="col-md-8 offset-md-2">
        <p class="paragraph">
          <span class="bold">Deffinition;</span>
          a practice or exercise to test or improve one's fitness for athletic competition, ability, or performance to exhaust (something, such as a mine) by working to devise, arrange, or achieve by resolving difficulties. Merriam-Webster.com Dictionary.
        </p>
        <p class="weekend">-weekend team</p>
        <div class="oval"></div>
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

.lego-defenition {
  float: right;
  width: 159px;
  height: 158px;
}

.deffiniton {
  height: 591px;
  background-color: #eebece;
  position: relative;
}

p {
  font-family: 'Work Sans';
  font-size: 21px;
  font-weight: 500;
  font-stretch: normal;
  font-style: normal;
  line-height: 1.52;
  letter-spacing: -0.75px;
  text-align: right;
  color: #000000;
}

.bold {
  font-family: 'Work Sans';
  font-weight: bold;
  color: #0b24fb;
}

.weekend {
  margin-top: 30px;
  font-weight: 600;
  font-stretch: normal;
  font-style: italic;
  line-height: normal;
  letter-spacing: normal;
  text-align: right;
  color: #ffffff;
}

.oval {
  width: 89px;
  height: 89px;
  object-fit: contain;
  background-color: #0b24fb;
  border-radius: 50px;
  margin-top: 38px;
  margin-left: -40px;
  margin-bottom: 70px;
}

@media screen and (max-width: 575px) {
  p {
    font-size: 16px;
  }

  .paragraph {
    margin-top: 63px;
  }

  .weekend {
    margin-top: 20px;
  }

  .oval {
    margin-left: 20px;
  }
}

</style>
