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
        margin: 0 0;
        height: 100vh;
    }
    div.main::after {
        content: "";
        background-image: url('https://ik.imagekit.io/sekosolares/SekoSite/FB_IMG_1584824595407_QVRBO0TbX.jpg');
        background-repeat: no-repeat;
        background-size: cover;
        top: 0;
        left: 0;
        bottom: 0;
        right: 0;
        filter: brightness(0.42) blur(1px);
        position: absolute;
        z-index: -1;
        min-height: 420px;
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
        border-top: 1px solid;
        padding: 12px 0;
        border-bottom: 1px solid;
    }
    div.main-container span {
        font-weight: 500;
        text-align: center;
    }
    i {
        font-size: 2.2em;
        margin: 0.5em;
    }
</style>

<div class="main">
    <div class="main-container">
        <h1>SEKO</h1>
        <h2>Developing Experiences</h2>

        <span>
            <i class="fas fa-exclamation-triangle"></i>
            <br>
            Site is Under Construction
        </span>
    </div>
</div>