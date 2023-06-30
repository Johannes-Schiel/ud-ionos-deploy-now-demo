<template>
	<main>
		<HeroCard />
		<Footer />
	</main>
</template>

<style lang="scss">
	:root {
		--prime: #ff6e48;
		--ciBlue: #00fff1;
		--ciRed: #ff00aa;
		--ciGreen: #46fcb4;
		--ciWhite: #ffffff;
		--second: #0c1016;
		--ciGrey: #dadada;
		--roboto: 'Roboto', sans-serif;
	}

	@font-face {
		font-family: var(--roboto);
		src: url('@/assets/fonts/Roboto-Regular.ttf');
		font-weight: 500;
	}

	body,
	html {
		background-color: var(--second);
		font-size: 10px;
		width: 100%;
		height: 100%;
		margin: 0;
		padding: 0;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	* {
		box-sizing: border-box;
	}
</style>
