<template>
    <div id='app' style='height: 100%;'>
        Helloweeen
    </div>
</template>

<script>

export default {
    name: 'App',
    components: {
    },
    data() {
        return {

        }
    }
}
</script>

<style>
body {
    background-color: #f0f8fa;
    overflow: hidden;
    background-repeat: no-repeat;
    background-position: center bottom;
    background-size: contain;

}

#app {
    height: 100%;
    font-family: MicrosoftYaHei;
}

.clearfloat:after {
    content: '';
    display: block;
    clear: both;
    visibility: hidden;
    height: 0
} 

.clearfloat {
    zoom: 1;
} 
</style>

