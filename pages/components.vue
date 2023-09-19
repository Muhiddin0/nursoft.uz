<template>
    <h1 style="text-align: center;">I am Component</h1>

    <button :style="`${button_sm}`" class="border-2 text-red-400">Button</button>

</template>

<script>

import { button_sm } from '~/theme';

export default {
    setup () {
        return {}
    }
}
</script>

<style lang="scss" scoped>

</style>