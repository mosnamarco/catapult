<script>
</script>

<header>
    <p>CATAPULT</p>
    <nav>
        <ul>
            <li><a href="#">About</a></li>
            <li><a href="#">Product List</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
    </nav>
</header>
<slot />
<footer />

<style>
    header p {
        font-family: 'Kelly Slab', cursive;
        color: gold;
    }
    header,
    nav ul {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    header {
        justify-content: space-between;
        padding-block: 20px;
        margin-inline: 10%;
    }
    nav ul {
        gap: 50px;
    }
    nav ul li {
        list-style: none;
    }
    nav ul li a {
        text-decoration: none;
    }
</style>
