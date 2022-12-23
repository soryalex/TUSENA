<template>

    <body>
        <!-- <div class="container"> -->
        <header
            class="d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-3 mb-4 border-bottom bg-success p-2 text-dark bg-opacity-50">
            <a href=""
                class="d-flex align-items-center col-md-3 mb-0 mb-md-0 text-dark text-decoration-none fw-bold fs-4">
                <img class="bi me-2 ms-4" width="50" height="50" role="img" aria-label="Bootstrap"
                    src="../assets/img/TUSENALOGO.png">
                TUSENA</a>

            <!-- <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
                    <li><a href="#" class="nav-link px-2 link-secondary">Home11</a></li>
                    <li><a href="#" class="nav-link px-2 link-dark">Features11</a></li>
                    <li><a href="#" class="nav-link px-2 link-dark">Pricing</a></li>
                    <li><a href="#" class="nav-link px-2 link-dark">FAQs</a></li>
                    <li><a href="#" class="nav-link px-2 link-dark">About</a></li>
                </ul> -->

            <div class="col-md-3 text-end">
                <button type="button" class="btn btn-outline-dark me-2 bg-success p-2 text-light bg-opacity-70"
                    data-bs-toggle="modal" data-bs-target="#exampleModal"> Iniciar Sesion</button>

                <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
                    aria-hidden="true">
                    <div class="modal-dialog">
                        <div class="modal-content">
                            <div class="modal-header">
                                <h1 class="modal-title fs-5 " id="exampleModalLabel">Inicia Sesion</h1>
                                <button type="button" class="btn-close" data-bs-dismiss="modal"
                                    aria-label="Close"></button>
                            </div>
                            <div class="modal-body">
                                <form>
                                    <div class="row mb-3">
                                        <label for="inputEmail3" class="col-sm-2 col-form-label">Identificacion</label>
                                        <div class="col-sm-10">
                                            <input type="email" class="form-control" id="inputEmail3">
                                        </div>
                                    </div>
                                    <div class="row mb-3">
                                        <label for="inputPassword3" class="col-sm-2 col-form-label">Contrasena</label>
                                        <div class="col-sm-10">
                                            <input type="password" class="form-control" id="inputPassword3">
                                        </div>
                                    </div>



                                    <div class="form-check d-flex justify-content-center mb-4">
                                        <input class="form-check-input me-2 success" type="checkbox" value=""
                                            id="form2Example33" checked />
                                        <label class="form-check-label" for="form2Example33">
                                            Recordarme
                                        </label>
                                    </div>

                                    <!-- Submit button -->
                                    <button type="submit" class="btn btn-success ">Inicia Sesion</button>

                                    <!-- Register buttons -->
                                    <div class="text-center">
                                        <p>o inicia sesion con:</p>
                                        <button type="button" class="btn btn-success btn-floating mx-1">
                                            <i class="bi bi-facebook"></i>
                                        </button>

                                        <button type="button" class="btn btn-success btn-floating mx-1">
                                            <i class="bi bi-google"></i>
                                        </button>

                                        <button type="button" class="btn btn-success btn-floating mx-1">
                                            <i class="bi bi-twitter"></i>
                                        </button>

                                        <!-- <button type="button" class="btn btn-secondary btn-floating mx-1">
                                            <i class="fab fa-github"></i>
                                        </button> -->
                                    </div>
                                </form>
                            </div>

                        </div>
                    </div>
                </div>


                <button type="button" class="btn btn-outline-dark me-2 bg-success p-2 text-light bg-opacity-70"
                    data-bs-toggle="modal" data-bs-target="#exampleModalR">Registro</button>


                <div class="modal fade" id="exampleModalR" tabindex="-1" aria-labelledby="exampleModalLabel"
                    aria-hidden="true">
                    <div class="modal-dialog">
                        <div class="modal-content">
                            <div class="modal-header">
                                <h1 class="modal-title fs-5" id="exampleModalLabel">Registro</h1>
                                <button type="button" class="btn-close" data-bs-dismiss="modal"
                                    aria-label="Close"></button>
                            </div>
                            <div class="modal-body">
                                <form>
                                    <!-- 2 column grid layout with text inputs for the first and last names -->
                                    <div class="row mb-4">
                                        <div class="col">
                                            <div class="form-outline">
                                                <input type="text" id="form3Example1" class="form-control" />
                                                <label class="form-label" for="form3Example1">Nombres</label>
                                            </div>
                                        </div>
                                        <div class="col">
                                            <div class="form-outline">
                                                <input type="text" id="form3Example2" class="form-control" />
                                                <label class="form-label" for="form3Example2">Apellidos</label>
                                            </div>
                                        </div>
                                    </div>

                                    <!-- Email input -->
                                    <div class="form-outline mb-4">
                                        <input type="email" id="form3Example3" class="form-control" />
                                        <label class="form-label" for="form3Example3">Correo Electronico</label>
                                    </div>

                                    <div class="form-outline mb-4">
                                        <input type="number" id="form3Example4" class="form-control" />
                                        <label class="form-label" for="form3Example3">Numero Identificacion</label>
                                    </div>

                                    <!-- Password input -->
                                    <div class="form-outline mb-4">
                                        <input type="password" id="form3Example5" class="form-control" />
                                        <label class="form-label" for="form3Example4">Contrasena</label>
                                    </div>

                                    <!-- Checkbox -->
                                    <div class="form-check d-flex justify-content-center mb-4">
                                        <input class="form-check-input me-2" type="checkbox" value=""
                                            id="form2Example33" checked />
                                        <label class="form-check-label" for="form2Example33">
                                            Acepto los terminos y Condiciones
                                        </label>
                                    </div>

                                    <!-- Submit button -->
                                    <button type="submit" class="btn btn-success btn-block mb-4">Registrarse</button>

                                    <!-- Register buttons -->
                                    <div class="text-center">
                                        <p>o registrate con:</p>
                                        <button type="button" class="btn btn-success btn-floating mx-1">
                                            <i class="bi bi-facebook"></i>
                                        </button>

                                        <button type="button" class="btn btn-success btn-floating mx-1">
                                            <i class="bi bi-google"></i>
                                        </button>

                                        <button type="button" class="btn btn-success btn-floating mx-1">
                                            <i class="bi bi-twitter"></i>
                                        </button>
                                        <!--                                   
                                      <button type="button" class="btn btn-secondary btn-floating mx-1">
                                        <i class="fab fa-github"></i>
                                      </button> -->
                                    </div>
                                </form>
                            </div>
                            <!-- <div class="modal-footer">
                                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                                <button type="button" class="btn btn-primary">Save changes</button>
                            </div> -->
                        </div>
                    </div>
                </div>

            </div>
        </header>

        <div class="container col-xxl-8 px-4 py-0">
            <div class="row flex-lg-row-reverse align-items-center g-5 py-5">
                <div class="col-10 col-sm-8 col-lg-6">



                    <img src="../assets/img/ASTRONAUTA.png" class="d-block mx-lg-auto img-fluid" alt="Bootstrap Themes"
                        width="700" height="500" loading="lazy">
                </div>
                <div class="col-lg-6">
                    <h1 class="display-1 fw-bold lh-1 mb-3">Bienvenido a TUSENA</h1>
                    <p class="lead">Si no conozco una cosa la investigaré
                        -Louis Pasteur</p>
                    <div class="d-grid gap-2 d-md-flex justify-content-md-start">
                        <!-- <i class="bi bi-google-play"></i> -->
                        <div class="d-flex flex-column flex-lg-row align-items-center">
                            <a class="me-lg-3 mb-4 mb-lg-0" href="#!"><img class="app-badge"
                                    src="https://www.designpieces.com/wp-content/uploads/2016/02/google-play-badge.png"
                                    alt="..." width="150" /></a>

                        </div>

                        <!-- <button type="button" class="btn btn-outline-secondary btn-lg px-4">Default</button> -->
                    </div>

                </div>

            </div>
        </div>
        <div class="p-2 p-md-5 mb-0 rounded text-bg-success">
            <div class="col-md-12 px-0">
                <p class="lead">TUSENA es una herramienta hecha por y para la investigación, en donde podrás
                    encontrar
                    los productos resultado de proyectos de investigación del Centro de Teleinformática y Producción
                    Industrial - Sena Popayán</p>
            </div>
        </div>

        <!-- </div> -->
    </body>
</template>