<div class="container">
    <span>CATAPULT</span>
    <nav>
        <ul class="nav-items">
            <li><a href="#top">Contacts</a></li>
            <li><a href="#top">About</a></li>
            <li><a href="#top">Product List</a></li>
        </ul>
    </nav>
</div>

<style>
    .container, .nav-items {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        color: white;
    }
    .container {
        padding: 20px;
        margin-inline: 20%;
    }
    .nav-items {
        gap: 20px;
        list-style-type: none;
    }
    .nav-items a {
        text-decoration: none;
        transition: all 0.2s;
        color: white;
    }
    .nav-items a:hover {
        color: rgba(255, 255, 255, 0.616);
    }
</style>