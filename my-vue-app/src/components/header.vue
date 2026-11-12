<template>
    <header>
        <h1>Мій перший vue Додаток</h1>
    </header>
</template>
<script>
export default {
    name:'HeaderComponent',
    props: {
        title:{
            type:String,
            required:true
        }
    }
}
</script>
<style scoped>
header{
    background-color: navy;
    color: white;
    padding: 15px;
    text-align: center;
}
</style>