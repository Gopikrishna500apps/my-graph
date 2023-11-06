<template>
    <div>
<NetworkGraph :chartData="chartData" />
    </div>
</template>
<script setup>
import NetworkGraph from '../src/components/NetworkGraph.vue';
import chartData from '../src/data/networkGraph.json';
</script>