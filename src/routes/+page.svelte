<script>
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>Inicio</title>
</svelte:head>

<section>
	<h1>
		<div class="Emanoel">
			<picture>
				<source srcset="svelte-emanoel.webp" type="image/webp" />
				<img src="svelte-emanoel.png" alt="Emanoel" />
			</picture>
		</div>

		Meu Primeiro<br />site na nuvem
	</h1>
<a
  href="https://wa.me/5521974446105?text=Vi%20seu%20site"
  target="_blank"
  style="
    display: inline-block;
    margin-top: 20px;
    padding: 12px 20px;
    background-color: #25D366;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: bold;
  "
>
  Falar comigo no WhatsApp
</a>


	<h2>
		try editing <strong>src/routes/index.svelte</strong>
	</h2>

	<Counter />
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
