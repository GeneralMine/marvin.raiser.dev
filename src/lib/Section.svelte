<script>
	export let title = 'Section';
</script>

<section>
	<h1>{title}</h1>
	<hr />
	<div class="sectionContent">
		<slot />
	</div>
</section>

<style>
	hr {
		border-top-style: solid;
		border-top-width: 2px;
		width: 10rem;
		border-color: #e9e9e9;
		margin-bottom: 15px;
		margin-left: 0;
	}
	h1 {
		color: #e9e9e9;
		margin-bottom: 15px;
		font-size: 2.9411764705882rem;
		font-weight: 400;
		font-family: 'Inconsolata', monospace;
		line-height: 1.1;
		clear: both;
	}
	.sectionContent {
		display: flex;
		flex-direction: row;
		width: 100%;
		height: 100%;
		padding: 0;
		margin: 0;
		flex-wrap: wrap;
		justify-content: space-evenly;
	}

	/* Mobile Mode */
	@media (max-width: 1036px) {
		h1 {
			text-align: center;
		}
		section {
			display: flex;
			flex-direction: column;
			align-items: center;
		}
		hr {
			margin-left: auto;
		}
		.sectionContent {
			flex-direction: column;
			align-items: center;
		}
	}
</style>
