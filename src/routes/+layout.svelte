<script>
    import './app.css';
</script>

<nav>
    <a href="/">home</a>
    <a href="/todo">todo</a>
    <a href="/tictactoe">tic tac toe</a>
</nav>

<slot />

<style>
    nav {
        display: flex;
        justify-content: space-evenly;
    }

    a {
        /* margin: 100px; */
        border: 1px dashed;
        padding: 10px 20px;
    }
</style>