<script>
    import Navbar from "../components/navbar.svelte";
</script>

<!-- Fix this shit, so messy... -->
<main>
    <div class="navbar">
        <Navbar/>
    </div>
    <div class="hero">

    </div>
</main>
<footer>
    this is a footer
</footer>

<style>
    main {
        font-size: 16px;
        height: 100vh;
        background-image: url('images/bread.png');
    }
    .navbar {
       background-color: rgb(59, 59, 59);
    }
</style>
