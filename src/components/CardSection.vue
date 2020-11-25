<template>
   <section>
      <div class="card-block-section-bg">
        <div class="card-block">
          <div class="card-block1">
            <div class="card-block-mini1">
              <h6>Reservations</h6>
              <p>
                Call us now to book a tale in our restaurant. Calls must be in the
                same days as the reservation
              </p>
              <a href="#">book a table</a>
            </div>
            <div class="card-block-mini1-img">
              
              <img src="../img/card-1-1-1.jpg" alt="#" />
            </div>
          </div>
          <div class="card-block2">
            <div class="card-block-mini2-img">
              
              <img src="../img/card-2-2-2-2.jpg" alt="#" />
            </div>
            <div class="card-block-mini2">
              <h6>About</h6>
              <p>
                Laibs’s Restaurant combines an inspired menu with a casually sophisticated setting in
                a historic downtown Excelsior main street building. Coalition is the creation of Chef Eli
                Wollenzien and reflects his passion for cooking with a diverse and inspired menu.
              </p>
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
.card-block {
  width: 1650px;
  border-radius: 10px;
  position: relative;
  top: -60px;
  display: flex;
  flex-direction: column;
  z-index: 5;
  -webkit-box-shadow: 0px 0px 18px -5px rgba(0, 0, 0, 0.5);
  box-shadow: 0px 0px 18px -5px rgba(0, 0, 0, 0.5);
  margin: 0px 135px;
}

.card-block1 {
  display: flex;
  background-color: white;
  border-radius: 10px 10px 0px 0px;
  height: 401px;
}
.card-block-mini1 {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: white;
  border-radius: 10px 10px 0px 0px;

  width: 600px;
  & h6 {
    font-size: 120px;
    font-family: "AthenaOfTheOcean";
    font-size: 168px;
    color: #fc4263;
    font-weight: normal;
    line-height: 130px;
  }
  & p {
    font-family: "Montserrat";
    font-size: 20px;
    font-weight: normal;
    color: #a7a7a7;
    text-align: center;
    padding: 25px 95px 25px 95px;
    line-height: 30px;
  }
  & a {
    padding: 25px 65px;
    font-size: 24px;
    border-radius: 5px;
    text-transform: uppercase;
    text-decoration: none;
    color: #fc4263;
    border: 2px solid #fc4263;
  }
}

.card-block2 {
  display: flex;
}
.card-block-mini2 {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: white;
  border-radius: 0px 0px 10px 0px;
  & h6 {
    font-size: 160px;
    font-family: "AthenaOfTheOcean";
    font-size: 168px;
    color: #fc4263;
    font-weight: normal;
  }
  & p {
    font-family: "Montserrat";
    font-size: 20px;
    font-weight: normal;
    color: #a7a7a7;
    text-align: center;
    padding: 25px 75px 25px 75px;
    line-height: 30px;
  }
}
.card-block-mini2-img {
  & img {
    border-radius: 0px 0px 0px 10px;
  }
}
</style>

<script>
export default {
  
}
</script>