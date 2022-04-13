<script>
	import Social from '$lib/Social.svelte';
</script>

<footer class="container-fluid ">
	<!-- full footer, for large screens -->
	<div class="row  d-none d-md-flex justify-content-center">
		<div class=" col col-4">
			<p><small> &copy; Copyright {new Date().getFullYear()}.</small></p>
			<p><small> All rights reserved.</small></p>
		</div>
		<div class=" col col-4">
			<p><strong>Contact</strong></p>

			<p><a href="mailto:mihaela.hagiu@hotmail.com" class="mail">mihaela.hagiu@hotmail.com</a></p>
		</div>

		<div class="col col-4">
			<p>Follow us on:</p>
			<Social />
		</div>
	</div>
   <!--for smaller screens-->
	<div class="row d-block .d-sm-none d-md-none justify-content-center">
		<div class=" col col-4">
			<p><small> &copy; Copyright {new Date().getFullYear()}.</small></p>
			<p><small> All rights reserved.</small></p>
		</div>
		<div class=" col col-4">
			<p><strong>Contact</strong></p>

			<p><a href="mailto:mihaela.hagiu@hotmail.com" class="mail">mihaela.hagiu@hotmail.com</a></p>
		</div>

		<div class="col col-4">
			<p>Follow us on:</p>
			<Social />
		</div>
	</div>
</footer>

<style>
	footer {
		width: 100%;
		margin-top: auto;
		margin-bottom: 0;
		padding-bottom: 10px;
		border-top: 1px dotted rgb(112, 111, 111) ;
	}

	footer > div {
		padding: 0 4%;
		padding-top: 10px;
		justify-content: center;
	}
	footer a {
		text-decoration: none;
		color: rgb(214, 211, 211);
		font-family: Verdana, Geneva, Tahoma, sans-serif;
		font-size: 20px;
	}
	footer div {
		color: rgb(214, 211, 211);
		font-family: Verdana, Geneva, Tahoma, sans-serif;
		font-size: 20px;
		justify-content: center;
	}
	.mail {
		color: rgb(214, 211, 211);
	}
	
</style>
