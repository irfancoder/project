<template>
    <div>
        Hello Krenovator 
        <button @click="clickMe('whats up')">Print</button>
    </div>
</template>

<script>
    import { print } from 'library'
    
    export default {
        mounted () {
            print('Hello Krenovator')
        },
        methods: {
            clickMe() {
                print('Whats up')
            }
        }
        
    }
</script>

<style lang="scss" scoped>

</style>