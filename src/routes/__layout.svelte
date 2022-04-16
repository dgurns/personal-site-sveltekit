<script>
	import '../app.css';
</script>

<nav class="flex flex-col justify-start px-4 py-2 md:flex-row md:space-x-4">
	<a href="/">Dan Gurney</a>
	<span class="hidden md:block">/</span>
	<a href="/software">Software</a>
	<a href="/music">Music</a>
	<a href="/blog">Blog</a>
</nav>

<slot />
