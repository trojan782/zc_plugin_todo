<template>
    <button class="bg-green-500 my-5 flex items-center p-4 rounded-md text-white">
        <svg width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M9 3.74994V14.2499" stroke="white" stroke-width="1.22693" stroke-linecap="round" stroke-linejoin="round"/>
        <path d="M3.74988 8.99994H14.2499" stroke="white" stroke-width="1.22693" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <span class="px-2">Create New Todo</span>
    </button>
</template>
<script>
export default {
    name: 'AddTaskBtn'
}
</script>
<style lang="scss" scoped>
button {
    box-shadow: 0 0 10px rgb(0 103 69 / 28%);
}
</style>
