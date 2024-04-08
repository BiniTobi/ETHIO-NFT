<script setup>
let logo = "Ethio NFT"
</script>
<template>
    <div class="container">
        <div class="logo">
            <h1>{{logo}}</h1>
        </div>
        <div class="center">
            <p>Explore</p>
            <p class="passive">Stats</p>
            <p class="passive">Resources</p>
            <p class="passive">Create</p>
        </div>
        <div class="button">
            <button>Connect Wallet</button>
        </div>
    </div>

</template>
<style scoped>

.container{
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    color: #fff;
    margin-top:40px ;
}
.center{
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 50px;
    cursor: pointer;
}
.passive{
    color: gray;
}
.passive:hover{
    font-weight: bold;
}
button{
    border: none;
    border: 2px solid #fff;
    padding: 10px;
    border-radius: 15px;
    color: #fff;
    cursor: pointer;
}
</style>