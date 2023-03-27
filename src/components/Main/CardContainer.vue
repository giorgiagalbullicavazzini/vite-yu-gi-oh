<script>
import Card from './Card.vue';

export default {
    name: 'CardContainer',
    components: {
        Card
    }
}
</script>

<template>
    <div class="small-container">
        <div class="smaller-container">
            <div class="found-cards">
                Found 39 cards
            </div>
            <div class="cards">
                <Card />
                <Card />
                <Card />
                <Card />
                <Card />
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../../assets/styles/partials/variables' as *;

.small-container {
    background-color: $secondary-color;
    padding: 35px;

    .found-cards {
        background-color: $tertiary-color;
        color: $secondary-color;
        font-weight: 600;
        padding: 15px;
    }

    .cards {
        display: flex;
        justify-content: space-between;
        margin: 0 (-$cards-margin);
    }
}
</style>