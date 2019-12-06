<template>
    <v-content class="amain-layout-wrap">
    <div class="container">
        <aside class="sidebar">
            <div>Aside</div>
        </aside>
        <main>
            <nuxt/>
        </main>
    </div>
    </v-content>
</template>
<style scoped>
.sidebar{
    width: 200px;
}
.amain-layout-wrap{
    height: 100vh;
    width: 100%;
}
.container{
    display: flex;
    padding: 0px;
    margin: 0px;
    height: 100vh;
}
</style>