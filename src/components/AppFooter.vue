<template>
  <footer>
    <div class="footer__upper">
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

    <div class="footer__bottom"></div>
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
    height: 500px;

    .menu {
      display: flex;
      flex-direction: column;
      flex-wrap: wrap;

      .submenu {
        h4 {
          color: white;
          font-weight: bold;
          margin-bottom: 0.5rem;
        }
        ul {
          li {
            a {
              color: grey;
              font-size: 0.5rem;
            }
          }
        }
      }
    }
  }
}
</style>
