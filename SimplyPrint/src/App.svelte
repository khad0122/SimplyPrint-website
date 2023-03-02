

<script>
	export let name;
	import Navigation from "./navigation-bar.svelte"

	import LandingPageCarousel from "./landing-page-carousel.svelte";
	import ThreeColumn from "./three-columns.svelte";

	import Getstarted from "./get-started.svelte"
	import SystemFunctions from "./system-functions.svelte"
	import TrustPilot from "./trustpilot-reviews.svelte"
	import Footer from "./footer.svelte"
	import QA from "./Q&A.svelte";
	import AboutUs from "./about-us.svelte"
	import Price from "./price.svelte"


</script>

<main>
	<Navigation/>
	<LandingPageCarousel/>
	<ThreeColumn/>
	<Getstarted/>
	<SystemFunctions/>
	<TrustPilot/>
	<QA/>
	<Price/>
	<AboutUs/>
	<Footer/>


</main>

<style>
	main {
		text-align: center;
		padding: 1em;

		margin: 0 auto;
	}




</style>
