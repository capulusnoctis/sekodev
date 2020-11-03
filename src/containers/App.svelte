<style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100&family=Quicksand:wght@500&display=swap');

    :global(body) {
        padding: 0;
        margin: 0;
    }
    div.main {
        display: grid;
        grid-template-columns: repeat(4, 1fr);
        column-gap: 20px;
        margin: 0 10px;
    }
    div.main-container {
        grid-column: 1 / 5;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-around;
        font-family: 'Quicksand', sans-serif;
        color: #E5EBEF;
    }
    div.main-container h1 {
        font-family: 'Montserrat', sans-serif;
        letter-spacing: 0.35em;
        font-size: 5em;
    }
    .bg-image {
        position: absolute;
        top: 0;
        left: -10em;
        bottom: 0;
        right: 0;
        filter: brightness(0.5);
        filter: drop-shadow(1.8);
        z-index: -1;
    }
</style>

<div class="main">
    <img src="https://ik.imagekit.io/sekosolares/SekoSite/FB_IMG_1584824595407_QVRBO0TbX.jpg" class="bg-image" alt="background_image">
    
    <div class="main-container">
        <h1>SEKO</h1>
        <h2>Developing Experiences</h2>

        <span>Site is Under Construction</span>
    </div>
</div>