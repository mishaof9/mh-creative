<script>
	import Modal from '$lib/Modal.svelte';
	export let src;
</script>

<Modal on:close>
	<div>
		<img {src} />
	</div>
</Modal>

<style>
	div {
		border:1px solid rgb(246, 243, 242);
    }
	img {
		max-width: 800px;
		max-height: 600px;
	}
</style>
