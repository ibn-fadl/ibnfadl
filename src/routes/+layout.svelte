<script lang="ts">
	import './layout.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Ardian ibn Fadl</title>
	<meta name="description" content="Ardian's site" />

	<!-- Facebook Meta Tags -->
	<meta property="og:url" content="https://ibnfadl.com" />
	<meta property="og:type" content="website" />
	<meta property="og:title" content="Ardian's Personal Site" />
	<meta property="og:description" content="Personal website of Ardian" />
	<meta property="og:image" content="https://ibnfadl.com/og-image.jpg" />

	<!-- Twitter Meta Tags -->
	<meta name="twitter:card" content="summary_large_image" />
	<meta property="twitter:domain" content="ibnfadl.com" />
	<meta property="twitter:url" content="https://ibnfadl.com" />
	<meta name="twitter:title" content="Ardian's Personal Site" />
	<meta name="twitter:description" content="Personal website of Ardian" />
	<meta name="twitter:image" content="https://ibnfadl.com/og-image.jpg" />
</svelte:head>
{@render children()}
