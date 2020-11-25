<template>
  <section>
        <div class="card-block-section-bg">
          <div class="block-menu-general">
            <div class="block-menu-general-mini-first">
              <div class="menu-block-first">
                <div class="menu-block-first-text  ">
                  <h1>lasagna</h1>
                  <p>Lorem Ipsum is simply
                    dummy text of the printing
                    and typesetting industry.</p>
                    <h6>from ₹200</h6>
                </div>
                <div>
                  <img src="../img/lasagna.jpg" alt="">
                </div>
              </div>
              <div class="menu-block-first">
                <div class="menu-block-first-text">
                  <h1>lasagna</h1>
                  <p>Lorem Ipsum is simply
                    dummy text of the printing
                    and typesetting industry.</p>
                    <h6>from ₹200</h6>
                </div>
                <div>
                  <img src="../img/pizza.jpg" alt="">
                </div>
              </div>
            </div>
            <!--  -->
            <div class="block-menu-general-mini-second">
              <div class="menu-block-first">
                <div>
                  <img src="../img/idlis.jpg" alt="">
                </div>
                <div class="menu-block-first-text">
                  <h1>lasagna</h1>
                  <p>Lorem Ipsum is simply
                    dummy text of the printing
                    and typesetting industry.</p>
                    <h6>from ₹200</h6>
                </div>
              </div>
              <div class="menu-block-first">
                <div>
                  <img src="../img/burger.jpg" alt="">
                </div>
                <div class="menu-block-first-text">
                  <h1>lasagna</h1>
                  <p>Lorem Ipsum is simply
                    dummy text of the printing
                    and typesetting industry.</p>
                    <h6>from ₹200</h6>
                </div>
                
              </div>
            </div>
          </div>
        </div>
        
      </section>
</template>

<style lang="scss" scoped>
.card-block-section-bg {
  height: 690px;
}
.block-menu-general {
  width: 1650px;
  position: relative;
  z-index: 5;
  margin: 0px 135px;
  top: -70px;
}
.block-menu-general-mini-first {
  display: flex;
  height: 410px;
  overflow: hidden;
  border-radius: 10px 10px 0px 0px;
}
.block-menu-general-mini-second {
  display: flex;
  height: 415px;
  overflow: hidden;
  border-radius: 0px 0px 10px 10px;
}

.menu-block-first {
  display: flex;
}
.menu-block-first-text {
  text-align: center;
  background-color: white;

  & h1 {
    padding-top: 95px;
    text-transform: uppercase;
    color: black;
    font-size: 30px;
    font-family: "Montserrat-bold";
    font-weight: bold;
  }
  & p {
    color: #757575;
    padding: 40px 25px;
    font-size: 24px;
    font-family: "Montserrat-regular";
    line-height: 40px;
  }
  & h6 {
    font-size: 25px;
    text-transform: uppercase;
    color: #fc4263;
    font-family: "Montserrat-bold";
  }
}
</style>

<script>
export default {
  
}
</script>