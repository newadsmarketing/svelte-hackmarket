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
		app: 'https://app.weaver.fi',
		api: 'https://api.weaver.fi',
		github: 'https://github.com/WeaverFi',
		twitter: 'https://twitter.com/weaver_fi',
		discord: 'https://discord.com/invite/DzADcq7y75',
		sdk: 'https://github.com/WeaverFi/weaverfi',
		contribute: 'https://github.com/WeaverFi/weaverfi/blob/main/CONTRIBUTING.md',
		gitcoin: 'https://gitcoin.co/grants/5854/weaverfi-the-open-source-defi-portfolio-tracker'
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