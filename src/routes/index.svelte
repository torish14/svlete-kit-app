<script context="module" lang="ts">
  // コンテンツの先読み
  export const prerender = true
</script>

<script lang="ts">
import Todos from '../components/Todos.svelte'
</script>

<!-- タブタイトル -->
<svelte:head>
	<title>Home</title>
</svelte:head>

<Todos />

<style>
</style>
