<script setup>
import comp from '@/components/NumberBlock.vue'
</script>
<template>
    <div class="flex  flex-row  justify-center">
    <comp class="  border-r border-yellow-400 px-[135px]  " num="30+" service="Satisfied Client" />
    <comp class="border-r border-yellow-400 px-[135px] " num="20+" service="Projects Completed" />
    <comp class="px-[135px]" num="40+" service="Reviews Given" />
    </div>

</template>