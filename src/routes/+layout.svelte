<script>
</script>

<header>
    <p>CATAPULT</p>
    <div>
        <nav>
            <ul>
                <li><a href="#">About</a></li>
                <li><a href="#">Product List</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
        <div class="box"></div>
        <div class="box"></div>
        <div class="box"></div>
    </div>
</header>
<slot />
<footer />

<style>
    .box {
        width: 50px;
        height: 50px;
        background-color: red;
        padding: 20px;
        margin: 10px;
    }
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
    he312312ader {
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
