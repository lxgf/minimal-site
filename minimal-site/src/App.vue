<template>
  <TheBackGround />
  <TheHeader />
</template>

<script>
import TheBackGround from "./components/TheBackGround.vue";
import TheHeader from "./components/TheHeader.vue";
export default {
  components: {TheBackGround, TheHeader}
}
</script>

<style>
@import './assets/css/reset.css';

@font-face {
  font-family: 'Segoe UI';
  src: url('./assets/fonts/SegoeUI-Light.woff');
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('./assets/fonts/SegoeUI-BoldItalic.woff');
  font-weight: bold;
  font-style: italic;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('./assets/fonts/SegoeUI-SemiBold.woff');
  font-weight: 600;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('./assets/fonts/SegoeUI-Regular.woff');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('./assets/fonts/SegoeUI-Bold.woff');
  font-weight: bold;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('./assets/fonts/SegoeUI-Italic.woff');
  font-weight: normal;
  font-style: italic;
}
</style>