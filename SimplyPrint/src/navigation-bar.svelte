<script>

</script>

<!--navigation-->
<section id="navbar">
    <nav id="navbar2" class="navbar navbar-expand-lg navbar-dark bg-transparent pt-2">
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
                    <a class="nav-link" href="#">Funktioner</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Priser</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Om os</a>
                </li>
                <li id="toggleMore" class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" id="moredropdownn" role="button"
                       data-toggle="dropdown"
                       aria-haspopup="true" aria-expanded="false">
                        More
                    </a>
                    <div id="moredropdown" class="dropdown-menu dropdown-menu-center text-white">
                        <div class="row">
                            <div class="col-4">

                                <a class="dropdown-item waves-effect waves-light" href="https://simplyprint.io/da/compatibility">
                                    Kompatibilitetsliste
                                </a>
                                <a class="dropdown-item waves-effect waves-light" href="https://simplyprint.io/da/downloads">
                                    Downloads
                                </a>
                                <a class="dropdown-item waves-effect waves-light" href="https://simplyprint.io/da/faq">
                                    FAQ
                                </a>
                                <a class="dropdown-item waves-effect waves-light" href="https://simplyprint.io/da/octoprint-difference">
                                    OctoPrint v. SimplyPrint?
                                </a>
                                <a class="dropdown-item waves-effect waves-light" href="https://help.simplyprint.io/" target="_blank" rel="noopener">
                                    Dokumentation (wiki)
                                </a>
                                <a class="dropdown-item waves-effect waves-light" href="https://status.simplyprint.io/" target="_blank" rel="noopener">
                                    Status side
                                </a>
                                <a class="dropdown-item waves-effect waves-light" href="https://simplyprint.io/da/credit">
                                    Credit
                                </a>

                                <a class="dropdown-item waves-effect waves-light" href="https://simplyprint.io/da/print-troubleshoot">
                                    Print fejlfinding
                                </a>
                                <a class="dropdown-item waves-effect waves-light" href="https://simplyprint.io/da/wifi-generate">
                                    WiFi-fil generator
                                </a>
                                <a class="dropdown-item waves-effect waves-light" href="https://simplyprint.io/da/branding">
                                    Brand &amp; medie-kit
                                </a>
                            </div>
                        </div>
                    </div>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" id="navbarDropdownEnterprise" role="button"
                       data-toggle="dropdown"
                       aria-haspopup="true" aria-expanded="false">
                        Enterprise
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdownEnterprise">
                        <a class="dropdown-item" href="https://www.google.dk/">Skoler</a>
                        <a class="dropdown-item" href="https://www.google.dk/">Print Farme</a>

                    </div>
                </li>


            </ul>

            <button type="button" class="btn btn-outline-light">Log in
            </button>
        </div>

    </nav>

</section>
<!--navigation-end-->
<style>
    /*==== NAVIGATION ====*/


    .navbar-brand img {
        height: 3rem;



    }
    .navbar{
        font-size: 1.10rem;
        letter-spacing: 0.07rem;
        z-index:99;
        margin:10px;

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