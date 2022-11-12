<template>
    <h1>{{content}}</h1>
</template>

<script>
export default{
    name:"HeaderComponent",
    props: {
        text: String
    },

    watch: {
        text(nVal) {
            return this.componentHC = nVal
        }
    },
    methods: {

    }
}
</script>
<style>
</style>