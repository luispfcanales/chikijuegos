<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>chikijuegos tiene como mision convertirse en el salon de juegos de niños preferidos por las familias de puerto Maldonado y asi poder extender nuestra marca a nivel nacional.</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
