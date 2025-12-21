<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/icon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<title>Ardian's Personal Site</title>
	<link rel="icon" href={favicon} />
</svelte:head>
{@render children()}
