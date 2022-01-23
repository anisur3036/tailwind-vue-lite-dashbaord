<template>
  <div class="">
    <h2>This is Range</h2>
    <input class="appearance-none bg-transparent cursor-pointer w-[15rem]" type="range" name="value-slider">
  </div>
</template>
<style scoped>
  input[type="range"] {
   -webkit-appearance: none;
    appearance: none;
    background: transparent;
    cursor: pointer;
    width: 15rem;
  }
  input[type="range"]::-webkit-slider-runnable-track {
    background:  #053a5f;
    height:  0.5rem;
  }
  input[type="range"]::-moz-range-track {
    background:  #053a5f;
    height:  0.5rem;
  }
  input[type="range"]::-webkit-slider-thumb {
    -webkit-appearance:  none;
    appearance:  none;
    margin-top: -12px;
    background-color: #5cd5eb;
    height:  2rem;
    width:  1rem;
  }
  input[type="range"]:focus::-webkit-slider-thumb {
    border:  1px solid #053a5f;
    outline:  3px solid #053a5f;
    outline-offset: 0.125rem;
  }
  input[type="range"]::-moz-range-track {
    background-color: #053a5f;
    border-radius: 0.5rem;
    height: 0.5rem;
  }
  input[type="range"]::-moz-range-thumb {
    border:  none;
    border-radius: 0;
    background-color: #5cd5eb;
    height: 2rem;
    width:  1rem;
  }
  input[type="range"]:fucus::-moz-range-thumb {
    border:  1px solid #053a5f;
    outline:  3px solid #053a5f;
    outline-offset: 0.125rem;
  }
</style>
