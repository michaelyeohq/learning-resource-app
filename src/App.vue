<template>
    <TheHeader title="RememberMe"></TheHeader>
    <TheResource></TheResource>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResource from './components/learning-resources/TheResource.vue';

export default {
    components: {
        TheHeader,
        TheResource
    },
    data() {
        return {
            storedResources: [
                { id: 'official-guide', title: 'Official Guide', description: 'The official vue.js', link: 'https://vuejs.org' },
                { id: 'google', title: 'Google', description: 'Learn to Google', link: 'https://google.org' }
            ]
        }
    }
}
</script>


<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

* {
    box-sizing: border-box;
}

html {
    font-family: 'Roboto', sans-serif;
}

body {
    margin: 0;
}
</style>