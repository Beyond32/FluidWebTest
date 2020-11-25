<template>
        <section>
            <div class="location-bg">
              <div class="location-block">
                <div class="location-header">
                  <h1>Locations</h1>
                  <div class="locations-underline"></div>
                </div>
                <div class="locations-box">
                  <div class="locations-first-block">
                    <div class="locatins-loc-block"><img src="/img/locations-icon.png" alt="">
                      <h1>indiranagar</h1></div>
                    <p>218, Double Rd, <br>
                      Near BDA Complex, Indiranagar</p>
                    <div class="location-call-block"><img src="../img/locations-call.png" alt=""><h1>9402393493</h1></div>
                    <img src="../img/locations-first.jpg" alt="">
                  </div>
                  <div class="locations-first-block">
                    <div class="locatins-loc-block"><img src="../img/locations-icon.png" alt="">
                      <h1>indiranagar</h1></div>
                    <p>218, Double Rd, <br>
                      Near BDA Complex, Indiranagar</p>
                    <div class="location-call-block"><img src="../img/locations-call.png" alt=""><h1>9402393493</h1></div>
                    <img src="../img/locations-first.jpg" alt="">
                  </div>
                </div>
              </div>
              <!--  -->
              <div class="sign-up-box">
                <h1>join our eat well, be well <br>
                  culture </h1>
                  <div class="input-block">
                    <input type="text"> 
                    <button>sign me up</button>
                  </div>
              </div>
            </div>
        </section>
</template>

<style lang="scss" scoped>
.location-bg {
  background: url("../img/location-bg.jpg");
  height: 1250px;
}
.location-block {
  position: relative;
  top: -50px;
  z-index: 5;
  width: 1650px;
  background-color: white;
  margin: auto;
  border-radius: 10px;
}
.location-header {
  display: flex;
  flex-direction: column;
  align-items: center;
  & h1 {
    font-size: 210px;
    font-family: "AthenaOfTheOcean";
    color: black;
    font-weight: normal;
  }
}
.locations-underline {
  background-color: #fc4263;
  width: 140px;
  height: 5px;
  border-radius: 10px;
  position: relative;
  top: -10px;
  right: -100px;
}
.locations-box {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  padding-bottom: 30px;
}
.locations-first-block {
  display: flex;
  flex-direction: column;
  align-items: center;
  & p {
    font-size: 30px;
    color: #878787;
    font-family: "Montserrat-regular";
    text-align: center;
    margin-bottom: 25px;
  }
}
.locatins-loc-block {
  display: flex;
  margin-bottom: 25px;
  align-items: center;
  & img {
    margin-right: 15px;
  }
  & h1 {
    text-transform: uppercase;
    color: #878787;
    font-size: 30px;
    font-family: "Montserrat";
  }
}
.location-call-block {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-bottom: 30px;
  & img {
    margin-right: 15px;
  }
  & h1 {
    color: #878787;
    font-size: 30px;
    font-family: "Montserrat";
  }
}

//
.sign-up-box {
  & h1 {
    text-transform: uppercase;
    font-size: 60px;
    font-family: "Montserrat";
    color: white;
    text-align: center;
    margin-bottom: 90px;
  }
}
.input-block {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: center;
  & input {
    background-color: #6f6f70;
    opacity: 70%;
    min-width: 900px;
    height: 95px;
    border-radius: 10px;
    font-size: 30px;
    font-family: "Montserrat";
    font-weight: normal;
    color: white;
    margin-right: 45px;
  }
  & button {
    padding: 30px 70px;
    font-size: 28px;
    font-family: "Montserrat";
    background-color: #fc4263;
    border-radius: 10px;
    text-transform: uppercase;
    color: White;
  }
}
</style>

<script>
export default {
  
}
</script>