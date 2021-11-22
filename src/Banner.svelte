<script>
    export let text;
    export let color = "black";
</script>

<div class="banner" style="color: {color}">
    {text}
</div>

<style>
    .banner {
        text-align: center;
        font-weight: bold;
        font-size: 1.5em;
        padding: 5px;   
    }
</style>    