<script>
	import PictureModal from '$lib/PictureModal.svelte';

	export let images = [];
	let selected_image = null;
</script>

{#if selected_image}
	<PictureModal on:close={() => (selected_image = null)} src={selected_image.full} />
{/if}
<div>
    <div class="row justify-content-center gallery">
		{#each images as image}
        <div class="col col-4 ">
				<img
					src={image.thumb}
					alt={image.title}
					class="thumb"
					on:click={() => (selected_image = image)}
				/>
		</div>
		{/each}
    </div>  
</div>

<style>
	.gallery {
	margin-top: 10px;
   
	}
	.thumb {
		border: 1px double rgb(248, 245, 245);
		border-radius: 4px;
		padding: 1px;
		cursor: pointer;
        height:170px;
        width:200;
		
	}
    .col{
        width:fit-content; 
        margin:0;
        padding:0;
    }
</style>
