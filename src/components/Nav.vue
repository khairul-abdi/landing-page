<template>
  <div class="fixed-top">
    <div class="container">
      <div class="media">
        <div>
          <img src="../assets/nav/bitmap.png">
        </div>
        <div class="media-body  ml-2">
          <p class="Good-Morning">Good Morning</p>
          <p class="Fellas">Fellas</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.fixed-top {
  height: 67px;
  padding: 17px 0;
  background-color: #ffff;
}

.Good-Morning {
  width: 82px;
  height: 14px;
  font-family: WorkSans;
  font-size: 12px;
  font-weight: normal;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  letter-spacing: normal;
}

.Fellas {
  width: 47px;
  height: 19px;
  font-family: WorkSans;
  font-size: 16px;
  font-weight: bold;
  font-stretch: normal;
  font-style: normal;
  line-height: normal;
  letter-spacing: normal;
}

.col {
  margin: 17px 0;
}

p {
  margin: 0;
  padding: 0;
}

@media screen and (max-width: 575px) {
  .media {
    padding: 0 24px;
  }
}
</style>
