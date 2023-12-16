<script>
	import 'bulma/css/bulma.min.css';
</script>

<header>
	<!-- svelte-ignore a11y-no-redundant-roles -->
	<nav class="navbar" role="navigation" aria-label="main navigation">
		<div class="navbar-brand">
		  <a class="navbar-item" href="/">
			<img src="/logo.png" alt="Estonya Startup Topluluğu">
		  </a>
	  
		  <!-- svelte-ignore a11y-missing-attribute -->
		  <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
			<span aria-hidden="true"></span>
			<span aria-hidden="true"></span>
			<span aria-hidden="true"></span>
		  </a>
		</div>

		<div class="navbar-end">
			<div class="navbar-item">
			  <div class="buttons">
				<!-- svelte-ignore a11y-missing-attribute -->
				<a href="https://estonyastartup.com.tr/blog" class="button is-primary">
				  <strong>Blog</strong>
				</a>
				<!-- svelte-ignore a11y-missing-attribute -->
				<a href="https://instagram.com/estonya.startup" class="button is-light">
					<i class="fa-brands fa-instagram"></i>
				</a>
				<!-- svelte-ignore a11y-missing-attribute -->
				<a href="https://x.com/estonyastartup" class="button is-light">
					<i class="fa-brands fa-x-twitter"></i>
				</a>
				<!-- svelte-ignore a11y-missing-attribute -->
				<a href="https://www.threads.net/@estonya.startup" class="button is-light">
					<i class="fa-brands fa-threads"></i>
				</a>
			  </div>
			</div>
		  </div>

	  </nav>
</header>

<style>
a:link {
  text-decoration: none;
}

a:visited {
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

a:active {
  text-decoration: underline;
}


</style>
