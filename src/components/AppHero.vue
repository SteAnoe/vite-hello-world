<script>
    export default{
        name: "AppHero",
        data() {
            return {
               
            }
        }
    }
</script>

<template>
    <div>
       <img src="https://picsum.photos/id/237/400/200" alt=""> 
       <h2>Cane</h2>
    </div>
  
</template>

<style scoped>
    div{
        display: flex;
        justify-content: center;
        position: relative;
    }
    h2{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
</style>