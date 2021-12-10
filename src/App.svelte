<script>
	import Chart from "./Chart.svelte"
</script>

<main>
  <section class = "title">
    <h1>Svelte Heatmap</h1>
  </section>

	<Chart />

</main>

<style>
	main {
		text-align: center;
		margin: 0 auto;
    font-family: "Inter", sans-serif;
    padding: 0 1em;
    max-width: 50em;
	}


	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

</style>