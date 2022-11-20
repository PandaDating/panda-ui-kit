<template>
  <main class="page">
    <router-view />
  </main>
</template>

<style lang="scss">
@import "./styles/panda.scss";

.colors {
  padding: 30px;

  & > div {
    width: 200px;
    height: 50px;
    border-radius: 2px;
    margin-bottom: 10px;
  }
}

.pink {
  background-color: $pink_color;
}

.pink-light {
  background-color: $pink_light_color;
}

.purple {
  background-color: $purple_color;
}

.blue {
  background-color: $blue_color;
}

.grey {
  background-color: $grey_color;
}

.turquoise {
  background-color: $turquoise_color;
}
</style>
