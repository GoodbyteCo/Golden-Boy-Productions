<template>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<link rel="icon" type="image/svg+xml" href="/favicon.svg">
	<meta name="theme-color" content="#fff4bd" media="(prefers-color-scheme: light)">
	<meta name="theme-color" content="#000000" media="(prefers-color-scheme: dark)">
</template>

<!-- eslint-disable-next-line vue-scoped-css/enforce-style-type -->
<style>
	@font-face
	{
		/* move to CDN */
		font-family: 'Roboto Extremo';
		src: url('assets/RobotoExtremo.ttf') format('truetype');
		/*
			url('assets/webfont-2.woff2') format('woff2'),
			url('assets/webfont-2.woff') format('woff'),
		*/
	}

	:root
	{
		--white: #fffcf0;
		--pale-yellow: #fff4bd;
		--bright-yellow: #fee305;
		--gold: #db8906;
		--black: #000000;

		--background: var(--pale-yellow);
		--foreground: var(--black);

		--roboto-extremo: 'Roboto Extremo', sans-serif;
	}

	html, body
	{
		background: var(--background);
		color: var(--foreground);
		font-family: var(--roboto-extremo);
		font-size: 10px;
		letter-spacing: 0.04em;
		text-transform: uppercase;
		margin: 0;
		padding: 0;
	}
</style>