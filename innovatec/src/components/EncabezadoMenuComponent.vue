<template>
    <nav class="navbar navbar-expand-lg bg-light p-0 p-0 fw-bold ">
        <div class="container-fluid font-weight-bold bg-warning">
            <!-- <a class="navbar-brand" href="#">Navbar</a> -->
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse " id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0 ">
                    <li class="nav-item dropdown ">
                        <router-link to="/" class="nav-link dropdown" href="#" role="button" aria-expanded="false">
                            Inicio
                        </router-link>

                    </li>
                    <li class="nav-item dropdown">
                        <router-link to="/" class="nav-link dropdown" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Quienes Somos
                        </router-link>
                        <ul class="dropdown-menu">
                            <li><router-link to="/quienes_somos" class="dropdown-item" href="#">Ver Quienes
                                    Somos</router-link></li>
                            <li><a class="dropdown-item" href="#">2</a></li>
                            <!-- <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li> -->
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <router-link to="" class="nav-link dropdown" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Investigadores
                        </router-link>
                        <ul class="dropdown-menu">
                            <li><router-link to="/investigadores" class="dropdown-item" href="#">Ver
                                    Investigadores</router-link></li>
                            <li><a class="dropdown-item" href="#">2</a></li>
                            <!-- <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li> -->
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <router-link to="" class="nav-link dropdown" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Semilleros
                        </router-link>
                        <ul class="dropdown-menu">
                            <li><router-link to="/semilleros" class="dropdown-item" href="#">Ver
                                    Semilleros</router-link></li>
                            <li><a class="dropdown-item" href="#">2</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown ">
                        <router-link to="" class="nav-link dropdown" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Equipo Sennova
                        </router-link>
                        <ul class="dropdown-menu">
                            <li><router-link to="/equipo_sennova" class="dropdown-item" href="#">Ver Equipo
                                    Sennova</router-link></li>
                            <li><a class="dropdown-item" href="#">2</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <router-link to="" class="nav-link dropdown" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Proyectos
                        </router-link>
                        <ul class="dropdown-menu">
                            <li><router-link to="/proyectos" class="dropdown-item" href="#">Ver Proyectos</router-link>
                            </li>
                            <li><a class="dropdown-item" href="#">2</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <router-link to="" class="nav-link dropdown" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Productos
                        </router-link>
                        <ul class="dropdown-menu">
                            <li><router-link to="/productos" class="dropdown-item" href="#">Ver Productos</router-link>
                            </li>
                            <li><a class="dropdown-item" href="#">2</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <router-link to="" class="nav-link dropdown" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Infraestructura
                        </router-link>
                        <ul class="dropdown-menu">
                            <li><router-link to="/infraestructura" class="dropdown-item" href="#">Ver
                                    Infraestructura</router-link></li>
                            <li><a class="dropdown-item" href="#">2</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>

                    <li class="nav-item dropdown">
                        <router-link to="" class="nav-link dropdown" href="#" role="button" data-bs-toggle="dropdown"
                            aria-expanded="false">
                            Noticias
                        </router-link>
                        <ul class="dropdown-menu">
                            <li><router-link to="/noticias" class="dropdown-item" href="#">Ver Noticias</router-link>
                            </li>
                            <li><a class="dropdown-item" href="#">2</a></li>
                            <li>
                                <hr class="dropdown-divider">
                            </li>
                            <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                    </li>

                </ul>
                <!-- <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form> -->
            </div>
        </div>
    </nav>
</template>

<script>


</script>

<style scoped>
nav {
    width: 100%;
}
</style>



