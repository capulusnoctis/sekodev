<script>
    import Navbar from './Navbar.svelte';
</script>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100&family=Quicksand:wght@500&display=swap');

    .Header-container {
        background-color: #000;
    }
    .Header-container header {
        width: 100%;
        display: flex;
        justify-content: space-around;
        align-items: center;
        font-family: 'Quicksand';
        color: #ebebeb;
    }
    .Header-title {
        padding: 0.5em 1.4em;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .Header-picture {
        padding: 1em 1.5em;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .Header-picture img {
        border: 0;
        border-radius: 100%;
        width: 24em;
        height: 24em;
        filter: drop-shadow(0.8);
    }
</style>

<div class="Header-container">
    <Navbar/>
    <header>
        <div class="Header-title">
            <h1>SEKO</h1>
            <h2>Frontend Developer</h2>
        </div>
        <div class="Header-picture">
            <img src="https://ik.imagekit.io/sekosolares/SekoSite/profile_actualizado_AQl1d2En6.jpeg" alt="Imagen de Seko Solares">
        </div>
    </header>
</div>