<template>
    <footer>
        <div class="footerJumboImg">
            <div class="container">
                <div class="row">
                    <div class="col-2">
                        <div class="row">
                            <div class="col-3">
                                <h3>DC COMICS</h3>
                                    <ul>
                                        <li>Character</li>
                                        <li>Comics</li>
                                        <li>Movies</li>
                                        <li>TV</li>
                                        <li>Games</li>
                                        <li>Videos</li>
                                        <li>News</li>
                                    </ul>
                                <h3>SHOP</h3>
                                <ul>
                                    <li>Shop DC</li>
                                    <li>Shop DC Collectables</li>
                                </ul>
                            </div>
                            <div class="col-3">
                                <h3>DC</h3>
                                <ul>
                                    <li>Lorem, ipsum.</li>
                                    <li>Corporis, architecto!</li>
                                    <li>Recusandae, temporibus!</li>
                                    <li>Iste, blanditiis?</li>
                                    <li>Nisi, dolor!</li>
                                    <li>Distinctio, accusamus.</li>
                                    <li>Alias, a.</li>
                                    <li>Quaerat, facere!</li>
                                    <li>Voluptatum, quidem.</li>
                                    <li>Neque, repudiandae?</li>
                                    <li>Autem, eum.</li>
                                </ul>
                            </div>
                            <div class="col-3">
                                <h3>SITES</h3>
                                <ul>
                                    <li>Lorem, ipsum.</li>
                                    <li>Nulla, dolore!</li>
                                    <li>Voluptas, illo!</li>
                                    <li>Vero, obcaecati?</li>
                                    <li>Debitis, hic!</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="col-2">
                        <img src="../assets/img/dc-logo-bg.png" alt="">
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">

.footerJumboImg{
    background-image:url(../assets/img/footer-bg.jpg);
    background-repeat:no-repeat;
    background-size: cover;
}

.col-3{
    h3{
        padding-top: 4rem;
        padding-bottom: 1rem;
        color:white;
    }
    ul{
        list-style: none;
        li{
            padding-top:0.5rem;
            color: #8f8f90;
        }
    }
}
</style>