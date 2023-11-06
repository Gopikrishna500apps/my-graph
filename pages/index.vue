<template>
    <div>
<NetworkGraph :chartData="chartData" />
    </div>
</template>
<script setup>
import NetworkGraph from '../src/components/NetworkGraph.vue';
import chartData from '../data/networkGraph.json';
</script>