<script>
	let socials = [
		{ icon: 'facebook', href: 'https://www.facebook.com/rousse.michie/' },
		{ icon: 'instagram', href: 'https://www.instagram.com/michie_ru/' },
		
	];
</script>

{#each socials as { icon, href }}
	<a {href} target="_blank">
		<i class="bi bi-{icon}" />
	</a>
{/each}

<style>
	a {
		text-decoration: none;
		
	}
	i {
		color: #fff;
	}
</style>