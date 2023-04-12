<script>
    import Menu from "./Menu.svelte";
</script>

<nav>
   <span>
    <a href="/">Home</a>
   </span>

   <span>
    <a href="/about">About</a>
   </span>

   <span>
    <a href="http://www.github.com/brnt-toast">Github</a>
   </span>

   <div>
   <a href="https://www.google.com">google</a>
   </div>
</nav>

<style>
    nav{
        display: flex;
        height: 3rem;
        justify-content: space-evenly;
        align-items: center;
    }
</style>