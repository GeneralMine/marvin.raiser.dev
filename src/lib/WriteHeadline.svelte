<div class="typewriter">
	<h1><slot /></h1>
</div>

<style>
	.typewriter h1 {
		color: #fff;
		font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu,
			Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
		overflow: hidden; /* Ensures the content is not revealed until the animation */
		border-right: 0.15em solid rgb(13, 110, 253); /* The typwriter cursor */
		white-space: nowrap; /* Keeps the content on a single line */
		margin: 0 auto; /* Gives that scrolling effect as the typing happens */
		letter-spacing: 0.15em; /* Adjust as needed */
		animation: typing 10s steps(30, end) infinite, blink-caret 0.7s step-end infinite;
	}

	@keyframes typing {
		from {
			width: 0;
		}
		20% {
			width: 100%;
		}
	}

	@keyframes blink-caret {
		from,
		to {
			border-color: transparent;
		}
		50% {
			border-color: rgb(13, 110, 253);
		}
	}
</style>
