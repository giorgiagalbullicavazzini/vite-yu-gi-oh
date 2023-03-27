<script>
export default {
    name: 'AppHeader',

}
</script>

<template>
    <header>
        <div class="container">
            <div class="logo">
                <a href="#"><img src="/img/yugioh-logo.png" alt="Yu-Gi-Oh Logo"></a>
            </div>
            <h1>Yu-Gi-Oh Api</h1>
        </div>
    </header>
</template>

<style lang="scss" scoped>
@use '../assets/styles/partials/variables';

header {
    background-color: variables.$secondary-color;
    .container {
        align-items: center;
        display: flex;
    
        .logo {
            margin-right: 1.25rem;
            width: 4.375rem;
        }
    
        h1 {
            font-size: 3.125rem;
            font-weight: 400;
        }
    }
}
</style>