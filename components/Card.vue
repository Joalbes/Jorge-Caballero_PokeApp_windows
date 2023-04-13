<template>
    <div class="w-[18%] h-[1/2] bg-gray-200 flex flex-col justify-center items-center">
        <img :src="url" >
        <p>{{ nombre }}</p>
    </div>
</template>
<script>
export default{
    props:{
        nombre:{
            type:String,
            required:true
        },
        url:{
            type:String,
            required: true
        }
    }
}</script>
<style></style>