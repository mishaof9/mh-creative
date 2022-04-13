<script>
	import Navbar from '$lib/Navbar.svelte';
	import Footer from '$lib/Footer.svelte';

	import '../app.css';
</script>

<Navbar />
<div>
	<slot />
</div>
<Footer />
<style>
	div {
		min-height:100%;
	}
</style>
