<template>
  <footer>
    <div class="footer__upper">
      <div class="container">
        <div class="menu">
          <div class="submenu">
            <h4>Lorem ipsum</h4>
            <ul>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
            </ul>
          </div>
          <div class="submenu">
            <h4>Lorem ipsum</h4>
            <ul>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
            </ul>
          </div>
          <div class="submenu">
            <h4>Lorem ipsum</h4>
            <ul>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
            </ul>
          </div>
          <div class="submenu">
            <h4>Lorem ipsum</h4>
            <ul>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
              <li><a href="">Lorem</a></li>
            </ul>
          </div>
        </div>

        <div class="img-container">
          <img src="../assets/img/dc-logo-bg.png" alt="" />
        </div>
      </div>
    </div>

    <div class="footer__bottom">
      <div class="container">
        <a href="" class="btn">SING-UP NOW</a>
        <div class="icons">
          <span>FOLLOW US</span>
          <div class="img-container">
            <img src="../assets/img/footer-facebook.png" alt="" />
          </div>
          <div class="img-container">
            <img src="../assets/img/footer-periscope.png" alt="" />
          </div>
          <div class="img-container">
            <img src="../assets/img/footer-pinterest.png" alt="" />
          </div>
          <div class="img-container">
            <img src="../assets/img/footer-twitter.png" alt="" />
          </div>
          <div class="img-container">
            <img src="../assets/img/footer-youtube.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style lang="scss" scoped>
footer {
  background-image: url("../assets/img/footer-bg.jpg");

  .footer__upper {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 350px;
    overflow: hidden;

    .container {
      height: 100%;

      .menu {
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        height: 100%;
        padding: 2rem 0;

        .submenu {
          h4 {
            color: white;
            font-weight: bold;
            margin: 0.5rem;
          }
          ul {
            li {
              a {
                color: grey;
                font-size: 0.8rem;
              }
            }
          }
        }
      }

      .img-container {
        width: 450px;
      }
    }
  }

  .footer__bottom {
    background-color: rgb(88, 87, 87);

    .btn {
      color: white;
      padding: 1rem;
      margin: 2rem;
      border: 2px solid blue;
    }

    .icons {
      display: flex;
      align-items: center;

      span {
        color: blue;
        font-weight: bold;
        font-size: 1.2rem;
      }

      .img-container {
        margin-left: 1rem;
        width: 30px;
      }
    }
  }
}
</style>
