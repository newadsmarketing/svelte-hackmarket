<script lang="ts">

	// Initializations & Exports:
	export let appLink: string;
	const launched = false;

</script>

<!-- #################################################################################################### -->

<section>

	<!-- Header Content -->
	<div class="content">
		<h2>배그핵 서든핵 옵치핵 , 국내 최저가 게임핵, 24시간 고객센터 운영중
		</h2>
		
			<a href="https://noonoo40.tv" style="cursor: not-allowed;"><strong>핵마켓 바로가기</strong></a>
		
	</div>

	<!-- Weavey -->
	<img src="/images/main.jpg" alt="hackmarket-logo">

</section>

<!-- #################################################################################################### -->

<style>

	section {
		margin-top: 5em;
		padding-top: 5em;
		padding-bottom: 5em;
	}

	div.content {
		display: flex;
		flex-direction: column;
		justify-content: center;
		flex: 1;
		padding-right: 1em;
	}

	div.content > h2 {
		font-size: 3em;
	}

	div.content > span {
		margin: 1em 0;
		font-size: 1.8em;
	}

	div.content > a {
		width: 12em;
		margin-bottom: 2em;
		padding: .8em;
		font-size: 1.2em;
		color: var(--secondaryColor);
		background-color: var(--accentColor);
		border: 3px solid var(--accentColor);
		border-radius: 2em;
		text-align: center;
		text-decoration: none;
		transition: all .3s ease-out;
	}

	div.content > a:hover {
		color: white;
		background-color: var(--primaryColor);
	}

	img {
		height: 35em;
	}

	@media screen and (max-width: 900px) {
		img {
			height: 30em;
		}
	}

	@media screen and (max-width: 700px) {
		section {
			flex-direction: column;
		}
	}
	
</style>
