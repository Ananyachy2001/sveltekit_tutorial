<script>
import Title from "$lib/title.svelte";
import '../styles/global.css'
</script>


<header>
    <Title title="Pro Gaming Guides" />
</header>

<main>
    <!-- page content -->
     <slot></slot>
</main>

<footer>
    <p>Copyright 2024 Pro Gaming Guides</p>
</footer>

<style>
    header{
        display: flex;
        justify-content: center;
    }

    main{
        max-width: 960px;
        margin: 20px auto;
    }
    footer{
        text-align: center;
    }
</style>