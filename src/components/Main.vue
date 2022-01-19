<template>
    <main class="container mt-5">
        <div class="row row-cols-5">
            <Card />
        </div>
    </main>
</template>

<script>
import axios from 'axios';
import Card from './Card.vue';

export default {
    name: 'Main',
    components: {
        Card,
    },
    data(){
        return{
            disc:[],
            query:'https://flynn.boolean.careers/exercises/api/array/music',
        }
    },
    created() {
        axios.get(this.query)
        .then((result) => {
            console.log(result);
        })
        .catch((error) => {
            console.log(error);
        })
    },
};

</script>

<style>

</style>