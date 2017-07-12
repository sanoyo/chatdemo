<template>
    <div class="chat-log">
        <chat-message></chat-message>
        <chat-message></chat-message>
        <chat-message></chat-message>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                messages: [
                {
                    message: 'Hey',
                    user: 'sano'
                },
                {
                    message: 'Hello'
                    user: 'Yo'
                }
                ]
            }
        }
    }
</script>

<style lang="css">
.chat-composer {
    display: flex;
}

.chat-composer input {
    flex: 1 auto;
}

.chat-composer button {
    border-radius: 0;
}

</style>