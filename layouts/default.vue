<template>
	<div>
		<header>
			<div class="container flex">  
				<nuxt-link class="linkToMain" to="/">
					<img class="logo" src="logo-min.png" alt="universal-stroy">
				</nuxt-link>
				<nav>
					<nuxt-link to="/goods">Продукция</nuxt-link>
					<nuxt-link to="/ourworks">Наши работы</nuxt-link>
					<nuxt-link to="/articles">Статьи</nuxt-link>
					<nuxt-link to="/about">О компании</nuxt-link>
					<nuxt-link to="/contacts">Контакты</nuxt-link>
				</nav>
				<p class="phoneNumber">(812) 992-92-92</p>
			</div>
		</header>
		<nuxt />
	</div>
</template>

<style>
a{
	text-decoration: none;
}
.container{
	max-width: 80%;
	margin: 0 auto;
}
.flex{
	display: -webkit-flex;
	display: -moz-flex;
	display: -ms-flex;
	display: -o-flex;
	display: flex;
	-ms-align-items: center;
	align-items: center;
	justify-content: space-between;
}
.justify-content-between{
	justify-content: space-between;
}
.align-center{
	text-align: center;
}
header{
}
.linkToMain{
	width: 10%;
}
.logo{
	width: 100%;
}
nav{

}
nav a {
	margin-left: 1.5em;
}
.phoneNumber{
	font-size: 1.5em;
	font-weight: 600;

}
/*MAIN*/
.banner{
	background: #777;
	box-sizing: border-box;
	width: 100%;
	height: 30vh;
	text-align: center;
	padding-top: 7vh;
	color: white;
}
.banner_button{
	color: white;
	background: rgba(0,0,0,0.3);
	border: 2px solid orange;
	width: 10%;
	height: 2.5em;
}
.categoriesTile{	
	-webkit-flex-wrap: wrap;
	-moz-flex-wrap: wrap;
	-ms-flex-wrap: wrap;
	-o-flex-wrap: wrap;
	flex-wrap: wrap;
	margin: 2em 0
}
.categoriesTile_elem{
	width: 24%;
	text-align: center;
}
.category{
	position: relative;
}
.category img{
	width: 100%;
}
.categoriesTile_elem:hover .properties{
	display: block;
}
.properties{
	box-sizing: border-box;
	padding-top: 2em;
	display: none;
	position: absolute;	
	top:0;
	width: 100%;
	height: 100%;
	color: white;
	font-size: 1.5em;
	background: rgba(0,0,0,0.5);
}
.ourClients{
	text-align: center;
}
.ourClients img{
	width: 80%;
}
</style>
