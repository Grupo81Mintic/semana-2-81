<template>
    <div>
        <header>
            <nav class="navbar navbar-expand-lg sticky-top navbar-dark bg-success">
                <a class="navbar-brand " href="# ">
                    <img src="" width="40" height="40" class="d-inline-block align-top" alt=" " loading="lazy"/> </a>
                <div class="collapse navbar-collapse justify-content-end " id="navbarNav">
                    <ul class="navbar-nav ">
                        <li class="nav-item active">
                            <a class="nav-link disable" name="inicio">Inicio<span class="sr-only">(current)</span></a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link active" href="#servicios">Servicios</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link active" href="#noticias">Noticias</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link active" href="#equipo">Equipo</a>
                        </li>
                    </ul>
                </div>
            </nav>
            <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
                <ol class="carousel-indicators">
                <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="3"></li>
                <li data-target="#carouselExampleCaptions" data-slide-to="4"></li>
                </ol>
                <div id="banner" class="carousel-inner">
                <div class="carousel-item active">
                    <img src="./img/slide1.jpg" class="d-block w-100" alt="..." height="600px">
                    <div class="carousel-caption d-none d-md-block">
                    <h2>{{paisaje1}}</h2>
                    <p>{{legenda1}}</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="./img/slide2.jpg" class="d-block w-100" alt="..." height="600px">
                    <div class="carousel-caption d-none d-md-block">
                        <h2>{{paisaje2}}</h2>
                        <p>{{legenda2}}</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="./img/slide3.jpg" class="d-block w-100" alt="..." height="600px">
                    <div class="carousel-caption d-none d-md-block">
                        <h2>{{paisaje3}}</h2>
                        <p>{{legenda3}}</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="./img/slide4.jpg" class="d-block w-100" alt="..." height="600px">
                    <div class="carousel-caption d-none d-md-block">
                        <h2>{{paisaje4}}</h2>
                        <p>{{legenda4}}</p>
                    </div>
                </div>
                <div class="carousel-item">
                    <img src="./img/slide5.jpg" class="d-block w-100" alt="..." height="600px">
                    <div class="carousel-caption d-none d-md-block">
                        <h2>{{paisaje5}}</h2>
                        <p>{{legenda5}}</p>
                    </div>
                </div>
                </div>
                <a class="carousel-control-prev" href="#carouselExampleCaptions" role="button" data-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="sr-only">Previous</span>
                </a>
                <a class="carousel-control-next" href="#carouselExampleCaptions" role="button" data-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="sr-only">Next</span>
                </a>
            </div>
        </header>
    </div>
</template>


<script>
export default {
    name : 'HeaderBanner'
}
</script>


<style  scoped>

</style>