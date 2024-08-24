<script setup>
defineProps({
    msg: {
    type: String,
    required: true,
    }
    
})
</script>
<template>
    <div class="msgparent">
    <div class="message border-[.5px] border-[#ffd330] rounded-[50%] h-[42px] w-[99px] flex item-center justify-center align-middle py-1.5">{{ msg }}</div>
 

    </div>
</template>

<style scoped>
.message{
    position: absolute;
    top: 6px;
    left:5px;
    line-height: 145%;
    font-weight: 500;
}
.child{
    position:absolute;
    top: 0px;
    left: 0px;
    border-radius: 50%;
    border: 0.5px #ffd330;   
    box-sizing: border-box;
    width: 99px;
    height: 42px;
}
.msgparent{
width: 100%;
position: relative;
height: 42px;
text-align: left;
font-size: 20px;
color: #ffd330;
font-family: Inter;
}
</style>