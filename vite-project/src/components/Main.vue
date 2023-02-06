<template>
    <div>
        <h2>Hello World, lets us work on props</h2>
        <h3>My name is {{ firstName }} {{ lastName }}. I am {{ age }} years old. </h3>
        <h3>My hobbies are: {{ hobbies }}</h3>
    </div>
</template>

<script>
export default {
    name: 'Main',
    props: {
        firstName: {
            type: String,
            default: 'John',
        },
        lastName: {
            type: String,
            default: 'Doe',
        },
        age: {
            type: Number,
            default: 30,
        },
        hobbies: {
            type: Array,
            default: () => ['Reading', 'Coding', 'Swimming'],
        },

    },
    };

</script>

<style scoped>

.main {
    background-color: #f5f5f5;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
}
</style>