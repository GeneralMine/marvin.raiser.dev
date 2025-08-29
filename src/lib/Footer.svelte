<script>
	import { PUBLIC_VERSION } from '$env/static/public';
</script>

<div class="summaryContainer">
	<a href={`/imprint`}>Imprint</a>
	<a class="version" href="https://github.com/GeneralMine/marvin.raiser.dev/releases/{PUBLIC_VERSION}">{PUBLIC_VERSION}</a>
	<a href={`/privacy`}>Privacy</a>
</div>

<style>
	div {
		display: flex;
		padding: 2rem;
		align-items: center;
		flex-direction: row;
		justify-content: center;
		font-size: 1rem;
		line-height: 1.15;
		text-align: center;
		flex-wrap: nowrap;
		margin-top: 0.3rem;
	}
	a {
		padding-left: 1rem;
		padding-right: 1rem;
		width: 33%;
		text-decoration: none;
		font-size: 1rem;
		line-height: 1.15;
		text-align: center;
	}
	@media (max-height: 600px) {
		div {
			padding: 0;
			margin: 0;
		}
	}
</style>
