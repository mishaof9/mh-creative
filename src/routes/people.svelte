<script>
	import Gallery from '$lib/Gallery.svelte';
    let images = [
        {
			full: '/static/img/People/_DSC0035.png',
			thumb: '/static/img/People/_DSC0035thumb.jpg',
			title: 'biker'
		},
		
        {
			full: '/static/img/People/DSC_0569.jpg',
			thumb: '/static/img/People/DSC_0569thumb.jpg',
			title: 'man'
		},
        
        {
			full: '/static/img/People/DSC_0861.jpg',
			thumb: '/static/img/People/DSC_0861thumb.jpg',
			title: 'frenchwoman'
		},
        {
			full: '/static/img/People/_DSC0276bw.png',
			thumb: '/static/img/People/_DSC0276bwthumb.jpg',
			title: 'woman'
		},
        {
			full: '/static/img/People/DSC_0062-3.jpg',
			thumb: '/static/img/People/DSC_0062-3thumb.jpg',
			title: 'model'
		},
        {
			full: '/static/img/People/_DSC0344.jpg',
			thumb: '/static/img/People/_DSC0344thumb.jpg',
			title: 'psygirl'
		},
        {
			full: '/static/img/People/DSC_0116.jpg',
			thumb: '/static/img/People/DSC_0116thumb.jpg',
			title: 'model'
		},
        {
			full: '/static/img/People/DSC_0125.jpg',
			thumb: '/static/img/People/DSC_0125thumb.jpg',
			title: 'closeup'
		},
        {
			full: '/static/img/People/DSC_0841.jpg',
			thumb: '/static/img/People/DSC_0841thumb.jpg',
			title: 'malmodel'
		}
    ]
</script>


<Gallery {images}/>

<style>
	

</style>