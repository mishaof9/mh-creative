<script>
	import Gallery from '$lib/Gallery.svelte';
	let images = [
		{
			full: '/static/img/Street/DSC_0723.jpg',
			thumb: '/static/img/Street/DSC_0723thumb.jpg',
			title: 'bikes'
		},
		{
			full: '/static/img/Street/DSC_0700.png',
			thumb: '/static/img/Street/DSC_0700thumb.jpg',
			title: 'bike'
		},
		{
			full: '/static/img/Street/DSC_0952.png',
			thumb: '/static/img/Street/DSC_0952thumb.jpg',
			title: 'gothic'
		},
		{
			full: '/static/img/Street/DSC_0313.jpg',
			thumb: '/static/img/Street/DSC_0313thumb.jpg',
			title: 'londoneye'
		},
		{
			full: '/static/img/Street/DSC_0634.jpg',
			thumb: '/static/img/Street/DSC_0634thumb.jpg',
			title: 'man'
		},
		{
			full: '/static/img/Street/DSC_0939.jpg',
			thumb: '/static/img/Street/DSC_0939thumb.jpg',
			title: 'lady'
		},
		{
			full: '/static/img/Street/_DSC0287.jpg',
			thumb: '/static/img/Street/_DSC0287thumb.jpg',
			title: 'londonmarket'
		},
		{
			full: '/static/img/Street/DSC_0735.png',
			thumb: '/static/img/Street/DSC_0735thumb.jpg',
			title: 'amsterdam'
		},
		{
			full: '/static/img/Street/_DSC0288.jpg',
			thumb: '/static/img/Street/_DSC0288thumb.jpg',
			title: 'londonmarket'
		}
	];
</script>

<Gallery {images} />

<style>
</style>
