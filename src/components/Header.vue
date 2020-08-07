<template>
  <div class="header">
    <div class="container">
      <div class="row">
        <div class="logo">
          <img src="../assets/fastrac.png" alt="logo" />
          <h6 class="header__tagline">Buy, Sell, Negotiate, Customize</h6>
        </div>
        <div class="headerIconHolder">
          <div class="headerIcon">
            <span class="material-icons-outlined">
              shopping_cart
            </span>
          </div>
          <div class="headerIcon"><span class="material-icons-outlined">
person
</span></div>
          <div class="headerIcon"><span class="material-icons-outlined">
share
</span></div>
        </div>
      </div>
    </div>
    <!-- <input type="text"> -->
  </div>
</template>

<script>
  export default {
    name: 'Header'
  };
</script>

<style scoped>
  /* .form__group {
    position: relative;
    z-index: 2;
    margin-top: 30px;
    height: 52px;
    width: 100%;
}
input{
  width: 100%;
    height: 52px;
    background-color: rgb(240, 240, 240);
    box-shadow: rgba(255, 255, 255, 0.7) -4px -4px 8px 0px inset, rgba(0, 0, 0, 0.05) 4px 4px 8px 0px inset;
    font-size: 14px;
    color: rgb(55, 55, 55);
    position: relative;
    border-radius: 30px;
    border-width: initial;
    border-style: none;
    border-color: initial;
    border-image: initial;
    padding: 0px 30px;
    transition: all 0.6s ease 0s;
} */
  .row {
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
  .header__tagline {
    display: block;
    font-size: 15px;
    color: rgb(203, 70, 37);
    margin-left: 30px;
    line-height: 21px;
    text-transform: uppercase;
    text-align: end;
    font-style: italic;
  }
  .headerIconHolder {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    /* margin-left: auto; */
    transition: all 0.6s ease 0s;
  }
  .headerIcon {
    border: 1px solid #d7892a;
    margin: 0px 3px;
    height: 52px;
    width: 52px;
    background-color: rgb(240, 240, 240);
    box-shadow: rgba(0, 0, 0, 0.06) 8px 8px 20px 0px, rgb(255, 255, 255) -8px -8px 20px 0px;
    color: rgb(55, 55, 55);
    border-radius: 30px;
    transition: all 0.6s ease 0s;
        display: flex;
    justify-content: center;
    align-items: center;
    color: #cb4625;
  }
  .headerIcon:hover {
    border: 1px solid #cb4625;
  }
  .header {
    margin-top: 5px;
  }
  .logo {
    max-width: 100%;
    height: auto;
  }
</style>
