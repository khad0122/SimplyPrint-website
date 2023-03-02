<div id="QandA" class="container-fluid mt-4 pt-3 ">
    <div class="text-center mt-4">
        <h2 class="font-weight-bold text-white" >Ofte stillede spørgsmål</h2>
    </div>
    <div id="frontpageFAQ" class=" col-10 py-5 text-left text-white " role="tablist" aria-multiselectable="true" style="margin-left: 7rem">
        <div class="card mb-3" style="border-color: #5885AF">
            <a id="faqHeading0" style="display:table;background:#333333;min-height:100px;border-bottom-color: transparent;" class="card-header collapsed text-white " href="#faqCollapse0" aria-expanded="false" data-toggle="collapse" role="tab" aria-controls="faqCollapse0">
                <h5 class="mb-0 font-weight-bold" style="display: table-cell;vertical-align: middle;">
                    <strong>Hvilke printere virker med SimplyPrint?</strong>
                    <i class="fas fa-angle-down rotate-icon float-right"></i></h5>
            </a>
            <div id="faqCollapse0" class="collapse" role="tabpanel" aria-labelledby="faqHeading">
                <div class="card-body" style="background:#333333;"><b>Langt de fleste 3D printere fungerer med SimplyPrint.</b> Den generelle tommelfingerregel er; hvis din printer fungerer med OctoPrint / har en måde at tilslutte et USB -kabel på, fungerer den med SimplyPrint.<br><br>Tag et kig på <a href="https://simplyprint.io/compatibility" target="_blank">kompatibilitetslisten</a> for at se om din(e) printer(e) er på listen over printere vi <i>ved</i> virker med SimplyPrint. Men frygt ikke, hvis du ikke finder din printer på listen; der er stor sandsynlighed for at den virker med vores system alligevel, vi kender måske bare ikke til den endnu.</div>
            </div>
        </div>
        <div class="card mb-3" style="border-color: #5885AF">
            <a id="faqHeading1" style="display:table;background:#333333;min-height:100px;border-bottom-color: transparent;" class="card-header collapsed text-white " href="#faqCollapse1" aria-expanded="false" data-toggle="collapse" role="tab" aria-controls="faqCollapse1">
                <h5 class="mb-0 font-weight-bold" style="display: table-cell;vertical-align: middle;">
                    <strong>Er sikkerheden i orden?</strong>
                    <i class="fas fa-angle-down rotate-icon float-right"></i></h5>
            </a>
            <div id="faqCollapse1" class="collapse" role="tabpanel" aria-labelledby="faqHeading">
                <div class="card-body" style="background:#333333;"><b> Ja.</b> Vi gør alt, hvad vi kan for at gøre SimplyPrint så sikkert som muligt - vi tager det ansvar, der følger med håndtering af noget så følsomt som din 3D printer, meget alvorligt. Som tilfældet ofte er, er det svageste link normalt brugerens egen konto, og derfor er vi gået all-in på funktioner, der kan hjælpe dig med at holde din konto sikker. Muligheden for at aktivere 2-faktor-godkendelse og få e-mails ved login fra ukendte enheder, parret med registrering af spam-forsøg, hjælper os med at underrette dig-hvis noget skulle være usædvanligt.<br>Desuden hostes vores servere hos udbydere, der er kendt for at være nogle af de bedst sikrede på markedet, vi bruger kryptering i bankkvalitet til dine følsomme data og naturligvis den maksimale sikkerhed, når det kommer til adgang til vores servere og databaser.<br><br>Det er vores opgave at sikre, at din printer er sikker, og det er et job, vi tager meget alvorligt.</div>
            </div>
        </div>
        <div class="card mb-3" style="border-color: #5885AF">
            <a id="faqHeading2" style="display:table;background:#333333;min-height:100px;border-bottom-color: transparent;" class="card-header collapsed text-white " href="#faqCollapse2" aria-expanded="false" data-toggle="collapse" role="tab" aria-controls="faqCollapse2">
                <h5 class="mb-0 font-weight-bold" style="display: table-cell;vertical-align: middle;">
                    <strong>Stopper mit print hvis internettet går?</strong>
                    <i class="fas fa-angle-down rotate-icon float-right"></i></h5>
            </a>
            <div id="faqCollapse2" class="collapse" role="tabpanel" aria-labelledby="faqHeading">
                <div class="card-body" style="background:#333333;"><b>Nej, dit print stopper ikke</b> hvis printeren / din Raspberry Pi mister forbindelse til internettet, eller hvis SimplyPrint går ned. SimplyPrint downloader GCODE filen som din printer skal printe, lokalt ned på din printer, så hvis forbindelsen mistes, printer den videre.</div>
            </div>
        </div>
        <div class="card mb-3" style="border-color: #5885AF">
            <a id="faqHeading3" style="display:table;background:#333333;min-height:100px;border-bottom-color: transparent;" class="card-header collapsed text-white " href="#faqCollapse3" aria-expanded="false" data-toggle="collapse" role="tab" aria-controls="faqCollapse3">
                <h5 class="mb-0 font-weight-bold" style="display: table-cell;vertical-align: middle;">
                    <strong>Kan jeg stadig printe via. USB eller OctoPrint, Mainsail, Fluidd, og bruge min egen slicer?</strong>
                    <i class="fas fa-angle-down rotate-icon float-right"></i></h5>
            </a>
            <div id="faqCollapse3" class="collapse" role="tabpanel" aria-labelledby="faqHeading">
                <div class="card-body" style="background:#333333;"><b>Ja</b>, ja og ja. SimplyPrint begrænser hverken dig eller din printer på nogen måde. Så hvis du stadig ved lejlighed starter et print gennem OctoPrint, Mainsail, Fluidd eller via. SD kort, kan du stadig gøre dét - og SimplyPrint vil endda stadig holde øje med dit print og vise dig fremskridt.<br><br>
                    Du kan også <b>stadig blive ved med at bruge den slicer, du foretrækker</b> - du er ikke tvunget til at bruge SimplyPrint-sliceren <i>(selvom du går glip af en fed oplevelse! ;))</i><br><br>
                    Dette betyder også, at hvis SimplyPrint går ned <i>(hvilket er meget usandsynligt - vi har en <a href="https://status.simplyprint.io/" target="_blank" rel="noopener">oppetid på 99,99%</a>)</i>, vil du stadig kunne interagere med din printer på den 'gammeldags' måde.</div>
            </div>
        </div>

        <div class="card mb-3 " style="border-color: #5885AF">
            <a id="faqHeading4" style="display:table;background:#333333;min-height:100px;border-bottom-color: transparent;" class="card-header collapsed text-white" href="#faqCollapse4" aria-expanded="false" data-toggle="collapse" role="tab" aria-controls="faqCollapse4">
                <h5 class="mb-0 font-weight-bold" style="display: table-cell;vertical-align: middle;">
                    <strong>Kan jeg køre flere printere fra én Raspberry Pi?</strong>
                    <i class="fas fa-angle-down rotate-icon float-right"></i></h5>
            </a>
            <div id="faqCollapse4" class="collapse" role="tabpanel" aria-labelledby="faqHeading">
                <div class="card-body text-white" style="background:#333333;"><b>Ja!</b> Det er ikke den <i>letteste</i> ting at gøre endnu, så hvis du ikke vil have beskidte hænder med Raspberry Pi-opsætningen, er én Pi pr. printer, anbefalet.<br>Hvis du er klar til det, kan du nemt køre mellem 2-8 printere fra en enkelt Raspberry Pi (4B, 2GB ram). Tjek <a href="https://github.com/SimplyPrint/Multi-Instance-Setup" target="_blank" rel="nofollow">Multi Instance Setup</a> projektet på GitHub.</div>
            </div>
        </div>

    </div>
</div>

<style>

    #QandA{

        background-color: black;

    }
card {
border-color: #5885AF!important;


}
    a{
        text-decoration: none;
        color: #5885AF;
    }
</style>