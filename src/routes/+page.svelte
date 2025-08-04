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
</svelte:head>

<Banner />
<Navbar />

<!-- Hero Icon positioned underneath -->
<div class="fixed top-[126px] left-[1px] md:left-[673px] z-0 w-full h-[326px] md:w-[666px] md:h-[679px]">
	<ResponsiveHeroIcon />
</div>

<!-- Hero Section positioned on top -->
<HeroSection/>
