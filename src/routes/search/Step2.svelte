<script lang="ts">
	export let button: HTMLInputElement

	let className: string | undefined = undefined
	export { className as class }
</script>

<div class={className}>
	<h1 class="text-xl font-semibold">Paso 2</h1>
	<p>Haces clic en el boton que dice <em>{button.value}</em></p>
</div>
