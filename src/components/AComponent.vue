<template>
    <div>
        <h1>A Component</h1>
        <p>{{appVersion}}</p>
    </div>
</template>

<script>
import BaseComponent from './BaseComponent.vue'
export default {
    name: 'AComponent',
    mixins: [BaseComponent]
}
</script>