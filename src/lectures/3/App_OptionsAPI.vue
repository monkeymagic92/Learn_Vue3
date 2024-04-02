<template>
    <div>
        <button v-on:click="increment">Counter : {{ counter }}</button>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                counter:0,
            };
        },
        methods: {
            increment() {
                this.counter++;
            }
        },
        mounted() {
            console.log('컴포넌트 마운트되어씁니다.');
        }
    }
</script>

<style lang="scss" scoped>

</style>