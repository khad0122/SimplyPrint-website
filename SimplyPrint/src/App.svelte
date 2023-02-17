

<script>
	export let name;
	import Navigation from "./navigation-bar.svelte"
	import Section1 from "./section1.svelte"
	import LandingPageCarousel from "./landing-page-carousel.svelte";
	import ThreeColumn from "./three-columns.svelte";
	import ProductDescription from "./product-description.svelte";
</script>

<main>
	<Navigation/>
	<LandingPageCarousel/>
	<ThreeColumn/>
	<ProductDescription/>

	<Section1/>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;

		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}


</style>
