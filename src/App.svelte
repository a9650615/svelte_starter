<script>
	export let name;
	import TailwindCss from './TailwindCss.svelte'
</script>

<TailwindCss/>
<main class="container">
	<h1 class="bg-green-500">Hello {name}!</h1>
	<p class="text-6xl">The quick brown fox ...</p>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>