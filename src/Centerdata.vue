<script setup>
import logo from "./assets/nft.png"
import log2 from "./assets/text.png"

</script>
<template>
<div class="conta">
    <div class="left">
        <img v-bind:src="log2"/>
        <h4>Best place for getting hottest NFT trending cards</h4>
        <div class="buttons">
            <h3 id="oh">Explore</h3>
            <h3>Learn More</h3>

        </div>
        <div class="k">
            <div class="textdata">
                <h1>35K+</h1>
                <p>Treanding Cards</p>
                <h1>35K+</h1>
                <p>Treanding Cards</p>
                <h1>35K+</h1>
                <p>Treanding Cards</p>
            </div>
        </div>
    </div>
    <div class="right">
        
        <img v-bind:src="logo"/>

    </div>
</div>

</template>
<style scoped>
.conta{
    display: flex;
    justify-content: center;
    align-items: center
}
.left{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 10px;
    color: #a38f8f;
}
.buttons{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
    color: #fff;
    margin-top: 20px;
}


.buttons>#oh{
    border: 2px solid #a38f8f;
    padding: 10px;
    border-radius: 10px;
    cursor: pointer;
}
.k{ 
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 0rem;
    position: relative;
}
.textdata{
    position:absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    top: 100px;
    gap: 25px;
}
</style>