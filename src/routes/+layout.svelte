<script>
	import '@fontsource/inconsolata';
	import Nav from '$lib/Nav.svelte';
	import Footer from '$lib/Footer.svelte';
</script>

<svelte:head>
	<meta property="og:type" content="website" />
	<meta property="og:locale" content="de_DE" />
</svelte:head>

<div class="root">
	<nav>
		<Nav />
	</nav>
	<div class="page">
		<main>
			<slot />
		</main>
		<footer>
			<Footer />
		</footer>
	</div>
</div>

<style>
	.root {
		display: flex;
		flex-direction: row;
		align-items: center;
		width: 100%;
		height: 100%;
		padding: 0;
		margin: 0;
	}
	.page {
		left: 320px;
		right: 0;
		margin-left: calc(320px + 3rem);
		margin-right: 3rem;
		margin-top: 3rem;
		min-height: calc(100vh - 3rem);
		min-width: calc(100vw - 320px - 6rem);
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}
	main {
		width: 100%;
		height: 100%;
		padding: 0;
		margin: 0 auto;
	}
	nav {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		width: 320px;
		min-height: 100%;
		background-color: #282828;
		position: fixed; /* Stay in place */
		top: 0; /* Stay at the top */
		left: 0;
	}
	footer {
		display: flex;
		flex-direction: row;
		align-items: center;
		justify-content: center;
		margin: 0.5rem;
		margin-top: 3rem;
	}

	/* Content will wrap into 1 column */
	@media (max-width: 1658px) {
	}
	/* Mobile Mode */
	@media (max-width: 1036px) {
		.root {
			flex-direction: column;
		}
		nav {
			width: 100%;
			height: 500px;
			min-height: 500px;
			position: relative;
		}
		.page {
			width: 100%;
			padding-left: 0;
			padding-right: 0;
			margin: 0 auto;
		}
		:global(img) {
			width: 100%;
			height: auto;
		}
	}

	:global(a) {
		color: #bfbfbf;
		text-decoration: none;
	}
	:global(a:hover) {
		color: rgb(13, 110, 253);
	}
	:global(h1, h2, h3, h4, p) {
		font-family: 'Inconsolata', monospace;
	}
</style>
