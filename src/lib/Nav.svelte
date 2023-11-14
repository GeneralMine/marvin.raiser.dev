<script>
	import AnimatedTextField from './AnimatedTextField.svelte';
	import WriteHeadline from './WriteHeadline.svelte';

	let wordsLeft = [
		'Open Source Full-Stack Developer',
		'Computer Science Student at TU Munich',
		'Professional Drone Pilot',
		'Recruit at Federal Agency for Technical Relief',
		'Casual hiker and bouldering enthusiast',
		'Passionate about Philosophy',
		'Ludologist and Gamer',
		'Terrific Spezi to Code Converter',
		'Trained Cat Cuddler',
		'Der Kuschelbeauftragte<br>The Cuddle Officer'
	];
</script>

<a href="/">
	<img class="profilePicture" alt="Marvin Raiser" src="MarvinRaiser.jpg" />
</a>
<a href="/">
	<WriteHeadline>Marvin Raiser</WriteHeadline>
</a>
<AnimatedTextField words={wordsLeft} />
<div class="socialmediaContainer">
	<div class="socialmediaList">
		<a class="socialmediaButton" role="button" href="https://github.com/GeneralMine">
			<img src="github.svg" alt="Github" class="socialmediaIcon" />
		</a>
		<a class="socialmediaButton" role="button" href="https://www.linkedin.com/in/marvin-raiser/">
			<img src="linkedin.png" alt="LinkedIn" class="socialmediaIcon" />
		</a>
		<a class="socialmediaButton" role="button" href="https://www.instagram.com/marvin.codes/">
			<img src="instagram.svg" alt="Instagram" class="socialmediaIcon" />
		</a>
	</div>
</div>
<p><a href="mailto:marvin@raiser.dev">marvin@raiser.dev</a></p>

<style>
	.profilePicture {
		width: 12rem;
		height: 12rem;
		border-radius: 100%;
		object-fit: cover;
		margin: 1rem;
	}

	.socialmediaList {
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
	}
	.socialmediaContainer {
		width: 100%;
	}
	.socialmediaButton {
		background-color: #313539;
		border: 1px solid #282b2f;
		border-radius: 50%;
		width: 34px;
		height: 34px;
		display: flex;
		align-items: center;
		justify-content: center;
		padding: 8px;
		margin: 5px;
		line-height: 18px;
		opacity: 0.6;
		transition: opacity 0.2s;
	}
	.socialmediaButton:hover {
		opacity: 1;
	}
	.socialmediaIcon {
		height: 24px;
		width: 24px;
		margin: 0;
	}

	@media (max-width: 992px) {
		.socialmediaList {
			padding: 0;
			display: flex;
			justify-content: center;
			align-items: center;
			padding-top: 1rem;
			padding-bottom: 0.5rem;
		}
	}
</style>
