<script lang="ts">

	// Initializations & Exports:
	export let githubLink: string;
	export let twitterLink: string;
	export let discordLink: string;
	export let scrollY: number;

</script>

<!-- #################################################################################################### -->

<nav class:shadow={scrollY > 0}>

	<!-- WeaverFi Branding -->
	<div class="brand" on:click={() => window.scrollTo({ top: 0, behavior: 'smooth' })} on:keydown={() => window.scrollTo({ top: 0, behavior: 'smooth' })}>
		<img src="/images/weavey.png" alt="Weavey">
		<h1>핵마켓</h1>
	</div>

	<!-- Links -->
	<div class="links">
		<a href="https://noonoo40.tv" style="cursor: not-allowed;"><strong>고객센터 문의</strong></a>
		</div>

</nav>

<!-- #################################################################################################### -->

<style>

	nav {
		justify-content: space-between;
		padding-top: 1em;
		padding-bottom: 1em;
		background-color: var(--secondaryColor);
	}

	nav::before {
		content: '';
		position: absolute;
		inset: 0;
		box-shadow: 0 0 30px black;
		transition: opacity 0.3s ease-in-out;
		opacity: 0;
		z-index: -1;
	}

	nav.shadow::before {
		opacity: 1;
	}

	div.brand {
		display: flex;
		align-items: center;
		font-size: .8em;
		cursor: pointer;
	}

	div.brand > img {
		height: 4em;
		margin-right: .8em;
	}

	div.brand > h1 {
		font-size: 2em;
		color: var(--primaryColor);
	}

	div.links {
		display: flex;
		align-items: center;
		gap: 1em;
	}

	div.links > a {
		display: flex;
	}

	div.links > a > svg {
		width: 1.8em;
		height: 1.8em;
		fill: var(--fontColor);
	}

	div.links > a > svg:hover {
		filter: drop-shadow(0 0 5px var(--accentColor));
	}

	@media screen and (max-width: 1270px) {
		nav {
			padding-top: 2em;
			padding-bottom: 2em;
		}
	}
	
</style>