<script>
export default {
    data() {
        return {
            title: "Header",
        };
    },
};
</script>

<template>
    <header>
        <div class="container">
            <div>
                <img src="../assets/dc-logo.png" alt="" />
            </div>

            <div>
                <ul>
                    <li>Characters</li>
                    <li>Comic</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Collectibles</li>
                    <li>Videos</li>
                    <li>Fans</li>
                    <li>News</li>
                    <li>Shop</li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style scoped>
header {
    background-color: white;
}

.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 20px;
}

ul li {
    display: inline-block;
    margin: 0 0.5rem;
    font-weight: bold;
}
</style>

