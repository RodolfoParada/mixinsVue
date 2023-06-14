<template>
    <div>
        <h1>B Component</h1>
        <button @click="clickHandler">Click me</button>
        <p>{{appVersion}}</p>
    </div>
</template>

<script>
import BaseComponent from './BaseComponent.vue'
export default {
    name: 'BComponent',
    mixins: [BaseComponent],
    methods: {
        clickHandler() {
            this.appVersion = "1.2.4"
        }
    }
}
</script>