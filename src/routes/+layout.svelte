<script lang="ts">
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>

	<title>thecasualdev</title>

	<link rel="icon" href={favicon} />
	<link rel="me" href="https://mastodon.social/@thecasualdev"/>

</svelte:head>

{@render children()}
