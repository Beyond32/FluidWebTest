<template>
   <section>
          <div class="menu-bg-block">
            <img class="pizza-bg-png" src="../img/pizza.png" alt="">
            <div class="menu-list-general">
              <div class="menu-list-header-block">
                <div class="menu-list-header">
                  <h1>Menu</h1>
                  <div class="menu-list-underline"></div>
                  <p>food and appetizers</p>
                </div>
                <div class="menu-list-big-section">
                  <div class="menu-list-two-sections">
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                  </div>
                  <div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                  </div>
                </div>
                <!--  -->
                <div class="middle-p"><p>deserts</p></div>

                <div class="menu-list-big-section">
                  <div class="menu-list-two-sections">
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                  </div>
                  <div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                    <div class="menu-list-section-overlay">
                      <div class="menu-list-section">
                        <h4>pizza mexicana</h4>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                          elit. Nam vehicula massa quis _____________________</p>
                      </div>
                      <div><h1 class="menu-list-value">₹199</h1></div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
</template>

<style lang="scss" scoped>

.menu-bg-block {
  background: url("../img/menu-bg.jpg");
  height: 1710px;
}
.pizza-bg-png {
  display: block;
  position: relative;
  top: -155px;
  left: 0px;
}
.menu-list-general {
  position: relative;
  top: -480px;
}
.menu-list-header {
  display: flex;
  flex-direction: column;
  align-items: center;

  & h1 {
    font-size: 210px;
    font-family: "AthenaOfTheOcean";
    font-weight: normal;
  }
  & p {
    color: #878787;
    font-size: 30px;
    text-transform: uppercase;
    font-family: "Montserrat";
    padding-top: 40px;
  }
}
.menu-list-underline {
  background-color: #fc4263;
  height: 5px;
  width: 138px;
  border-radius: 10px;
}
.menu-list-header-block {
  position: relative;
  top: 0px;
}
.menu-list-big-section {
  margin-top: 60px;
  display: flex;
  justify-content: center;
}
.menu-list-two-sections {
  margin-right: 110px;
}
.menu-list-section-overlay {
  display: flex;
  flex-direction: row;
  margin-bottom: 55px;
  &:last-child {
    margin-bottom: 0px;
  }
}
.menu-list-section {
  & h4 {
    font-size: 27px;
    color: black;
    font-family: "Montserrat";
    text-transform: uppercase;
  }
  & p {
    font-size: 18px;
    font-family: "Montserrat-regular";
    color: #393939;
    padding-top: 20px;
  }
}
.menu-list-value {
  color: #fc4263;
  font-size: 85px;
  font-family: "Montserrat-bold";
  text-transform: uppercase;
}
.middle-p {
  color: #878787;
  font-size: 30px;
  text-transform: uppercase;
  font-family: "Montserrat";
  margin-top: 100px;
  text-align: center;
}
</style>

<script>
export default {
  
}
</script>