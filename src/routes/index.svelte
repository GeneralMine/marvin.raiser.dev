<div class="typewriter">
	<h1>Coming soon.</h1>
</div>
<a href="https://github.com/GeneralMine/marvin.raiser.dev">0.0.2</a>

<style>
	:global(body) {
		background: #333;
		padding-top: 5em;
		display: flex;
		justify-content: center;
		flex-direction: column;
		align-items: center;
	}

	a {
		padding-top: 1rem;
	}

	.typewriter h1 {
		color: #fff;
		font-family: monospace;
		overflow: hidden; /* Ensures the content is not revealed until the animation */
		border-right: 0.15em solid orange; /* The typwriter cursor */
		white-space: nowrap; /* Keeps the content on a single line */
		margin: 0 auto; /* Gives that scrolling effect as the typing happens */
		letter-spacing: 0.15em; /* Adjust as needed */
		animation: typing 2s steps(30, end), blink-caret 0.5s step-end infinite;
	}

	@keyframes typing {
		from {
			width: 0;
		}
		to {
			width: 100%;
		}
	}

	@keyframes blink-caret {
		from,
		to {
			border-color: transparent;
		}
		50% {
			border-color: orange;
		}
	}
</style>
