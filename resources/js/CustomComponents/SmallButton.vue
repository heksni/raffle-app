<template>
    <button :type="type" class="inline-flex items-center px-1.5 py-0.5 bg-gray-800 border border-transparent rounded-md font-semibold text-xs text-white uppercase tracking-widest hover:bg-gray-700 active:bg-gray-900 focus:outline-none focus:border-gray-900 focus:ring focus:ring-gray-300 disabled:opacity-25 transition">
        <slot></slot>
    </button>
</template>

<script>
export default {
    name: "SmallButton",
    props: {
        type: {
            type: String,
            default: 'submit',
        },
    }
}
</script>

<style scoped>

</style>
