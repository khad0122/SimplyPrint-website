<script>

</script>

<!--Carousel Content-->
<section id="landingPageCarousel">
    <div id="carousel" class="carousel slide" data-ride="carousel"
         data-interval="5000"><!--intervalet mellem billede slides sat til 5 sekunder-->
        <!--Carousel Content-->

        <!-- Indicators -->
        <ul class="carousel-indicators">
            <li data-target="#demo" data-slide-to="0" class="active"></li>
            <li data-target="#demo" data-slide-to="1"></li>
            <li data-target="#demo" data-slide-to="2"></li>

        </ul>

        <div class="carousel-inner" >

            <div class="carousel-item active">
                <img src="img/carousel/printer.jpg" alt="" class="w-100">
                <!--max width of 100 procent of its parent element-->
                <div class="carousel-caption">
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-8 bg-custom d-none d-lg-block py-3">
                                <!--py giver vertikal padding på 1,5 rem-->
                                <h1>Gør 3D print til en leg</h1>
                                <div class="border-bottom  border mx-auto my-3"></div>

                                <p>3D print behøves ikke være en besværlig, analog, SD-kort-fyldt oplevelse; træd ind i
                                    fremtidens, moderne, 3D print.</p>

                                <p> Slice, print og hold øje med din(e) printere når som helst, hvor som helst, på alle
                                    dine devices fra én platform.</p>
                                <button type="button" class="btn btn-light ">KOM I GANG
                                </button>
                                <button type="button" class="btn btn-light ">LÆS MERE
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="carousel-item">
                <img src="img/carousel/printfarm2.jpg" alt="" class="w-100">
                <!--max width of 100 procent of its parent element-->
                <div class="carousel-caption">
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-10 bg-custom d-none d-lg-block py-3">
                                <!--py giver vertikal padding på 1,5 rem-->
                                <h1>Gør 3D print nemmere for print farms </h1>
                                <div class="border-bottom  border mx-auto my-3"></div>

                                <p>Få alle dine printere samlet i ét panel, med smarte funktioner som printkø og
                                    multiprint - det skal ikke at være svært.</p>

                                <button type="button" class="btn btn-light ">FÅ EN DEMO
                                </button>
                                <button type="button" class="btn btn-light ">LÆS MERE
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="carousel-item">
                <img src="img/carousel/school.jpg" alt="" class="w-100">
                <!--max width of 100 procent of its parent element-->
                <div class="carousel-caption">
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-9 bg-custom d-none d-lg-block py-3">
                                <!--py giver vertikal padding på 1,5 rem-->
                                <h1>Gør 3D print til en leg for skoler</h1>
                                <div class="border-bottom  border mx-auto my-3"></div>

                                <p>SimplyPrint tager alt besværet ud af 3D print; du behøves ikke længere være ekspert;
                                    her er det let for alle at komme i gang.</p>

                                <button type="button" class="btn btn-light ">FÅ EN DEMO
                                </button>
                                <button type="button" class="btn btn-light ">LÆS MERE
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
        <!--End Carousel Content-->


        <!--Previous and Next Buttons-->
        <a href="#carousel" class="carousel-control-prev" role="button"
           data-slide="prev">
            <span class="fas fa-chevron-left fa-2x"></span>

        </a>
        <a href="#carousel" class="carousel-control-next" role="button"
           data-slide="next">
            <span class="fas fa-chevron-right fa-2x"></span>
        </a>

        <!--Previous and Next Buttons-->
    </div>
</section>
<!--End Image Carousel-->
<style>


    /*==== Carousel ====*/

    #carousel{
        box-shadow: 0 1rem 1rem rgba(0,0,0,.2);
        margin-top: -100px;
        margin-bottom: 10px;


    }


    .carousel-inner{
        max-height: 42rem!important;


    }
    .carousel-item-next,
    .carousel-item-prev,
    .carousel-item.active{
        transition: transform 1.2s ease;
    }
    /*==== Carousel  content====*/

    .carousel-caption{

        position: absolute;
        top: 48%;
        transform: translateY(-50%);


    }

    .bg-custom{
        background-color: rgba(0,0,0,0.4);
        color: white;
        border-radius: 1rem;

    }
    .carousel-caption h1{
        font-size: 2.7rem!important;
        text-shadow: .1rem .1rem .3rem rgba(0,0,0,1);

    }

    .border{
        border-bottom: .2rem solid !important;
        background-color: #bcd5f1 !important;
    }
    .carousel-caption p{
        font-size: 1.3rem;
        text-shadow: .1rem .1rem .3rem rgba(0,0,0,1);

    }
    .btn-light:hover{
        background-color: #bcd5f1 !important;
    }


</style>