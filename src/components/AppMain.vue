<script>
export default {
    data() {
        return {
            products: [
                {
                    thumb:
                        "https://imgs.search.brave.com/aUNyvZBXUulb963JH7KnQm9AMr8bcBoLsiHREOqayIU/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvOWZm/ZWYzMDMtMGZhYy00/OGRkLTg3ODctYzUy/NTk0MDk2ODAwXzEu/MTc1ZDk1Mjg2NzY0/OGEwOTczMTY2NGMy/MTE1NjNlYWIuanBl/Zz9vZG5XaWR0aD02/MTImb2RuSGVpZ2h0/PTYxMiZvZG5CZz1m/ZmZmZmY",

                    series: "Action Comics",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/OU2E3_3vA7flyv-SJ3TcFW1d99KDlp5ZfmW9ylLLFDo/rs:fit:1012:1200:1/g:ce/aHR0cHM6Ly9pMC53/cC5jb20vd3d3LnN1/cGVycG91dm9pci5j/b20vd3AtY29udGVu/dC91cGxvYWRzLzIw/MjAvMDcvQW1lcmlj/YW4tVmFtcGlyZS0x/OTc2LTAxLWNvdi1B/bGJ1cXVlcnF1ZS0y/MDIwLmpwZz9yZXNp/emU9MTAxMiUyQzE1/NTYmc3NsPTE",

                    series: "Action Comics",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/gAZQuZyt6WjcUWF6aXCIBaiJqtOJAK-X4nxS9Vbvwno/rs:fit:1200:1200:1/g:ce/aHR0cHM6Ly9jZG4y/LnBlbmd1aW4uY29t/LmF1L2NvdmVycy9v/cmlnaW5hbC85Nzgx/NDAxMjc1NDI2Lmpw/Zw",

                    series: "Aquaman",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/YET9wY29Aa29TyHqlbieS9qsz3HWyNYQx-WkRqdBRX4/rs:fit:640:984:1/g:ce/aHR0cDovL2dldHlv/dXJjb21pY29uLmNv/LnVrL3dwLWNvbnRl/bnQvdXBsb2Fkcy8y/MDE2LzA4L2JhdGdp/cmwtcmViaXJ0aC0x/LWNvdmVyLmpwZw",

                    series: "Batgirl",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/jgxYlrx442aozemzjqdmCsd9DkIkRollJp1T8sG8TfE/rs:fit:720:1106:1/g:ce/aHR0cHM6Ly9veXN0/ZXIuaWduaW1ncy5j/b20vd29yZHByZXNz/L3N0Zy5pZ24uY29t/LzIwMTgvMTAvU1RM/MDk3MDk1LTcyMHgx/MTA2LmpwZw",

                    series: "Batman",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/jgxYlrx442aozemzjqdmCsd9DkIkRollJp1T8sG8TfE/rs:fit:720:1106:1/g:ce/aHR0cHM6Ly9veXN0/ZXIuaWduaW1ncy5j/b20vd29yZHByZXNz/L3N0Zy5pZ24uY29t/LzIwMTgvMTAvU1RM/MDk3MDk1LTcyMHgx/MTA2LmpwZw",

                    series: "Batman Beyond",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/cSaB3m-tghN3_Cllp9IOlUPEPsyShCnl8gijRyPFdrg/rs:fit:791:1200:1/g:ce/aHR0cHM6Ly8xNDk0/NTUxNTIudjIucHJl/c3NhYmxlY2RuLmNv/bS93cC1jb250ZW50/L3VwbG9hZHMvMjAx/OS8wOC9CTVNNX0N2/MV9CQVQuanBn",

                    series: "Batman/Superman",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/jfaQd--WUx7RG8MiQ-VyCOqLUJW19ojBnjkNOG81rL4/rs:fit:666:1024:1/g:ce/aHR0cHM6Ly90aGVn/d3cuY29tL3dwLWNv/bnRlbnQvdXBsb2Fk/cy8yMDIwLzA5L0Jh/dG1hbi1TdXBlcm1h/bi1Bbm51YWwtQ3Yx/LTY2NngxMDI0Lmpw/Zw",

                    series: "Batman/Superman Annual",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/kSLCPBIeE9s218LRC4cIyrHOYmxrSS2Wt7LvNNfED2I/rs:fit:455:700:1/g:ce/aHR0cHM6Ly9jb21p/Y2Jvb2tyZWFsbS5j/b20vY292ZXItc2Nh/bi81ZmFmMTFjYTk1/NGQ1MGVjZDA1ZmU3/M2U1NjBiNWQyOC94/bC8tLWlzc3VlLTEu/anBn",

                    series: "Batman: The Joker War Zone",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/a6fAPUra4t94xMJFlYv6X7Lwm4z_qPmslx7Hiqafbok/rs:fit:600:923:1/g:ce/aHR0cHM6Ly9jZG4u/ZmxpY2tlcmluZ215/dGguY29tL3dwLWNv/bnRlbnQvdXBsb2Fk/cy8yMDIwLzA4L0Jh/dG1hbi1UaHJlZS1K/b2tlcnMtMS02MDB4/OTIzLTEuanBn",

                    series: "Batman: Three Jokers",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/qMxyCwK99aguaETp4ioxXLrpxwNg2JNBN3Oq7LGAgzM/rs:fit:780:1200:1/g:ce/aHR0cHM6Ly9jZG4u/ZmxpY2tlcmluZ215/dGguY29tL3dwLWNv/bnRlbnQvdXBsb2Fk/cy8yMDIwLzEwL0Jh/dG1hbi1XaGl0ZS1L/bmlnaHQtUHJlc2Vu/dHMtSGFybGV5LVF1/aW5uLTEtMS5qcGc",

                    series: "Batman: White Knight Presents: Harley Quinn",

                },
                {
                    thumb:
                        "https://imgs.search.brave.com/bf_FlGnymAgmvweY8YiLAcyy600JdSMl_jHpdR3t5ro/rs:fit:612:612:1/g:ce/aHR0cHM6Ly9pNS53/YWxtYXJ0aW1hZ2Vz/LmNvbS9hc3IvNTA5/M2IxOTEtZTkzZS00/NTJjLThhYTQtYTEw/ZDY0ZTcxN2E5LjA5/N2UwZWM5NDgzYzky/OGExMjY4Nzk1Nzk2/NTliZWNjLmpwZWc_/b2RuV2lkdGg9NjEy/Jm9kbkhlaWdodD02/MTImb2RuQmc9ZmZm/ZmZm",

                    series: "Catwoman",

                },
            ],
        };
    },
};
</script>

