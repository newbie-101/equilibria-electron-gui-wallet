<template>
<span>
    {{ value }} LOKI
</span>
</template>

<script>
export default {
    name: "FormatLoki",
    props: {
        amount: {
            required: true
        },
        round: {
            type: Boolean,
            required: false,
            default: false
        }
    },
    computed: {
        value () {
            let value = this.amount / 1e9
            if(this.round)
                value = value.toFixed(3)
            return value.toLocaleString()
        }

    }
}
</script>

<style>
</style>
