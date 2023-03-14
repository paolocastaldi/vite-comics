<script>
export default {
    data() {
        return {
            title: "Icons",
        };
    },
};
</script>

<template>
    <section class="IconContent">
        <div class="container">
            <div>
                <img src="../assets/buy-comics-digital-comics.png" alt="" />
                <span>DIGITAL COMICS</span>
            </div>
            <div>
                <img src="../assets/buy-comics-merchandise.png" alt="" />
                <span>DC MERCHANDISE</span>
            </div>
            <div>
                <img src="../assets/buy-comics-subscriptions.png" alt="" />
                <span>SUBSCRIPTION</span>
            </div>
            <div>
                <img src="../assets/buy-comics-shop-locator.png" alt="" />
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div>
                <img src="../assets/buy-dc-power-visa.svg" alt="" />
                <span>DC POWER VISA</span>
            </div>
        </div>
    </section>
</template>

<style scoped>
.IconContent {
    background-color: #0282f9;
    padding-top: 50px;
    padding-bottom: 50px;
    color: white;
}

.container {
    display: flex;
    justify-content: space-around;
}

img {
    width: 50px;
    height: 50px;
}

div {
    display: flex;
    align-items: center;
}

span {
    padding-left: 20px;
}
</style>