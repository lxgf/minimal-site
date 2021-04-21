<template>
  <TheHeader />
</template>

<script>
import TheHeader from "./components/TheHeader.vue";
export default {
  components: {TheHeader}
}
</script>

<style>
@font-face {
  font-family: 'Segoe UI';
  src: url('public/fonts/SegoeUI-Light.woff');
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('public/fonts/SegoeUI-BoldItalic.woff');
  font-weight: bold;
  font-style: italic;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('public/fonts/SegoeUI-SemiBold.woff');
  font-weight: 600;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('public/fonts/SegoeUI.woff');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('public/fonts/SegoeUI-Bold.woff');
  font-weight: bold;
  font-style: normal;
}

@font-face {
  font-family: 'Segoe UI';
  src: url('public/fonts/SegoeUI-Italic.woff');
  font-weight: normal;
  font-style: italic;
}
</style>