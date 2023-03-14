<script>
export default {
    data() {
        return {
            title: "Footer",
        };
    },
};
</script>

<template>
    <footer class="upperFooter">
        <div class="container">
            <!-- Prima lista -->
            <div>
                <h4 class="TitleUlFooter">DC COMICS</h4>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <h4 class="TitleUlFooter">Shop</h4>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <!-- Prima lista -->

            <!-- Seconda lista -->
            <div>
                <h4 class="TitleUlFooter">DC</h4>
                <ul>
                    <li>Terms Of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shops Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <!-- Seconda lista -->

            <!-- Terza lista -->
            <div>
                <h4 class="TitleUlFooter">Sites</h4>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
            <!-- Terza lista -->
        </div>
    </footer>

    <footer class="bottomFooter">
        <div class="container">
            <div>
                <button class="btn-footer">SIGN-UP NOW !</button>
            </div>
            <div class="IconsFooter">
                <ul>
                    <li class="follow-us">FOLLOW US</li>

                </ul>
            </div>
        </div>
    </footer>
</template>

<style scoped>
/* UpperFooter */
.upperFooter {
    background-image: url(../assets/footer-bg.jpg);
    background-position: center;
    background-size: cover;
}

.upperFooter ul {
    color: grey;
}

.container {
    display: flex;
}

.container div {
    padding-top: 30px;
    padding-right: 50px;
}

h4 {
    margin-bottom: 10px;
    color: white;
}

.upperFooter div * {
    padding-bottom: 10px;
}

.TitleUlFooter {
    font-size: 20px;
}

/* Bottom Footer */
.bottomFooter {
    background-color: #303030;
}

.follow-us {
    color: #0282f9;
    font-weight: bold;
}

.bottomFooter ul li {
    display: inline-block;
    vertical-align: middle;
    padding-right: 20px;
}

.bottomFooter .container {
    display: flex;
    justify-content: space-between;
    padding-bottom: 30px;
}

.btn-footer {
    background-color: transparent;
    border: solid #0282f9;
    padding: 10px;
    color: white;
    font-weight: bold;
}

/* Bottom Footer */
</style>