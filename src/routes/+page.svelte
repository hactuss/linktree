<script>
	let NUMBER_EQUALS_CHARACTERS = 6;
	let EQUAL_CHARACTERS = '='.repeat(20);
	let MAIN_WIDTH = 0;
	let MAIN_MIN_WIDTH = 1700;
	function setAmountofEqualCharacters() {
		EQUAL_CHARACTERS.repeat(+1);
		return console.log(NUMBER_EQUALS_CHARACTERS);
	}
	//console.log(visualViewport?.width + "x" + visualViewport?.height);
	console.log('https://haj-links.vercel.app/signs');
</script>

<!--
<p>Actual width: {MAIN_WIDTH}</p>
<p>Min width: {MAIN_MIN_WIDTH}</p> -->
<main id="main-container" bind:clientWidth={MAIN_WIDTH}>
	<div id="inner-content">
		<div>┏{EQUAL_CHARACTERS}┓</div>
		<div>
			<br />
			<h1>Hactuss</h1>
			<br />
			<img
				src="https://media1.tenor.com/m/mc3OyxhLazUAAAAC/doggo-doge.gif"
				alt=""
				width="150px"
			/>
			<br />
			<a href="https://hactuss.vercel.app">Homepage</a>
			<a href="https://youtube.com/@hactuss">YouTube</a>
			<a href="https://hactuss.newgrounds.com">Newgrounds</a>
			<a href="https://steamcommunity.com/profiles/76561199810742102">Steam</a>
			<a href="https://github.com/hactuss">Github</a>
			<br />
			<a href="https://hactuss-portfolio.vercel.app/"> ---- my portfolio ----</a>
			<br />
			<h2>passion projects</h2>
			<ul>
				<li><a href="https://isitspookymonth.vercel.app">is it spooky month?</a></li>
				<li><a href="https://hactuss.github.io/pages/office/office.html">worldclock</a></li>
				<li><a href="https://center-calc.vercel.app">center calculator</a></li>
				<li><a href="https://uk-terminal.vercel.app">ultrakill terminal</a></li>
			</ul>
		</div>
		<div>┗{EQUAL_CHARACTERS}┛</div>
		<a href="/signs">signs</a>
	</div>
</main>

<!-- ▎▒-->
<style>
	#main-container {
		margin-top: 50px;
		display: flex;
		justify-content: center;
	}
</style>
