<template lang="pug">
    div
        Nav
        section.min-h-screen.max-w-6xl.mx-auto.py-5
            h1 Create a website using pinoccio
        Footer
</template>
<script>
import Nav from "./.vuepress/components/Nav";
import Footer from "./.vuepress/components/Footer";

export default {
  components: {
    Nav,
    Footer,
  },
};
</script>

<style lang="stylus">
@import './.vuepress/theme/styles/theme.styl';
</style>
