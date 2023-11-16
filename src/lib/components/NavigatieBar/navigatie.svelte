<section class="section-nav">
	<nav class="nav-bar">
		<img
			src="https://hallostrandeiland.nl/blobs/gebiedsplatform/w250h250/98691/2022/50/hseTekengebied_8.png"
			alt="logo"
		/>
		<a class="nav-link" href="/">Berichten</a>
		<a class="nav-link" href="/">Activiteiten</a>
		<a class="nav-link" href="/">Over Strandeiland</a>
		<a class="nav-link" href="/">Planning</a>
		<a class="nav-link" href="/">Participatieteam</a>
		<a class="nav-link" href="/">Personen</a>
		<a class="nav-link" href="/">Organisaties</a>
		<a class="Wensen" href="/">Wensen</a>

        <details>
            <summary>
                <div class="dropdown">
                    <svg
                        width="40"
                        height="32"
                        viewBox="0 0 44 32"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                    >
                        <rect width="44" height="4" fill="" />
                        <rect y="14" width="44" height="4" fill="" />
                        <rect y="28" width="44" height="4" fill="" />
                    </svg>
                    
                </div>
            </summary>
            <ul>
                <li>
                    <a href="/">
                        Berichten</a
                    >
                </li>
                <li>
                    <a href="/">
                        Activiteiten</a
                    >
                </li>
                <li>
                    <a href="/">
                        Over Strandeiland</a
                    >
                </li>
                <li>
                    <a href="/">
                        Planning
                </li>
                <li>
                    <a href="/">
                        Participatieteam
                </li>
                <li>
                    <a href="/">
                        Personen
                </li>
                <li>
                    <a href="/">
                        Organisaties
                </li>
                <li>
                    <a href="/">
                        Wensen
                </li>
			</ul>
	</nav>
</section>

<style>

    /* Image */

    img{
    max-width: 70px;
    max-height: 70px;
}

	/* Mobile nav */
	.nav-bar {
		display: flex;
		background-color: var(--color-secundary-pure);
		justify-content: space-between;
		border-bottom-style: solid;
		border-width: 0.5px;
        padding-left: 50px;
        padding-right: 50px;
	}


	.nav-bar img {
		width: 86.5px;
		aspect-ratio: 1/1;
	}

   
	.nav-link {
		margin-top: 30px;
		text-decoration: none;
		color: black;
        display: none;
	}

	.nav-link:hover {
		transform: scale(1.1);
		transition-duration: 1s;
	}

	.Wensen {
		background-color: yellow;
		text-decoration: none;
		color: black;
		padding: 20px;
		border-radius: 20px;
		margin: 10px;
        display: none;
	}

	.Wensen:hover {
		transform: scale(1.1);
		transition-duration: 1s;
	}

	@media (min-width: 970px) {
        .nav-link{
            display: block;
        }
        .Wensen{
            display: block;
        }
        details{
        display: none;
        
    }
	}

    svg{
        width: 20px;
    }

    details .dropdown svg {
		fill: var(--color-primary);
	}

    details{
        margin: 10px;
        margin-top: 30px;
        text-align: right;
    }
  
  
    ul{
        list-style-type: none;
        padding-top: 10px;
    }
    
    li{
        text-decoration: none;
        padding: 5px;
        border-radius: 10px;
    }

    li:hover{
        transform: scale(1.1);
        transition-duration: 1s;
        background-color: yellow;
    }

    a{
        text-decoration: none;
        color: black;
    }

	details > summary {
  list-style: none;
}

details summary::-webkit-details-marker {
  display:none;
}



</style>
