<script>
let title = "Ananyo Gaming Guides"


const updateTitle = () => {
title = "something comepletely different"
}
</script>
<div class="index">
<h1>{title}</h1>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus amet dignissimos sint optio odit cupiditate necessitatibus eaque nemo, dolorem fugiat.</p>
<button on:click={updateTitle}>change title</button>

<input type="text" bind:value={title}>
</div>
<a href="/about">About my site</a>
<style>
.index{
    text-align: center;
    display: block;
    margin: 20px auto;
}
</style>
