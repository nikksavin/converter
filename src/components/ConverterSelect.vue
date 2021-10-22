<template>
    <v-select
            :items="items"
            label="Coin"
    ></v-select>
</template>

<script>
    export default {
        name: "ConverterSelect",
        data: () => ({
            items: ['BTC', 'ETH', 'USD'],
        }),
    }
</script>

<style scoped>

</style>