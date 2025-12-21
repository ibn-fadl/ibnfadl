<script lang="ts">
	import './layout.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Ardian's Personal Site</title>
</svelte:head>
{@render children()}
