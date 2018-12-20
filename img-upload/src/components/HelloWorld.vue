<template>
    <div>
        <img-upload></img-upload>
    </div>
</template>

<script>
import imgUpload from './upload'
export default {
    name: "HelloWorld",
    components:{ imgUpload },
    data() {
        return {};
    }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
