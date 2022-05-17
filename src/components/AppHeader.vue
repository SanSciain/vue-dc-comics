<template>
  <div class="container">
    <div class="container__img">
      <img src="../assets/img/dc-logo.png" alt="logo" />
    </div>
    <div class="container__menu">
      <ul>
        <li
          v-for="(item, index) in navItems"
          :key="index"
          :class="{ active: item.active }"
        >
          <a href="">{{ item.text }}</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
  data: function () {
    return {
      navItems: [
        {
          text: "characters",
          active: false,
        },
        {
          text: "comics",
          active: true,
        },
        {
          text: "movies",
          active: false,
        },
        {
          text: "tv",
          active: false,
        },
        {
          text: "games",
          active: false,
        },
        {
          text: "collectibles",
          active: false,
        },
        {
          text: "videos",
          active: false,
        },
        {
          text: "fans",
          active: false,
        },
        {
          text: "news",
          active: false,
        },
        {
          text: "shop",
          active: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.container {
  &__img {
    width: 70px;
  }

  &__menu {
    ul {
      display: flex;
      justify-content: space-evenly;
    }

    li {
      display: inline-block;
      padding: 1rem 0.5rem;
      color: black;

      a {
        font-size: 0.8rem;
        text-transform: uppercase;
        font-weight: bold;
        color: inherit;
      }

      &.active {
        color: blue;
        border-bottom: 4px solid blue;
      }
    }
  }
}
</style>
