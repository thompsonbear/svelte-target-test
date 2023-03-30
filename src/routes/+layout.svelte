<nav>
    <a href="/test#square">Link to '/test#square'</a>
<a href="/">Link to Home</a>
</nav>

<slot/>

<style>
    nav{
        display: flex;
        flex-direction: column;
    }

    a{
        padding: 4px;
        text-decoration: none;
        color: black;
        border: 1px solid black;
        width: min-content;
        white-space: nowrap;
        border-radius: 8px;
        margin: 4px;
    }

    a:hover{
        background: #e0e0e0;
    }
</style>