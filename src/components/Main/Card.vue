<script>
export default {
    name: 'Card'
}
</script>

<template>
    <div class="card">
        <div class="image">
            <img src="https://picsum.photos/id/1/200/300" alt="">
        </div>
        <h2>Card Name</h2>
        <div class="race">Race</div>
    </div>
</template>

<style lang="scss" scoped>
@use '../../assets/styles/partials/variables' as *;

.card {
    background-color: $primary-color;
    flex-basis: 20%;
    margin: 0 $cards-margin $cards-margin;
    text-align: center;

    h2 {
        color: $secondary-color;
        margin: 1.875rem 1.25rem;
    }

    .race {
        color: $tertiary-color;
        margin-bottom: 1.875rem;
    }
}
</style>