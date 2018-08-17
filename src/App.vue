<template>
    <button @click="addItem">Add item to array</button>
</template>

<script>
    export default {
        name: 'app',
        data() {
            return {
                items: []
            }
        },
        methods: {
            addItem() {
                this.items.push('Item: ' + new Date())
            }
        }
    }
</script>
