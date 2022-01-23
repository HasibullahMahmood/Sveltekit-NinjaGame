<script>
	let title = 'Ninja';

	const updateTitle = () => {
		title = 'New Ninja';
	};
</script>

<main class="index">
	<h2>{title}</h2>
	<p>
		Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem aut labore magnam, quod ad ipsa vero perspiciatis
		tenetur eos est unde in? Ut nam sunt numquam dolor earum natus a aliquam fugit debitis neque mollitia,
		laudantium deserunt ratione, alias eius voluptas illo consequuntur? Nihil officiis eveniet aspernatur dolores
		itaque, eligendi sed odio nulla veritatis amet, mollitia ducimus culpa quae tempore!
	</p>
	<button on:click={updateTitle}>Update Tile</button>
	<input type="text" bind:value={title} />
</main>

<style>
	.index {
		margin: 20px auto;
		text-align: center;
	}
</style>
