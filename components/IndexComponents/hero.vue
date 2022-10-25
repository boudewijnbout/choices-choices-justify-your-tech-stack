<template>
	<section>
		<h2>Communication and Multimedia Design Midterm</h2>
		<p>
			De midterm review 2022 willen we graag inzetten om feedback te krijgen op
			ons onderwijs en met het panel te kijken naar de toekomst van het
			vakgebied en ontwerp- onderwijs. Deze website beschrijft het onderwijs bij
			CMD Amsterdam, onze kritische reflectie hierop en ambities voor de
			toekomst. <br /><br />CMD Amsterdam is een leergemeenschap waarbij
			studenten, docenten en medewerkers met en van elkaar leren. Deze site is
			daar ook een voorbeeld van: de inhoud is verzorgd door docenten en
			medewerkers (Diantha Kinkhouwers, Laura van der Vlies, David de Vries, Jos
			Kok, Arif Khan, Michel Alders, Tatjana Finke en Zuzana van Polen) en het
			ontwerp is gemaakt door studenten van CMD Agency (Alana Eastman, Ryan
			Zoeters, Nina Rijntjes en Pip Harsveld), de minor Web development
			(Fabienne van den Steen, Kai van Wezel en Nathan Bommezijn) van CMD
			Amsterdam en Justin Lung (AD Frontend Design en Development, HvA) onder
			begeleiding van Joost Faber (docent), alles overzien door onze hoofddocent
			Irene Kamp.<br /><br />
			We kijken uit naar de gesprekken op 4 oktober,<br /><br />Andre Neumann -
			opleidingsmanager
		</p>
	</section>
</template>

<style>
section {
	background-color: var(--color-cmd-yellow);
	display: grid;
	/* grid-template-columns: 1fr 1fr; */
	grid-template-columns: 1fr;
	/* grid-gap: 5rem; */
	grid-gap: 2rem;
	border-left: 3px solid var(--color-black);
	border-right: 3px solid var(--color-black);
	border-bottom: 3px solid var(--color-black);
	/* padding: 6rem 5rem; */
	padding: 1rem;
}

h2 {
	/* font-size: 3.5rem; */
	font-size: 2rem;
}

p {
	font-size: 0.85rem;
}

@media (min-width: 60rem) {
	section {
		grid-template-columns: 1fr 1fr;
		grid-gap: 5rem;
		padding: 6rem 5rem;
	}

	h2 {
		font-size: 3.5rem;
	}
}
</style>
