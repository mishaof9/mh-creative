<script>
	import Gallery from '$lib/Gallery.svelte';

	let images = [
		{
			full: '/static/img/nature/whiteflower.png',
			thumb: '/static/img/nature/whiteflowerthumb.jpg',
			title: 'whiteflower'
		},
		
        {
			full: '/static/img/nature/DSC_0058.png',
			thumb: '/static/img/nature/DSC_0058thumb.jpg',
			title: 'yellowflower'
		},
		
		{
			full: '/static/img/nature/DSC085.png',
			thumb: '/static/img/nature/DSC085thumb.jpg',
			title: 'forest '
		},

		{
			full: '/static/img/nature/_DSC0281.png',
			thumb: '/static/img/nature/_DSC0281thumb.jpg',
			title: 'redflower'
		},
		{
			full: '/static/img/nature/_DSC1409.png',
			thumb: '/static/img/nature/_DSC1409thumb.jpg',
			title: 'lake'
		},
		
		{
			full: '/static/img/nature/DSC_1986.png',
			thumb: '/static/img/nature/DSC_1986thumb.jpg',
			title: 'cherryflower '
		},
        
		{
			full: '/static/img/nature/_DSC0218-3.png',
			thumb: '/static/img/nature/_DSC0218-3thumb.jpg',
			title: 'purpleflower '
		},
		{
			full: '/static/img/nature/DSC_0598.png',
			thumb: '/static/img/nature/DSC_0598thumb.jpg',
			title: 'grass'
		}
	];
	
</script>

<Gallery {images}/>

<style>
	

</style>
