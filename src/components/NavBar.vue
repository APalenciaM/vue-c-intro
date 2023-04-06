<script>
export default {
  name: 'NavBar',
}
</script>

<template>
  <div id="NavBarDiv">
    <div id="IronhackLogoDiv">
      <img src="./icons/Ironhack_logo.png"/>
    </div>
    <div id="BurgerMenuDiv">
      <img src="./icons/Burger_menu.png"/>
    </div>
  </div>
</template>

<style scoped>

  #NavBarDiv {
    display: grid;

    margin-top: 20px;
  }

  #IronhackLogoDiv {
    grid-column: 1;
    margin-left: 30px

  }

  #BurgerMenuDiv {
    display: grid;
    grid-column: 2;
    justify-content: end;
    margin-right: 30px;

  }
</style>
