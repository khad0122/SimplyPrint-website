
<!--navigation-->

<script>

    import Functions from "./functions.svelte"
</script>
<section id="navbar">
    <nav id="navbar2" class="navbar navbar-expand-lg navbar-dark ">
        <!--navbar-expand-lg, lg stands for large screen-->

        <a href="index.html" class="navbar-brand"><img src="/img/header_gradient_white@0.5x.png"></a>

        <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbarSupportedContent"
                aria-controls="navbarSupportedContent"
                aria-expanded="false"
                aria-label="Toggle navigation"
        >
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item ">
                    <a class="nav-link active" href="index.html">Overblik</a>
                </li>
                <li class="nav-item">
                    <btn>

                    </btn>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="functions.svelte">Priser</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="https://www.google.dk/">Om os</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" id="navbarDropdownMore" role="button" data-toggle="dropdown"
                       aria-haspopup="true" aria-expanded="false">
                        Mere
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdownMore">
                        <a class="dropdown-item" href="https://www.google.dk/">Action</a>
                        <a class="dropdown-item" href="https://www.google.dk/">Another action</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="https://www.google.dk/">Something else here</a>
                    </div>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" id="navbarDropdownEnterprise" role="button"
                       data-toggle="dropdown"
                       aria-haspopup="true" aria-expanded="false">
                        Enterprise
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdownEnterprise">
                        <a class="dropdown-item" href="https://www.google.dk/">Action</a>
                        <a class="dropdown-item" href="https://www.google.dk/">Another action</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="https://www.google.dk/">Something else here</a>
                    </div>
                </li>

            </ul>

            <button type="button" class="btn btn-outline-light">Log in
            </button>
        </div>

    </nav>

</section>
<style>
    /*==== NAVIGATION ====*/


    .navbar-brand img {
        height: 3rem;

    }
    .navbar{
        font-size: 1.10rem;
        letter-spacing: 0.07rem;
        z-index:99;

        background-color: #5885AF;
    }
    .nav-link{
        color: white!important;
    }

    .nav-link:hover{
        color: #bcd5f1 !important;
        font-weight: 450;
    }

    .btn{
        margin:0.6rem;
        padding-left: 1.8rem !important;
        padding-right: 30px!important;
        border-radius: 2px!important;


    }

</style>