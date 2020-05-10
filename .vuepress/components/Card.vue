<template lang="pug">
    div.card
        img.w-full(src='https://via.placeholder.com/300')
        .card-body
            a(href='#').text-xl.font-bold {{ title }}
            p {{ content }}
            span.text-xs {{ tag }}
</template>

<script>
export default {
    props: ['tag', 'title', 'content']
}
</script>

<style lang="styl">
.card {
    @apply mt-2 shadow-md;
    min-width: 320px;

    img {
        @apply m-0;
        height: 250px;
    }

    .card-body {
        @apply p-3;
    }
}
</style>