<script lang="ts">
	export let name: string;
</script>

<main>
	<header class="App-header">
		<a href="https://powerfleet.fathym-it.com/"><img src="assets/powerfleet-logo-80.jpg" class="pf-logo" alt="logo" /></a>
		<div class="siteNav">
			<a href="https://powerfleet.fathym-it.com/dash1" target="_blank">
			<button class="navbutton">Dash 1</button>
			</a>
			<a href="https://powerfleet.fathym-it.com/dash2" target="_blank">
			<button class="navbutton">Dash 2</button>
			</a>
			<a href="https://powerfleet.fathym-it.com/dash3" target="_blank">
			<button class="navbutton">Dash 3</button>
			</a>
		</div>
	</header>
	<div class="dashboard">
		<iframe title="powerfleet-LV450-reefer-tracking - Page 1" width="1540" height="941.25" src="https://app.powerbi.com/view?r=eyJrIjoiOGJjYTA0MzktMWY4MS00M2I4LTkzYTctMjRmNzQ1YjU1YjU5IiwidCI6IjZkY2JlYmQwLWY4ZDAtNGE5ZC04OWU1LTU4NzNlODE0NmIwYSIsImMiOjR9" frameborder="0" allowFullScreen="true"></iframe>
		<div class="builtin">
			Built in Svelte<br>
			<img src="assets/svelte2.jpg" class="frameworkImage" alt="Svelte" />
		</div>
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
		width: 345px;
		height: 70px;
		padding: 1rem 0 2rem 4rem;
	}

	.dashboard {
		text-align: center;
		padding-top: 1rem;
		margin: 0 auto;
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
</style>