<template>
    <section class="FirstSection">
        <div id="FirstSectionUP">
            <div class="container-jumbo"></div>
        </div>
        <div id="FirstSectionDOWN">
            <div class="container-jumbo">
                <div class="card" v-for="products in products">
                    <div class="img">
                        <img :src="products.thumb" :alt="products.series" />
                    </div>
                    <div class="testo">
                        {{ products.series }}
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.container {
    display: flex;
    align-items: center;
}

.FirstSection {
    background-color: #1c1c1c;
    color: white;
    height: 1300px;
}

.FirstSection {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    background-color: #1c1c1c;
}

.FirstSection #FirstSectionUP {
    height: 30%;
    width: 100%;
    background-image: url(../assets/jumbotron.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}

.FirstSection #FirstSectionDOWN {
    height: 70%;
    width: 80%;
    display: flex;
    justify-content: center;
}

.container-jumbo {
    height: 100%;
    width: 80%;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    color: white;
}

#FirstSectionDOWN .card {
    width: calc(100% / 7);
    color: black;
    height: 200px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin: 50px 10px;
}

#FirstSectionDOWN .card .img {
    height: 80%;
    width: 100%;
    background-size: cover;
}

#FirstSectionDOWN .card .testo {
    height: 40%;
    width: 100%;
    background-color: #1c1c1c;
    color: white;
}
</style>