<script context="module" lang="ts">
  // コンテンツの先読み
  export const prerender = true;
</script>

<script lang="ts">
	import Counter from '$lib/Counter.svelte';
</script>

<!-- タブタイトル -->
<svelte:head>
	<title>Home</title>
</svelte:head>

<section>
	<h1>
	</h1>

	<h2>
	</h2>

	<Counter />
</section>

<style>
</style>
