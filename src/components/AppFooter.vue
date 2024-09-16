<script>
export default {
    data() {
        return {
        
        }
    }
}
</script>

<template>
    <footer>
        <section>
            <img src="../assets/img/la-molisana-logo.png" alt="La molisana main logo">
        </section>
        <section id="pastificio" class="footer-links">
            <h5>Pastificio</h5>
            <nav>
                <ul>
                    <li><a href="#">Il Pastificio</a></li>
                    <li><a href="#">Grano</a></li>
                    <li><a href="#">Filiera</a></li>
                    <li><a href="#">100 anni di pasta</a></li>
                    <li><a href="#">Sartoria della pasta</a></li>
                </ul>
            </nav>
        </section>
        
        <section id="prodotti" class="footer-links">
            <h5>Prodotti</h5>
            <nav>
                <ul>
                    <li><a href="#">Le classiche</a></li>
                    <li><a href="#">Le Integrali</a></li>
                    <li><a href="#">Le Speciali</a></li>
                    <li><a href="#">Le Biologiche</a></li>
                    <li><a href="#">Le Gluten-free</a></li>
                </ul>
            </nav>
        </section>
        <div class="mountains">
            <img src="../assets/img/footer-montagne-bottom.jpg" alt="">
        </div>
    </footer>
</template>

<style scoped>
    footer{
        display: flex;
        flex-wrap: wrap;
        padding-top: 5rem;

        section{
            width: calc(100% / 3);
        }

        section.footer-links{
            h5{
                text-transform: uppercase;
                font-size: 1.5rem;
            }

            ul{
                list-style-type: none;
                display: flex;
                flex-direction: column;
            }
        }


    }
</style>