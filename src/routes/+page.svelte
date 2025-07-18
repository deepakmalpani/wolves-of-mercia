<script lang="ts">
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div>
		<div class="card w-full max-w-md preset-filled-surface-100-900 p-4 text-center">
			<label class="label">
				<span class="label-text">Enter your name</span>
				<input class="input" type="text" placeholder="Input" />
			</label>
		</div>
	</div>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}
</style>
