<template>
  <div class="calculator">
    <div class="display"/>
    <button>C</button>
    <button>+/-</button>
    <button>%</button>
    <button>÷</button>
    <button>7</button>
    <button>8</button>
    <button>9</button>
    <button>x</button>
    <button>4</button>
    <button>5</button>
    <button>6</button>
    <button>-</button>
    <button>1</button>
    <button>2</button>
    <button>3</button>
    <button>+</button>
    <button>0</button>
    <button>.</button>
    <button>=</button>
    <button>?</button>
  </div>
<!--  <div class="emptySpace"/>-->
</template>

<script>
export default {
  name: 'Calculator',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.calculator {
  display: grid;
  background-color:#879bf4;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(40px, auto);
  border-radius: 10px;
  box-shadow: 3px 5px 5px rgba(0, 0, 0, 0.2);
  width: 30%;
}

button {
  border-radius: 0px;
  border-width: 1px;
  border-color: white;
  background-color: transparent;
  color: white;
}

.display {
  grid-column: 1/5;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  background-color: white;

}
</style>
