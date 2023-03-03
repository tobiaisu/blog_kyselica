<template>
	<header>
		<h1>website</h1>
		<NuxtLink class="header" to="/">home</NuxtLink>
		<NuxtLink class="header" to="/contact">contact</NuxtLink>
		<NuxtLink class="header" to="/articles">articles</NuxtLink>
	</header>

	<NuxtPage/>

	<footer>
		<div>© Tobias Kyselica</div>
	</footer>
</template>

<style>
	* {
		font-family: monospace;
	  color: indianred;
	}

	h1 {
		font-size: 40px;
		margin-top: 20px;
		margin-bottom: 30px;
	}

  h2 {
	  font-size: 25px;
  }

	a.header {
		background-color: floralwhite;
	  font-size: 15px;
		margin-left: 2px;
		margin-right: 2px;
		padding: 10px 25px;
		text-decoration: none;
	  border-radius: 10px;
	}

	a.header:hover {
		background-color: antiquewhite;
	}

	header {
	  border: 2px solid beige;
		background-color: #fefefc;
	  border-radius: 10px;
	  text-align: center;
	  padding-bottom: 25px;
	}

	footer {
	  position: fixed;
	  bottom: 0;
		background-color: #fefefc;
		width: 99%;
		text-align: center;
		padding-top: 15px;
		padding-bottom: 15px;
	  border: 2px solid beige;
	  border-radius: 10px;
		margin: 0 10px 10px 0;
	}
</style>