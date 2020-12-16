<template>
    <div class="card text-white bg-dark">
        <div class="d-flex justify-content-center p-2">
            <img :src="member.image" alt="Fotografia miembro del equipo" width="200">
        </div>
        <div class="card-body">
            <p class="card-text">Cedula: {{member.codigo}}</p>
            <h5 class="card-title">{{member.nombre}}</h5>
            <p class="card-text">{{member.descripcion}}</p>
            <p class="card-text">{{member.rol}}</p>
        </div>                                        
        <div class="card-footer">
            <small class="text-muted">Miembros Equipo 57-61</small>
        </div>
    </div>
</template>

<script>
    export default {
        name: "TeamCard",
        props: {
            "member": Object
        }
    }
</script>

<style scoped>


</style>
