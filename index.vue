<template lang="pug">
    div
      Nav
      div.min-h-screen.max-w-5xl.mx-auto.py-10.px-5(class="lg:px-0")
        .grid.grid-cols-1.grid-rows-2.grid-flow-row.gap-2(class="sm:grid-cols-2 lg:grid-cols-3")
          Card(tag='vue' title='A long text which should break when reaches the part' content='almafa')
          Card(tag='vue' title='How to find out a location of the user?' content='almafa')
      Footer
</template>
<script>
import Nav from "./.vuepress/components/Nav";
import Footer from "./.vuepress/components/Footer";
import Card from "./.vuepress/components/Card";

export default {
  components: {
    Nav,
    Footer,
    Card
  },
};
</script>

<style lang="stylus">
@import './.vuepress/theme/styles/theme.styl';
</style>
