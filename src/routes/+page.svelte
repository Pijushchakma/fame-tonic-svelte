<script lang="ts">
	// Simple welcome page
	import Banner from '../components/Banner.svelte';
	import HeroSection from '../components/HeroSection.svelte';
	import Navbar from '../components/Navbar.svelte';
	import ResponsiveHeroIcon from '../components/ResponsiveHeroIcon.svelte';
</script>

<svelte:head>
	<title>Fame Tonic</title>
	<meta name="description" content="Welcome to Fame Tonic Svelte" />
	<style>
		:global(.hero-icon-container svg) {
			width: 100% !important;
			height: 100% !important;
		}
	</style>
</svelte:head>

<Banner />
<Navbar />

<!-- Hero Icon positioned underneath -->
<div class="fixed top-[76px] md:top-[126px] left-[1px] md:left-[673px] z-0 border border-red-600 w-[390px] h-[426px] md:w-[666px] md:h-[679px]">
	<ResponsiveHeroIcon />
</div>

<!-- Hero Section positioned on top -->
<HeroSection/>
