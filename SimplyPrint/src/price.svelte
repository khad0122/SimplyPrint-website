<script>

    import CompararisonTable from "./comparison-table.svelte"
</script>
<section class="container-fluid">
    <div class="shadow mx-md-4 bg-white rounded-md">
        <div class="text-center px-2">
            <h1 class="pricing-title pt-5">Priser</h1>
            <h2 class="pricing-title pt-2">
                <small>Find løsningen for dig</small>
            </h2>
        </div>
        <div>
            <div id="pricing_table" class="tab-content p-0 pb-3 ">
                <div id="personal" class="tab-pane active show" role="tabpanel">
                    <p class="text-center mt-1 mb-1 text-muted opacity-0">Prices are in
                        <strong>DKK</strong> incl. VAT</p>

                    <div class="pricing-table pt-4">
                        <div class="row justify-content-center m-0 w-100">
                            <div class="col-2.5 m-2">
                                <div class="cardPrices border border-dark">
                                    <div class="card-body  px-4">
                                        <div class="card-title border-bottom text-center py-3">
                                            <h2 class="font-400 text-muted">Free</h2>
                                        </div>
                                        <ul class="plan-details list-unstyled mt-4 text-info text-left">
                                            <li><span>Op til 2 printere</span></li>
                                            <li><span>1 GB cloud plads</span></li>
                                            <li class="mb-2">
                                                <span class="feature pricing-card-tooltip"
                                                      data-toggle="pricing-popover-hover"
                                                      data-placement="top" title=""
                                                      data-content="1 billede fra din printer hvert 6. sekund - hvorend du er i verdenen"
                                                      data-
                                                      original-title="Livestream"><i class="fa-solid fa-check"></i>
                                                    <span class="featuretext">1 frame /6s livestream</span>
                                                </span>
                                            </li>
                                            <li class="mb-2">
                                                <span class="feature" data-content="null">
                                                        <span class="featuretext">Live-chat</span>
                                                    </span>
                                                <small class="mb-0 d-block">Lav prioritet,
                                                    <br>
                                                    kl. 10-15 <i>(hverdage)</i>
                                                </small>
                                            </li>
                                            <li class="mb-2">
                                                <span class="feature">
                                                    <i class="fa-solid fa-check"></i>
                                                    <span class="featuretext">Indbygget online slicer</span>
                                                </span>
                                            </li>
                                            <li class="mb-2">
                                                <span class="feature">
                                                    <i class="fa-solid fa-check"></i>
                                                    <span class="featuretext">Fuld printer kontrol</span>
                                                </span>
                                            </li>
                                        </ul>
                                        <a class="btn btn-light"
                                           href="https://simplyprint.io/signup?utm_source=lp&amp;utm_content=1"
                                           disabled="true">Kom i gang</a>
                                    </div>
                                </div>
                            </div>
                            <div class="col-2.5 m-2">
                                <div class="cardPrices border border-dark">
                                    <div class="card-body text-center px-4">
                                        <div class="card-title border-bottom py-3">
                                            <h2 class="font-400 text-muted">Basic</h2>
                                            <h3 class="text-info mb-0">
                                                        <span style="font-weight: 600;"><span>
                                                            <span class="cost">39</span> kr. </span>
                                                        </span> /md
                                            </h3>
                                        </div>
                                        <ul class="plan-details list-unstyled mt-4 text-info text-left">
                                            <li>
                                                <span>Op til 3 printere</span>
                                            </li>
                                            <li>
                                                <span>2 GB cloud plads</span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                            <span class="featuretext">
                                                                <span class="text-muted">Alle features fra "<i>Free"</i></span>
                                                            </span>
                                                        </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature pricing-card-tooltip"
                                                              data-toggle="pricing-popover-hover"
                                                              data-placement="top" title=""
                                                              data-content="1 billede fra din printer hvert 4. sekund - hvorend du er i verdenen"
                                                              data-original-title="Livestream">
                                                            <img draggable="false"
                                                                 src="https://cdn.simplyprint.io/i/static/pricing/threearrows.svg"
                                                                 alt="Better arrows" width="18px">
                                                            <span class="featuretext">1 frame /4s livestream</span>
                                                        </span></li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                            <span class="featuretext">Live-chat</span>
                                                        </span>
                                                <small class="mb-0 d-block">Medium prioritet, kl. 10-18</small>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature pricing-card-tooltip"
                                                              data-toggle="pricing-popover-hover"
                                                              data-placement="top" title=""
                                                              data-content="Vi sørger for at varme printhovedet op til den perfekte temperatur, trækker filamentet ud og skubber det nye filament ind - ved blot ét klik."
                                                              data-original-title="Filament skift hjælper">
                                                            <i class="fa-solid fa-check"></i>
                                                            <span class="featuretext">Filament skift hjælper</span>
                                                        </span></li>
                                            <li class="mb-2" style="position: relative;">
                                                    <span class="feature pricing-card-tooltip"
                                                          data-toggle="pricing-popover-hover"
                                                          data-placement="top" title=""
                                                          data-content="Vi roterer automatisk modeller i vores slicer, så de ligger så perfekt som de kan, så du aldrig skal tænke på hvordan modellen skal ligge igen."
                                                          data-original-title="Smart rotation">
                                                        <i class="fa-solid fa-check"></i>
                                                        <span class="featuretext">Smart rotation</span>
                                                    </span>
                                            </li>
                                        </ul>
                                    </div>
                                    <a class="btn btn-light"
                                       href="https://simplyprint.io/signup?utm_source=lp&amp;utm_content=2">Prøv gratis
                                        i 14 dage</a>
                                    <div class="text-center small mb-2">
                                        <em class="font-400">Ingen binding</em>
                                        <br>
                                        <small>30 dages pengene tilbage garanti</small>
                                    </div>
                                </div>
                            </div>
                            <div class="col-2.5 most-popular higher m-2">
                                <div class="cardPrices border border-info">
                                    <div class="card-body text-center px-4">

                                        <div class="card-title border-bottom py-3">
                                            <h2 class="font-weight-bold">Pro</h2>
                                            <h3 class="text-info mb-0">
                                                        <span style="font-weight: 600;"><span>
                                                            <span class="cost">69</span> kr. </span>
                                                        </span> /md
                                            </h3>
                                        </div>
                                        <div class="ribbon">Most popular</div>
                                        <ul class="plan-details list-unstyled mt-2 text-info text-left">
                                            <li class="pricing-card-tooltip">
                                                <span data-toggle="tooltip" title="" class="featuretext"
                                                      data-original-title="15 kr./måneden per ekstra printer (10% rabat ved årlig betaling)">5+ printer pladser</span>
                                            </li>
                                            <li>
                                                <span>5+ GB cloud plads</span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                    <span class="feature" data-content="null">
                                                        <span class="featuretext">
                                                            <span class="text-muted">Alle features fra "<i>Basic"</i></span>
                                                        </span>
                                                    </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature pricing-card-tooltip"
                                                              data-toggle="pricing-popover-hover" data-placement="top"
                                                              title=""
                                                              data-content="1 billede fra din printer hvert 0.7. sekund - hvorend du er i verdenen"
                                                              data-original-title="Livestream">
                                                            <img draggable="false"
                                                                 src="https://cdn.simplyprint.io/i/static/pricing/threearrows.svg"
                                                                 alt="Better arrows" width="18px">
                                                            <span class="featuretext">1 frame /0.7s livestream</span>
                                                        </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                            <span class="featuretext">Live-chat</span>
                                                        </span> <small class="mb-0 d-block">Høj prioritet, kl.
                                                10-20</small>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                    <span class="feature pricing-card-tooltip"
                                                          data-toggle="pricing-popover-hover" data-placement="top"
                                                          title=""
                                                          data-content="Start samme print på flere printere på én gang. Inkluderer multi-cancel, multi-pause &amp; genoptag"
                                                          data-original-title="Multiprint">
                                                        <i class="fa-solid fa-check"></i> <span class="featuretext">Multiprint</span>
                                                    </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                            <i class="fa-solid fa-check"></i>
                                                            <span class="featuretext">Printkø</span>
                                                        </span></li>
                                            <li class="mb-2" style="position: relative;">
                                                    <span class="feature pricing-card-tooltip"
                                                          data-toggle="pricing-popover-hover" data-placement="top"
                                                          title=""
                                                          data-content="Se alle dine printeres kameraer - samtidig"
                                                          data-original-title="Multi-livestream">
                                                        <i class="fa-solid fa-check"></i>
                                                        <span class="featuretext">Multi-livestream</span>
                                                    </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature pricing-card-tooltip"
                                                              data-toggle="pricing-popover-hover" data-placement="top"
                                                              title=""
                                                              data-content="Få indblik i dine print-vaner, filament-forbrug, print-success og mere!"
                                                              data-original-title="Statistik">
                                                            <i class="fa-solid fa-check"></i>
                                                            <span class="featuretext">Statistik</span>
                                                        </span></li>
                                            <li class="mb-2" style="position: relative;">
                                                    <span class="feature" data-content="null">
                                                        <i class="fa-solid fa-check"></i>
                                                        <span class="featuretext">SMS notifikationer</span>
                                                    </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                            <i class="fa-solid fa-check"></i>
                                                            <span class="featuretext">API-adgang <i>(closed beta)</i></span>
                                                        </span>
                                            </li>
                                        </ul>
                                    </div>
                                    <a class="btn btn-primary"
                                       href="https://simplyprint.io/signup?utm_source=lp&amp;utm_content=3">Prøv gratis
                                        i 14 dage</a>
                                    <div class="text-center small mb-2">
                                        <em class="font-400">Ingen binding</em>
                                        <br>
                                        <small>30 dages pengene tilbage garanti</small>
                                    </div>
                                </div>
                            </div>
                            <div class="col-2.5 m-2">
                                <div class="cardPrices border border-info">
                                    <div class="card-body text-center px-4">
                                        <div class="card-title border-bottom py-3">
                                            <h2 class="font-weight-bold">Print farm</h2>
                                            <h3 class="text-info mb-0">
                                                        <span style="font-weight: 600;">
                                                            <span>
                                                                <span class="cost">250</span> kr.
                                                            </span>
                                                        </span> /md
                                            </h3>
                                        </div>
                                        <ul class="plan-details list-unstyled mt-4 text-info text-left">
                                            <li class="pricing-card-tooltip">
                                                <span data-toggle="tooltip" title="" class="featuretext"
                                                      data-original-title="15 kr./måneden per ekstra printer (10% rabat ved årlig betaling)">10+ printer pladser</span>
                                            </li>
                                            <li>
                                                <span>5+ GB cloud plads /user</span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                            <span class="featuretext">
                                                                <span class="text-muted">Alle features fra "<i>Pro"</i></span>
                                                            </span>
                                                        </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature pricing-card-tooltip"
                                                              data-toggle="pricing-popover-hover" data-placement="top"
                                                              title=""
                                                              data-content="1 billede fra din printer hvert 0.5. sekund - hvorend du er i verdenen"
                                                              data-original-title="Livestream">
                                                            <img draggable="false"
                                                                 src="https://cdn.simplyprint.io/i/static/pricing/threearrows.svg"
                                                                 alt="Better arrows" width="18px">
                                                            <span class="featuretext">1 frame /0.5s livestream</span>
                                                        </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                            <span class="featuretext">Live-chat</span>
                                                        </span>
                                                <small class="mb-0 d-block">Høj prioritet, kl. 10-20</small>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                    <span class="feature" data-content="null">
                                                        <i class="fa-solid fa-check"></i>
                                                        <span class="featuretext">Flere brugere</span>
                                                    </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                           <i class="fa-solid fa-check"></i>
                                                            <span class="featuretext">Hub &amp; register page</span>
                                                        </span></li>
                                            <li class="mb-2" style="position: relative;">
                                                    <span class="feature" data-content="null">
                                                        <i class="fa-solid fa-check"></i>
                                                        <span class="featuretext">Shared files, folders<br> &amp; slicer profiles</span>
                                                    </span></li>
                                            <li class="mb-2" style="position: relative;">
                                                    <span class="feature" data-content="null">
                                                        <i class="fa-solid fa-check"></i>
                                                        <span class="featuretext">Permissions &amp; roles</span>
                                                    </span>
                                            </li>
                                            <li class="mb-2" style="position: relative;">
                                                        <span class="feature" data-content="null">
                                                            <i class="fa-solid fa-check"></i>
                                                            <span class="featuretext">Enhanced API access <br><i>(auto-print <br> more - closed beta)</i></span>
                                                        </span>
                                            </li>
                                        </ul>
                                    </div>
                                    <a class="btn btn-primary"
                                       href="https://simplyprint.io/signup?utm_source=lp&amp;utm_content=4">Prøv gratis
                                        i 14 dage</a>
                                    <div class="text-center small mb-2">
                                        <em class="font-400">Ingen binding</em>
                                        <br>
                                        <small>30 dages pengene tilbage garanti</small>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <button type="button" class="text-dark mt-2 mb-2 font-500 bg-white border-1" data-toggle="collapse" data-target="#demo">Feature sammeligning<i class="fa-solid fa-angle-down ml-2" ></i></button>
            <div id="demo" class="collapse">
<CompararisonTable/>
            </div>
        </div>
    </div>

</section>


<style>

    a {
        color: white !important;
        background-color: black !important;
    }

    i {
        color: #19768f;
    }

    .cardPrices {
        border-radius: 10px;
    }

    th {
        text-align: left;
    }
</style>