<script lang="ts">
	import Footer from './footer.svelte'
	import Header from './header.svelte'
</script>

<Header />

<nav>
		<a href="/">Home</a>
		<a href="/posts">Posts</a>
</nav>

<slot />

<Footer />
