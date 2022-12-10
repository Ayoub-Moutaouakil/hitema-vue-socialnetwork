<template>
    <div id="form">
        <div id="form-title">
            <h2 id="h2-title">Créer un nouveau profil</h2>
            <img id="form-image" src="../assets/images/user.png" />
        </div>
        <form id="form-main">
            <input id="form-input" type="text" placeholder="pseudo" />
            <input id="form-input" type="email" placeholder="votre@email.fr" />
            <input id="form-input" type="password" placeholder="password" />
            <input id="form-input" type="password" placeholder="confirmer password" />
            <input id="form-input" type="text" placeholder="url de votre image" />
            <input id="form-submit" type="submit" />
        </form>
    </div>
</template>

<script setup>

</script>

<style scoped>

#form {
    width: 95%;
    height: auto;
    margin-top: 30px;
    margin-bottom: 10px;
    border-radius: 10px;
    border: 1px solid black;
    display: flex;
    flex-direction: column;
    background-color: #F5F5F5;
}

#form-title {
    width: 100%;
    height: 80px;
    display: flex;
    align-items: center;
}

#h2-title {
    font-size: 30px;
    margin-left: 20px;
}

#form-image {
    width: 50px;
    height: 50px;
    padding-left: 20px;
}

#form-main {
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 40px;
}

#form-input {
    width: 97%;
    height: 35px;
    margin-bottom: 30px;
    border-radius: 5px;
    border: 1px solid grey;
    padding-left: 10px;
    font-size: 15px;
    font-weight: 600;
}

#form-submit {
    width: 20%;
    height: 35px;
    border-radius: 5px;
    border: 1px solid black;
    font-size: 15px;
    font-weight: 600;
    background-color: green;
    color: white;
    cursor: pointer;
}

</style>