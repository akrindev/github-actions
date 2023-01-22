<script setup>
const name = 'syakirin amin'

defineProps({ say: Object })
</script>

<template>
    <div>
        Hello, ini awal dari sebuah percobaan inertiajs dengan vuejs. <br>
        My name is {{ name }} and I want to say {{ say }}
    </div>
</template>
