<script>
import CardSearch from './CardSearch.vue';
import CardContainer from './CardContainer.vue';

export default {
    name: 'AppMain',
    components: {
        CardContainer,
        CardSearch
    }
}
</script>

<template>
    <main>
        <CardSearch />
        <CardContainer />
    </main>
</template>