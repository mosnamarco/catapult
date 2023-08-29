<div class="container">
    <slot class="image" name="bread-image" />
    <slot name="bread-name" />
    <slot name="bread-price" />
</div>

<style>
    .container {
        background: rgb(29, 29, 29);
        border-radius: 20px;
        width: fit-content;
        padding: 20px;
        margin-block: 20px;
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        gap: 20px;
        animation-duration: 1s;
        animation-direction: alternate;
        animation-iteration-count: infinite;
    }
    .image {
        max-width: 200px;
        max-height: 200px;
    }
    .container:hover {
        animation-name: shadowFlare;
    }

    @keyframes throb {
        from {
            scale: 1;
        }
        to {
            scale: 1.1;
        }
    }
    @keyframes shadowFlare {
        from {
            scale: 1;
            box-shadow: none;
        }
        to {
            scale: 1.1;
            box-shadow: 0px 0px 30px 10px gold;
        }
    }
</style>
