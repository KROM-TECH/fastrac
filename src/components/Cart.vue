<template>
  <div class="product">
    <div class="product__img"><img src="img/products/7.png" alt="" /></div>
    <h3 class="product__title">Discount On Sports Equipment and lots of cool stuff</h3>
    <span class="product__price">$42.00</span>
    <div class="row">
  <button type="button" class="product__add"></button>
    <button type="button" class="product__add"></button>
    <button type="button" class="product__add"></button>
    </div>
  
  </div>
</template>

<script>
  export default {
    name: 'Cart',
    data() {
      return {};
    }
  };
</script>

<style >
button{
  outline: none !important;
    margin-top: 30px;
    background-color: rgb(240, 240, 240);
    box-shadow: rgba(0, 0, 0, 0.07) 15px 15px 30px 0px, rgba(255, 255, 255, 0.8) -15px -15px 30px 0px;
  transition: all 0.6s ease 0s;
   display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
        margin-top: 1rem !important;
    border-radius: 1rem !important;
    border: 1px solid black !important;
}
  .product__add {
    /* position: absolute; */
    z-index: 3;
     margin: 0px 3px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    right: 30px;
    bottom: 30px;
    width: 52px;
    height: 52px;
    line-height: 52px;
    box-shadow: rgba(0, 0, 0, 0.1) 8px 8px 20px 0px, rgba(255, 255, 255, 0.9) -8px -8px 20px 0px;
    background-color: rgb(240, 240, 240);
    border-radius: 50%;
    transition: all 0.6s ease 0s;
  }

  .product__price {
    position: relative;
    z-index: 2;
    color: rgba(55, 55, 55, 0.8);
    line-height: 100%;
    font-size: 14px;
    font-family: Spartan, sans-serif;
    font-weight: 500;
  }
  .product__title {
    position: relative;
    z-index: 2;
    color: rgb(55, 55, 55);
    font-weight: 600;
    line-height: 140%;
    margin-bottom: 15px;
    font-size: 16px;
    padding-right: 50px;
  }
  .product__img img {
    width: 100%;
    height: auto;
  }

  img {
    vertical-align: middle;
    border-style: none;
  }
  .product__img {
    position: relative;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: auto;
    background-color: transparent;
    margin-bottom: auto;
    border-radius: 10px;
    overflow: hidden;
  }
  .product {
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    align-items: flex-start;
    height: 300px;
    margin-top: 30px;
    background-color: rgb(240, 240, 240);
    box-shadow: rgba(0, 0, 0, 0.07) 15px 15px 30px 0px, rgba(255, 255, 255, 0.8) -15px -15px 30px 0px;
    border-radius: 30px;
    padding: 30px;
  }
</style>
