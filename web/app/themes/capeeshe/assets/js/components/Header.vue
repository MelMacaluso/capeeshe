<template>
    <div>
        {{ body }}
    </div>
</template>

<script>
    export default {
        data() {
            return {
                body: 'I am a notification.'
            }
        }
    }
</script>

<style>
    .notification {
        background: grey;
    }
</style>