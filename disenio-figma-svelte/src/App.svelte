<script>
    import Header from "./componentes/Header.svelte";
    import ImagenesFondo from "./componentes/ImagenesFondo.svelte";


</script>

<main>
	<div class="contenedor-principal">
		<div class="contenedor-header">
			<Header />
		</div>
		<div class="contenedor-contenido">
			<ImagenesFondo />
		</div>
	</div>
</main>

<style>
	.contenedor-principal{
		width: 100%;
	}
</style>