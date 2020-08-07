<template>
  <div id='app'>
    <Header/>
    <carousel/>
    <!-- <Cart /> -->
    <button type="button">Register as a Vendor</button>

  </div>
</template>

<script>
  // import Cart from './components/Cart.vue';
  import Header from './components/Header.vue';
  import Carousel from './components/Carousel.vue';
  export default {
    name: 'app',
    components: {
      // Cart,
      Header,
      Carousel
    }
  };
</script>

<style>
#app{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
button{
  outline: none !important;
  width: fit-content;
    height: 52px;
    background-color: rgb(240, 240, 240);
    box-shadow: rgba(255, 255, 255, 0.7) -4px -4px 8px 0px inset, rgba(0, 0, 0, 0.05) 4px 4px 8px 0px inset;
    font-size: 14px;
  transition: all 0.6s ease 0s;
   display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
        margin-top: 1rem !important;
    border-radius: 1rem !important;
    border: 1px solid #d7892a !important;
    color: #cb4625;
}
@font-face {
  font-family: 'Material Icons Outlined';
  font-style: normal;
  font-weight: 400;
  src: url(https://fonts.gstatic.com/s/materialiconsoutlined/v22/gok-H7zzDkdnRel8-DQ6KAXJ69wP1tGnf4ZGhUce.woff2) format('woff2');
}
.material-icons-outlined {
  font-family: 'Material Icons Outlined';
  font-weight: normal;
  font-style: normal;
  font-size: 32px;
  line-height: 1;
  letter-spacing: normal;
  text-transform: none;
  display: inline-block;
  white-space: nowrap;
  word-wrap: normal;
  direction: ltr;
  -webkit-font-feature-settings: 'liga';
  -webkit-font-smoothing: antialiased;
}
  body {
    font-family: 'Open Sans', sans-serif;
    font-weight: 400;
    background-color: rgb(240, 240, 240) !important;
    -webkit-font-smoothing: antialiased;
    text-size-adjust: 100%;
    color: rgb(55, 55, 55);
    text-shadow: none;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
  button{
    border: none;
    outline: none;
  }

  .container {
    width: 100%;
 
  }

  @media (min-width: 576px) {
    .container {
      max-width: 540px;
    }
  }

  @media (min-width: 768px) {
    .container {
      max-width: 720px;
    }
  }
  @media (min-width: 992px) {
    .container {
      max-width: 960px;
    }
  }

  .row {
    display: flex;
    flex-wrap: wrap;

}

  #nav {
    padding: 30px;
  }

  #nav a {
    font-weight: bold;
    color: #2c3e50;
  }

  #nav a.router-link-exact-active {
    color: #42b983;
  }
</style>
