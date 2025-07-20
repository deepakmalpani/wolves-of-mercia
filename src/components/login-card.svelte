<script lang="ts">
	import { PawPrint } from '@lucide/svelte';
</script>

<div class="card w-full max-w-md preset-filled-surface-100-900 p-4 text-center">
	<div class = "p-4">
		<PawPrint class="w-full"/>
		<h1 class="text-2xl w-full">Wolves of Mercia</h1>
	</div>
	<label class="label">
		<span class="label-text text-base">Choose your username</span>
		<input class="input mt-4" type="text" placeholder="" />
	</label>
	<button type="button" class="btn preset-filled-primary-500 m-4">START</button>
</div>
