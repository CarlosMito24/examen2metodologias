<template>
    <div>
        <form class="formulario">
            <legend>
                <h2>Formulario Metodologias</h2>
            </legend>
            <br/>
            <label> Nombre: </label>
            <input type="text" />
            <br />
            <label> Apellido: </label>
            <input type="text" />
            <br />
            <label> Teléfono: </label>
            <input type="text" />
            <br />
            <label> Usuario: </label>
            <input type="text" />
            <br />
            <label> Contraseña: </label>
            <input type="password" />
            <br />
            <button type="submit">Registrarse</button>

        </form>
    </div>
</template>

<script>

</script>

<style scoped>
*
{
    font-family: Arial, Helvetica, sans-serif;
}

.formulario {
    width: 500px;
    display: block;
    margin: auto;
    margin-top: 20px;
    border-radius: 20px;
    border: 1px solid #ccc;
    padding: 20px;
    background: #ccc;
}

h2 {
    font-weight: bold;
}

label {
    margin: 10px;
}

input {
    margin: 10px auto;
    display: block;
    width: 400px;
    height: 25px;
}

button {
    margin-left: 10px;
    background-color: #48e;
    width: 200px;
    height: 40px;
    font-size: 15px;
    border-radius: 10px;
    border: none;
    color: #FFF;
    margin: auto;
    display: block;
}
</style>