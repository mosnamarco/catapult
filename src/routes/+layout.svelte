<header>
    <h1>CATAPULT</h1>
    <nav>
        <ul>
            <li><a href="#">About</a></li>
            <li><a href="#">Product List</a></li>
            <li><a href="#">Contact Us</a></li>
        </ul>
    </nav>
</header>
<slot />
<footer></footer>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Kelly+Slab&display=swap');
    
    :global(*) {
        padding: 0;
        margin: 0;
        font-family: monospace;
        font-size: 16px;
        color: white;
    }
    :global(body) {
        height: 100vh;
        background-color: rgb(34, 34, 34);
    }
    :global(h1) {
        font-size: 32px;
        font-family: 'Kelly Slab', cursive;
    }
    header h1 {
        color: gold;
    }
    header, nav ul {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    header {
        justify-content: space-between;
        padding: 20px;
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
