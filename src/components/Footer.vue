<template>
       <footer>
            <div class="footer-social-links">
              <div>
                <div class="socials-links-icons">
                  <a href="#"><img src="../img/social-links-facebook.png" alt=""></a>
                  <a href="#"><img src="../img/social-links-facebook.png" alt=""></a>
                  <a href="#"><img src="../img/social-links-facebook.png" alt=""></a>
                  <a href="#"><img src="../img/social-links-facebook.png" alt=""></a>
                </div>
                <div class="footer-social-menu">
                  <a href="#">home</a>
                  <a href="#">menu</a>
                  <a href="#">story</a>
                  <a href="#">about</a>
                  <a href="#">locations</a>
                </div>
                <div class="footer-social-menu-second">
                  <a href="#">contact</a>
                  <div class="footer-social-menu-second-line"></div>
                  <a href="#">blog</a>
                  <div class="footer-social-menu-second-line"></div>
                  <a href="#">catering</a>
                  <div class="footer-social-menu-second-line"></div>
                  <a href="#">delivery</a>
                </div>
              </div>
            </div>
            <div class="copyright">
              <h6>HEALTHY MEXICAN FAST-CASUAL FOOD, CRAFTED WITH <img src="../img/LOVE_INDIA.png" alt="">    in india</h6>
              <p>	&copy; all rights reserved</p>
            </div>
        </footer>
</template>

<style lang="scss" scoped>
.footer-social-links {
  background-color: #272727;
  height: 445px;
  padding-top: 130px;
}
.socials-links-icons {
  display: flex;
  justify-content: center;
  margin-bottom: 50px;
  & a {
    margin-right: 40px;
    & img {
      display: block;
      width: 65px;
      height: auto;
    }
  }
  & :last-child {
    margin-right: 0px;
  }
}
.footer-social-menu {
  display: flex;
  justify-content: center;
  margin-bottom: 35px;
  & a {
    color: white;
    text-transform: uppercase;
    text-decoration: none;
    margin-right: 80px;
    font-size: 24px;
    font-family: "Montserrat";
  }
  & :last-child {
    margin-right: 0px;
  }
}
.footer-social-menu-second {
  display: flex;
  justify-content: center;
  align-items: center;
  & a {
    text-decoration: none;
    color: white;
    text-transform: uppercase;
    font-family: "Montserrat-regular";
    font-size: 20px;
  }
}
.footer-social-menu-second-line {
  background-color: white;
  height: 20px;
  width: 2px;
  margin: 0px 30px;
}
.copyright {
  height: 150px;
  background-color: black;
  padding-top: 45px;
  display: flex;
  flex-direction: column;
  align-items: center;
  & h6 {
    text-transform: uppercase;
    color: white;
    font-family: "Montserrat-regular";
    font-size: 26px;
    font-weight: normal;
    margin-bottom: 25px;
  }
  & p {
    color: white;
    text-transform: uppercase;
    font-size: 20px;
  }
}

</style>

<script>
export default {
  
}
</script>