<style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100&family=Quicksand:wght@500&display=swap');
    .Navbar-container {
        width: 100%;
        height: 8em;
        background-color: transparent;
        color: #ebebeb;
        font-family: 'Montserrat';
    }
    .Navbar-container nav {
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 0.5em 1em;
    }
    .Navbar-container nav ul {
        list-style: none;
        display: flex;
        justify-content: flex-end;
        width: 65%;
    }

    .Navbar-container nav ul li {
        padding: 0;
        margin: 0.5em 1.2em;
    }

    .Navbar-container a {
        padding: 0.5em 1em;
        text-decoration: none;
        font-weight: 700;
        color: inherit;
    }
    .Navbar-container a:visited {
        color: inherit;
    }
</style>


<div class="Navbar-container">
    <nav>
        <a href="javascript:{console.log('Inicio')}">SEKO</a>
        <ul>
            <li><a href="javascript:{console.log('Inicio')}">Inicio</a></li>
            <li><a href="javascript:{console.log('Yo soy')}">Sobre Mí</a></li>
        </ul>
    </nav>
</div>