<script>
	import linkedin from '$lib/assets/linkedin-logo.png';
	import github from '$lib/assets/github-icon.png';
</script>

<footer>
	<hr />
	<div class="icons">
		<img src={linkedin} alt="linkedin logo" /><img src={github} alt="github logo" />
	</div>
	<hr />
</footer>

<style>
	footer {
		display: flex;
		justify-content: center;
		align-items: flex-end;
		color: var(--primary);
		background-color: var(--secondary);
		position: fixed;
		bottom: 0;
		width: 100%;
		height: 10vh;
	}

	hr {
		color: var(--primary);
		width: 50%;
		margin-bottom: 1rem;
		border-top: 0.5px;
	}

	.icons {
		display: flex;
		gap: 8px;
		margin: 0 2rem;
	}

	.icons img {
		width: 100%;
		max-width: 40px;
		height: auto;
	}
</style>
