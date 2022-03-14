<template>
    <n-date-picker v-model:value="timestamp" type="datetime" clearable />
    <pre>{{ JSON.stringify(timestamp) }}</pre>
    <n-button type="success">
        Success
    </n-button>
</template>

<script setup lang="ts">
    import { ref } from 'vue'
    import {NDatePicker, NButton} from 'naive-ui'
    const timestamp =  ref(1183135260000)
</script>