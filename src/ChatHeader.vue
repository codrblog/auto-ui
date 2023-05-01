<template>
    <div class='w-full py-2 px-4 flex justify-between items-center bg-pink-600 text-white'>
        <h1 class='font-bold text-2xl'>Title</h1>
        <form class='flex justify-end w-2/3' @submit.prevent='submit'>
            <input type='text' class='w-full py-1 px-2 border rounded-lg' placeholder='Search...'>
            <button type='submit' class='bg-pink-700 rounded-lg ml-2 hover:bg-pink-800'>Search</button>
        </form>
    </div>
</template>

<script>
export default {
    name: 'ChatHeader',
    methods: {
        submit() {
            // Handle Search Submission
        }
    }
}
</script>
