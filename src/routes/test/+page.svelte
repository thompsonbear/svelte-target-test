<div class="square" id="square">
    <p>This square turns red if navigating to '/test#square' from the current page but not when navigating from another page.</p>
</div>

<style>
    p{
        color: white;
        font-family: sans-serif;
        padding: 2rem;
    }
    .square{
        margin: 20px;
        background: black;
        height: 300px;
        width: 300px;
    }

    .square:target{
        background: red;
    }
</style>