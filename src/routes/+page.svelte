<script>
    import Card from '../components/card.svelte'
</script>

<section>
    <div class="hero-container">
        <p style="font-size: 64px;">
            <span
                style="color: gold; font-size: 64px; font-family: 'Kelly Slab', cursive;"
                >CATAPULT</span
            >
            your taste with<br />the freshest bread<br />on the block!
        </p>
    </div>
</section>

<!-- Hero Background -->
<div class="gradient_black" />
<div class="background_movable" />
<!-- End -->

<section class="menu-section">
    <div class="container">
        <h2>What's Hot and Pipin'?</h2>
        <div class="items">
            <Card>
                <img slot="bread-image" src="/images/bread.jpeg" alt="">
                <p slot="bread-name">Bread Bread</p>
                <p slot="bread-price">200 PHP</p>
            </Card>
            <Card>
                <img slot="bread-image" src="/images/bread.jpeg" alt="">
                <p slot="bread-name">Bread Bread</p>
                <p slot="bread-price">200 PHP</p>
            </Card>
            <Card>
                <img slot="bread-image" src="/images/bread.jpeg" alt="">
                <p slot="bread-name">Bread Bread</p>
                <p slot="bread-price">200 PHP</p>
            </Card>
        </div>
    </div>
</section>

<style>
    .hero-container {
        margin-inline: 10%;
        display: flex;
        align-items: center;
        justify-content: left;
        gap: 500px;
        height: calc(100vh - 79px);
    }
    .background_movable {
        width: 100%;
        height: 100%;
        overflow: hidden;
        position: fixed;
        top: 0;
        left: 0;
        z-index: -2;
        background-image: url("/images/bread.jpeg");
        background-repeat: no-repeat;
        background-size: cover;
    }
    .gradient_black {
        background-image: linear-gradient(black, transparent);
        width: 100%;
        height: 100%;
        position: fixed;
        top: 0;
        left: 0;
        z-index: -1;
    }
    .menu-section {
        background-color: black;
        padding-block: 30px;
    }
    .menu-section .container {
        margin-inline: 10%;
        padding-block: 20px;
    }
    img {
        max-width: 200px;
        height: auto;
    }
    .items {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 200px;
    }
    .container {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }
    h2 {
        padding-block-end: 50px;
    }
</style>
