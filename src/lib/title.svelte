<script>
    export let title = "Pro Gaming"
</script>
<div class="title">
    <img src="/controller.svg" alt="">
    <h1>{title}</h1>
</div>

<style>
    .title{
        display: flex;
    }
    .title img{
        display: inline-block;
        filter: invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg) brightness(100%)
        contrast(90%);
        width: 50px;
    }
    .title h1{
        margin-left: 10px;
    }
</style>