<template>
    <div class="primer_diseño">
        <p>Mi primer parrafo afgnEJIFNJGNegjirgmnqJIGNEROGJNejigrnj</p>
    </div>
    <div id="form" class="container">
        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Nombre y apellido</label>
            <input type="text" class="form-control" id="text1" placeholder="Coloque sus nombres">
        </div>

        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Cedula</label>
            <input type="number" class="form-control" id="text2" placeholder="Numero de identificacion">
        </div>

        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Email address</label>
            <input type="email" class="form-control" id="text3" placeholder="name@example.com">
        </div>
        <div class="mb-3">
            <label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
            <textarea class="form-control" id="text4" rows="3"></textarea>
        </div>
        <button type="submit">Enviar registro</button>
    </div >

</template>

<script setup>

</script>

<style scoped>
    .primer_diseño{
        background-color: rgb(122, 72, 240);
        width: 400px;
        height: 300px;
        position: relative;
        padding: 14px;
        margin: 4px;
        top: 50%;
        left: 40%;
    }
</style>

