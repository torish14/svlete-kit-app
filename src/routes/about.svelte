<script context="module">
	import { browser, dev } from '$app/env';

	// we don't need any JS on this page, though we'll load
	// it in dev so that we get hot module replacement...
// true だと 初回アクセス時に SSR された JS をクライアントで読み込む
	export const hydrate = dev;

	// ...but if the client-side router is already loaded
	// (i.e. we came here from elsewhere in the app), use it
  // true だとページ遷移を制御
	export const router = browser;

	// since there's no dynamic data here, we can prerender
	// it so that it gets served as a static asset in prod
  // コンテンツの先読み
	export const prerender = true;
</script>

<!-- タブタイトル -->
<svelte:head>
	<title>About</title>
</svelte:head>

<div class="content">
	<h1>
  </h1>
</div>

<style>
</style>
