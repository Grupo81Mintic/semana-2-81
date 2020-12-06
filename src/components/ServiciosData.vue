<template>
    <div class="card">
    <img v-bind:src="servicio.imagen" class="card-img-top" alt="..." height="300">
        <div class="card-body">
            <div class="card-header">{{servicio.servicio}}</div>
            <p class="card-text">{{servicio.detalle}}</p>
                <a href="servicio.url" class="btn btn-secondary">{{servicio.enlace}}</a>
        </div>
    </div>
</template>

<script>
export default {
    name : 'ServiciosData',
    props : ['servicio']
}
</script>


<style scoped>

</style>