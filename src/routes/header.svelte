<script lang="ts">
	import * as config from '$lib/config'
</script>

<nav>
	<!--Title-->
	<a href="/" class="title">
		<b>{config.title}</b>
	</a>

	<ul class="links">
		<li>
			<a href="/">Home</a>
		</li>
		<li>
			<a href="/posts">Posts</a>
		</li>
	</ul>
</nav>

<style>
	ul {
		display: flex;
		list-style-type: none;
	}

	li {
		padding: 5px
	}
</style>
