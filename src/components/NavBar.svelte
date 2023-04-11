<script>
    import Menu from "./Menu.svelte";
</script>

<nav>
    <p class="home">home</p>
    <Menu />
</nav>

<style>
    nav{
        display: flex;
        height: 3rem;
        justify-content: space-between;
        align-items: center;
    }
</style>