<template>
    <div v-for="item in data">
        <div>{{item.title}}</div>
        <div>{{item.subtitle}}</div>
        <div>{{item.body}}</div>
    </div>
</template>
<script setup>
    const data = [
        {
            title: 'Titulo1',
            subtitle: 'Subtitulo1',
            body: 'Body1',
        },
        {
            title: 'Titulo2',
            subtitle: 'Subtitulo2',
            body: 'Body2',
        },
        {
            title: 'Titulo3',
            subtitle: 'Subtitulo3',
            body: 'Body3',
        }
    ]
</script>

<style scoped>
</style>