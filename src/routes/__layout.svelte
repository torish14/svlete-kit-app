<!-- 共通レイアウトの作成 -->
<script lang="ts">
  // ヘッダーの読み込み
	import Header from '$lib/header/Header.svelte';
  // 共通CSS の読み込み
	import '../app.css';
</script>

<Header />

<main>
	<slot />
</main>

<footer>
</footer>

<style>
</style>
