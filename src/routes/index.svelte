<script>
	import { pokemon } from '../stores/pokestores';
	console.log($pokemon);
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<h1>Welcome to SvelteKit</h1>

{#each $pokemon as pokeman}
	<p>{pokeman.name}</p>
{/each}
