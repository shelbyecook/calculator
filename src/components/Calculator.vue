<template>
  <div class="calculator">
    <h1>{{ msg }}</h1>
    <div class="display"></div>
    <div style="font-weight: bold">C</div>
    <div style="font-size: 18px">+/-</div>
    <div style="font-size: 18px">%</div>
    <div style="font-size: 22px">÷</div>
    <div>7</div>
    <div>8</div>
    <div>9</div>
    <div style="font-size: 18px">x</div>
    <div>4</div>
    <div>5</div>
    <div>6</div>
    <div style="font-size: 18px">-</div>
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>+</div>
    <div>0</div>
    <div>.</div>
    <div style="font-size: 18px">=</div>








  </div>
</template>

<script>
export default {
  name: 'Calculator',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*h1 {*/
/*  font-size: 10px;*/
/*  text-align: center;*/
/*}*/

.calculator {
  display: grid;
  background-color:orange;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(20px, auto);
}

.display {
  grid-column: 1/5;
  background-color: blue;
}
</style>
