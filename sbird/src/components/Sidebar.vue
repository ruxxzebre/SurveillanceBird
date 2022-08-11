<script setup>
import TrendsPanel from "./TrendsPanel.vue";
import UserPanel from "./UserPanel.vue";

const map = {
    "user": UserPanel,
    "trends": TrendsPanel
};

const { type } = defineProps({
    type: String
});

const comp = map[type];

</script>

<template>
<component :is="comp" />
</template>