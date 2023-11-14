<script>
	import { onMount } from 'svelte';
	import { slide } from 'svelte/transition';

	export let words = ['Code', 'Drohnen', 'Lehre', 'Design', 'Philosophie', 'Ludologie'];
	let selected = 0;

	function nextWord() {
		selected = (selected + 1) % words.length;
	}

	onMount(() => {
		let timer = setInterval(nextWord, 3000);
		return () => {
			clearInterval(timer);
		};
	});
</script>

{#each [words[selected]] as word (selected)}
	<h4 transition:slide|local>
		{@html word}
	</h4>
{/each}

<style>
	h4 {
		text-align: center;
	}
</style>
