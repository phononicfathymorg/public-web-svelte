<script lang="ts">
	export let name: string;
</script>

<main>
	<header class="App-header">
		<a href="https://phononic.fathym-it.com/"><img src="./assets/phononic380.jpg" class="pf-logo" alt="logo" /></a>
		<div class="siteNav">
			<a href="https://phononic.fathym-it.com/dash1/">
				<button class="navbutton">Dash 1</button>
			</a>
			<a href="https://phononic.fathym-it.com/dash2/">
				<button class="navbutton">Dash 2</button>
			</a>
			<a href="https://phononic.fathym-it.com/dash3/">
				<button class="navbutton">Dash 3</button>
			</a>
		</div>
	</header>
	<br>
	<div class="dashboard">
		<iframe title="phononic-thermal-tracking" class="responsive-iframe" src="https://app.powerbi.com/view?r=eyJrIjoiNTFlNjAwYWUtOWY4Yi00ZDE4LWE2MmQtNDI1MTkxOTdkZmIwIiwidCI6IjZkY2JlYmQwLWY4ZDAtNGE5ZC04OWU1LTU4NzNlODE0NmIwYSIsImMiOjR9" frameborder="0" allowFullScreen="true"></iframe>
	  </div>
	<br>
	<div class="builtin">
		Built in Svelte<br>
		<img src="./assets/svelte2.jpg" class="frameworkImage" alt="Svelte" />
	</div>
</main>

<style>	
	.App-header {
		background-color: #fff;
	}

	.siteNav {
		float: right;
		padding: 2rem;
	}

	.navbutton {
		background-color: #5a5a5a;
		border: none;
		color: white;
		padding: 15px 32px;
		text-align: center;
		text-decoration: none;
		display: inline-block;
		font-size: 16px;
		margin: 4px 10px;
		cursor: pointer;
	}

	.pf-logo {
		width: 100%;
		height: auto;
		max-width: 380px;
		max-height: 70px;
		padding: 1rem 0 2rem 4rem;
	}

	@media only screen and (max-width: 650px) {
		.siteNav {
			float: left;
			padding: 1rem;
		}
		
		.navbutton {
			padding: 7px 16px;
			margin: 2px 5px;
		}

		.pf-logo {
			width: 100%;
			height: auto;
			padding: 1rem 0 1rem 1rem;
		}
	}

	.dashboard {
		text-align: center;
		margin: 0 auto;
		position: relative;
		overflow: hidden;
		width: 100%;
		padding-top: 56.25%;
	}
		
	.builtin {
		margin: 0 auto;
		text-align: center;
		font-family: Verdana, Geneva, Tahoma, sans-serif;
		font-size: 14px;
		font-weight: bold;
		padding:2rem;
		background-color: white;
		width: 200px;
	}

	.frameworkImage {
		padding-top:1rem;
		height: 100px;
	}

	.responsive-iframe {
		position: absolute;
		top: 0;
		left: 0;
		bottom: 0;
		right: 0;
		width: 100%;
		height: 100%;
	}
</style>