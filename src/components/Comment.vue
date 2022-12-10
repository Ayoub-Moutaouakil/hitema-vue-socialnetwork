<template>
    <div id="comment">
        <div id="comment-info">
            <div id="comment-info-user">
                <h3 id="h3-title">Béatrice</h3>
            </div>
            <div id="comment-info-date">
                <h4 id="h4-info">Posté le 10/12/2022 à 13h01</h4>
            </div>
        </div>
        <div id="comment-section">
            <p id="comment-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>

#comment {
    width: 100%;
    height: auto;
    display: flex;
    flex-direction: column;
    border-bottom: 1px solid lightgray;
}

#comment-info {
    width: 100%;
    height: 40px;
    display: flex;
    flex-direction: row;
}

#comment-info-user {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
}

#h3-title {
    font-size: 15px;
    font-weight: 600;
    margin-left: 20px;
}

#h4-info {
    font-weight: 500;
    margin-right: 20px;
}

#comment-info-date {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
}

#comment-section {
    width: 100%;
    height: auto;
}

#comment-text {
    padding-left: 20px;
}

</style>