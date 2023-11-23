<script setup>

defineProps(["text"])

</script>

<template>

<a href="#!" class="btn">{{ text }}</a>

</template>

<style scoped>
.btn {
    padding: 15px 30px;
    color: #fff;
    border-radius: 5px;
    background: #3A68B8;
    transition: 0.5s;
}

.btn:hover {
    box-shadow:  5px 5px 13px 5px #191970;
}
</style>