<template>
    <inertia-link :href="'/'">
        <img class="w-80" :src="image" alt="Logo grifftagram">
    </inertia-link>
</template>

<script>
import image from '../../image/grifftagram.png'

export default {
    data() {
        return {
            image:image
        }
    },
}
</script>
