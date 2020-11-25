<template>
   <header class="header">
      <div class="header-logo-navbar">
        <div>
          <a class="logo">Laibas</a>
        </div>
        <div>
          <ul class="nav-bar">
            <a href="#">shop</a>
            <div class="elipse"></div>
            <a href="#">recipes</a>
            <div class="elipse"></div>
            <a href="#">news</a>
            <div class="elipse"></div>
            <a href="#">about laiba's</a>
            <div class="elipse"></div>
            <a href="#">contact</a>
          </ul>
        </div>
      </div>
      <div class="central-logo-block">
        <h1 class="central-logo">Laibas</h1>
        <h2 class="central-logo-text">rstaurant & bar</h2>
      </div>
    </header>
</template>

<style lang="scss" >
@import "../scss/main.scss";

.header {
  background: url("../img/home-screen.jpg") no-repeat center center fixed;
}

.header-logo-navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 47px 57px 0px 57px;
  line-height: 20px;
}

.logo {
  font-family: "AthenaOfTheOcean";
  font-size: 156px;
  color: white;
}

.nav-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  & a {
    font-size: 24px;
    color: white;
    text-decoration: none;
    font-family: "Montserrat";
    text-transform: uppercase;
  }
}

.elipse {
  width: 6px;
  height: 6px;
  background-color: white;
  border-radius: 50%;
  margin-right: 40px;
  margin-left: 40px;
}
.central-logo-block {
  padding-bottom: 310px;
}
.central-logo {
  font-size: 449px;
  text-align: center;
  color: white;
  font-family: "AthenaOfTheOcean";
  font-weight: normal;
}
.central-logo-text {
  font-size: 93px;
  font-family: "Montserrat";
  text-align: center;
  color: white;
  letter-spacing: 32px;
}
</style>


<script>
export default {
  
}
</script>