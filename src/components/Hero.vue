<template>
    <div class="jumbotron">
        <h2>Il tuo primo Jumbotron con Vue CLI!</h2>
        <div class="cta">
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptatem, a. Temporibus nobis ex asperiores molestiae eligendi? Doloribus, laborum id reiciendis itaque obcaecati alias sapiente esse ipsum ipsa ullam nostrum quia.</p>
            <a class="btn btn-green" href="#">Tutorial Vue CLI</a>
        </div>
    </div>
</template>

<script>
export default {
   name: "Hero"
};
</script>

<style scoped>
    /* COMMON */
    .btn{
        padding: 10px 15px;
        border-radius: 5px;
    }
    .btn-green{
        background-color: lightgreen;
        color: inherit;
    }
    a{
        text-decoration: none;
        color: inherit;
    }
    /* Jumbotron */
    .jumbotron{
        width: 100%;
        background-image: url("../assets/lake-landscape-under-purple-dusk_800.jpg");
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        color: white;
        padding: 80px 0;
        position: relative;
    }
    /* Cta */
    .cta{
        width: 50%;
        padding: 20px;
    }
    .cta p{
        padding: 20px 0;
        text-align: left;
    }
</style>