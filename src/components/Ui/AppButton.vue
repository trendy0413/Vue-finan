<template>
    <button
      class="inline-flex items-center justify-center border focus:outline-none transition ease-in-out duration-150 text-black bg-green-300 hover:bg-green-400 border-green-700 hover:border-white rounded text-sm px-4 py-2"
      @click="$emit('click')"
    >
      <slot />
    </button>
</template>

<script>
    export default {
        name: 'AppButton',

        data() {
            return {
            };
        },

        methods: {},
    };
</script>
