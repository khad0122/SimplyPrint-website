<script>

</script>

<section id="threecolumns">
    <div class="col-12 text-center text-white mt-5 mb-5">
        <h1 class="text-white pt-4">Ét system til din printers behov</h1>
        <p>SimplyPrint samler alle features der gør din printe oplevelse bedre</p>
    </div>


    <!--three column section-->
    <div class="col-12 mt-5 text-white">
        <div class="row justify-content-center text-center" style="min-height: 390px">
            <div class="col">
                <h3 class="font-weight-bold mb-2">Print</h3>
                <p>Print & overvåg - for 1 eller 1.000 printere</p>
                <img src="img/printer-rotated.png" class=" w-100 h-auto">
            </div>

            <div class="col">
                <h3 class="font-weight-bold mb-2">Slice</h3>
                <p>Alle slicere er lige godt supporteret!</p>
                <img src="img/slicing_3d.png" class=" w-100 h-auto">
            </div>

            <div class="col">
                <h3 class="font-weight-bold mb-2">Håndtering og opbevaring</h3>
                <p>Filament, filer, brugere, printkø mm.</p>
                <img src="img/filament_3d_rotated.png" class=" w-100 h-auto">
            </div>
        </div>
    </div>


</section>


<section id="choisebtn">
    <div id="choises" class="container">
        <div class="container" style="min-height: 20rem">

            <h2 class="text-white pt-4">En løsning for alle</h2>

            <div style="width:80%;margin:0 auto;">
                <div class="p-4 row justify-content-center">
                    <div class="col-12 col-md-4 mb-2 ">
                        <a href="https://simplyprint.io/schools" class="btn btn-lg btn-outline-dark btn-block "><i
                                class="fas fa-graduation-cap fa-2x"></i><br>Skoler
                        </a>
                    </div>
                    <div class="col-12 col-md-4 mb-2">
                        <a href="https://simplyprint.io/print-farms" class="btn btn-lg btn-outline-dark btn-block "><i
                                class="fas fa-warehouse fa-2x"></i><br>Farm
                        </a>
                    </div>
                    <div class="col-12 col-md-4 mb-2">
                        <a href="#setup_second" class="btn btn-lg btn-outline-dark btn-block "><i
                                class="fas fa-user fa-2x"></i><br>Hobby
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!--End three column section-->

<style>

    #choises a {
        color: #C3E0E5;

    }

    #choises a:hover {
        color: white;

    }

    #choises {
        background-color: #000000;
    }

    #threecolumns {
        background-color: #000000;
    }

    #choisebtn {
        background-color: #000000;
    }




    .btn-block {
        --glow-color: rgb(88, 133, 175);
        --glow-spread-color: rgb(88, 133, 175);
        --enhanced-glow-color: rgb(88, 133, 175);
        --btn-color: rgb(3, 3, 3);
        border: .25em solid var(--glow-color);
        padding: 1em 2.5em;
        color: var(--glow-color);
        font-size: 17px;
        font-weight: bold;
        background-color: var(--btn-color);
        border-radius: 1em;
        outline: none;
        box-shadow: 0 0 1em .25em var(--glow-color),
        0 0 4em 1em var(--glow-spread-color),
        inset 0 0 .75em .25em var(--glow-color);
        text-shadow: 0 0 .5em var(--glow-color);
        position: relative;
        transition: all 0.3s;
    }


    .btn-block::after {
        pointer-events: none;
        content: "";
        position: absolute;
        top: 120%;
        left: 0;
        height: 100%;
        width: 100%;
        background-color: var(--glow-spread-color);
        filter: blur(2em);
        opacity: .7;
        transform: perspective(1.5em) rotateX(35deg) scale(1, .6);
    }

    .btn-block:hover {
        color: var(--btn-color);
        background-color: var(--glow-color);
        box-shadow: 0 0 1em .25em var(--glow-color),
        0 0 4em 2em var(--glow-spread-color),
        inset 0 0 .75em .25em var(--glow-color);
    }

    .btn-block:active {
        box-shadow: 0 0 0.6em .25em var(--glow-color),
        0 0 2.5em 2em var(--glow-spread-color),
        inset 0 0 .5em .25em var(--glow-color);
    }

    a {
        padding: 10px 5px;
        display: inline-block;
        color: #35a7d9;
        box-shadow: 0 0 50px #14d4ff;

        text-transform: uppercase;
        text-decoration: none;
        font-size: 2em;
        overflow: hidden;
        border-color: #14d4ff;
        border-width: 4px;
        border-radius: 40px !important;

    }

    /*creating animation effect*/
    a:hover {
        color: #111;
        background: #14d4ff;
        box-shadow: 0 0 50px #14d4ff;
    }

    i {

    }


</style>