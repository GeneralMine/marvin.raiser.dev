<script>
	export let src = '';
	export let text = '';
</script>

<div class="peopleCardContainer">
	<img {src} alt={src} />
	<p>{@html text}</p>
</div>

<style>
	.peopleCardContainer {
		display: flex;
		flex-direction: column;
		max-width: 588px;
		margin-top: 3rem;
		margin-left: 1rem;
		margin-right: 1rem;
	}
	img {
		height: 78px;
		max-height: 78px;
		max-width: 550px;
		object-fit: contain;
	}
	p {
		box-sizing: border-box;
		color: #e9e9e9;
		display: block;
		margin-top: 24px;
		margin-bottom: 0;
		margin-block-start: 24px;
		margin-block-end: 0;
		overflow-wrap: break-word;
		word-break: break-word;
		font-family: 'Inconsolata', monospace;
		font-size: 17px;
		font-weight: 400;
		line-height: 1.85714285714286;
		line-height: 31.5667px;
		font-style: normal;
		overflow-wrap: break-word;
		padding-bottom: 0px;
		padding-left: 0px;
		padding-right: 0px;
		padding-top: 0px;
		scrollbar-width: auto;
		word-break: break-word;
	}
</style>
