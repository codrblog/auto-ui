<template>
    <div class='w-full py-2 px-4 bg-gray-200 flex'>
        <form class='w-full' @submit.prevent='submit'>
            <textarea class='py-1 px-2 border rounded-lg w-full' placeholder='Type your message...' rows='2'></textarea>
            <button class='bg-pink-600 text-white mt-2 rounded-lg py-1 px-2 hover:bg-pink-700'>Send</button>
        </form>
    </div>
</template>

<script>
export default {
    name: 'ChatFooter',
    methods: {
        submit() {
            // Handle Message Submission
        }
    }
}
</script>
