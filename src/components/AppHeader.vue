<script>
export default {
    data() {
        return {
            navLinks: [
                "Home",
                "Prodotti",
                "Chi siamo",
                "Contatti"
            ]
        }
    }
}
</script>

<template>
    <header>    
        <section class="main-logo">
            <img src="../assets/img/la-molisana-logo.png" alt="La molisana main logo">
        </section>

        <section class="navbar">
            <nav>
                <ul>
                    <li v-for="navItem in navLinks">
                        {{ navItem }}
                    </li>
                </ul>
            </nav>
        </section>

    </header>
</template>

<style lang="scss" scoped>
    header{
        text-align: center;

        ul{
            list-style-type: none;
            margin-bottom: 2rem;
            display: flex;
            justify-content: center;
            align-items: center;

            li{
                margin-right: 1.5rem;
                padding: 1rem;

                &:hover,
                &.active{
                    background-color: #dae8fe;
                }

            }
        }
    }
</style>