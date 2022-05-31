<template>
    <div>
        <h1>Child component</h1>
        <h2>{{name}}</h2>
    </div>
</template>
<script>
export default {
    name:"Child",
    props:{
        name
    }
}
</script>