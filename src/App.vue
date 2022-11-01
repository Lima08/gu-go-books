<script lang="ts">
import { defineComponent } from 'vue';
import CardComponent from './components/CardComponent.vue';

export default defineComponent({
    name: 'App',
    components: {
        CardComponent,
    },
});
</script>

<template>
    <div>
        <div>Inicio Gu Go Books</div>
        <CardComponent />
    </div>
</template>
