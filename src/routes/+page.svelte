<script lang="ts">

	// Imports:
	import Navbar from '$lib/Navbar.svelte';
	import Header from '$lib/Header.svelte';
	import Footer from '$lib/Footer.svelte';
	import Support from '$lib/Support.svelte';
	import Features from '$lib/Features.svelte';
	import Highlights from '$lib/Highlights.svelte';
	import Contributors from '$lib/Contributors.svelte';

	// Links:
	const links = {
		app: 'https://hackmarket.netlify.app/',
		api: 'https://hackmarket.netlify.app/',
		github: 'https://hackmarket.netlify.app/',
		twitter: 'https://hackmarket.netlify.app/',
		discord: 'https://hackmarket.netlify.app/',
		sdk: 'https://hackmarket.netlify.app/',
		contribute: 'https://hackmarket.netlify.app/',
		gitcoin: 'https://hackmarket.netlify.app/'
	}

	// Initializations:
	let scrollY = 0;
	
</script>

<!-- #################################################################################################### -->

<!-- SvelteKit Dynamic Header -->
<svelte:head>
	<title>핵마켓</title>
	<meta name="description" content="배그핵마켓, 서든핵마켓, 옵치핵마켓, 게임핵마켓, 배틀그라운드 핵, 서든어택 핵, 오버워치핵, 바디샷, 월핵, esp " />
	
</svelte:head>

<!-- Window Bindings -->
<svelte:window bind:scrollY />

<!-- Navbar -->
<Navbar bind:scrollY twitterLink={links.twitter} discordLink={links.discord} githubLink={links.github} />

<!-- Header Section -->
<Header appLink={links.app} />

<!-- Main Highlights -->
<Highlights sdkLink={links.sdk} apiLink={links.api} />

<!-- Blockchain/Project/Token Support -->
<Support />

<!-- Features -->
<Features />

<!-- Contributors -->
<Contributors contributeLink={links.contribute} discordLink={links.discord} />

<!-- Footer -->
<Footer {links} />