# Site for ENKI ONLINE
Сайт для SA:MP проекта ENKI ONLINE: www.enki-rp.ru

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Pug](https://img.shields.io/badge/Pug-FFF?style=for-the-badge&logo=pug&logoColor=A86454)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)

<details>
<summary>Изображения</summary>
    
<img src="images/home.png" />
<img src="images/news.png" />
<img src="images/newspage.png" />
<img src="images/donate.png" />
</details>

<details>
<summary>Пример кода CSS</summary>
    
```css
.info .start
{
	width: calc(100% - 30px - 270px);
	/*max-width: calc(100% - 30px);*/

	background-color: rgba(255, 255, 255, .5);
	display: flex;

	/*min-height: 350px;*/
}

.info .start .left,
.info .start .right
{
	width: 50%;
	position: relative;

	border-radius: 8px;
}

.info .start .left
{
	background-image: url('/images/main/start_bg.png');
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center;

	height: 350px;
}
.info .start .left span
{
	color: white;
	text-shadow: 0px 1px 13px rgba(0, 0, 0, 0.9);

	font-family: 'Gilroy Semibold';
	font-size: 25px;

	position: absolute;

	top: 50%;
	right: 50px;

	transform: translateY(-50%);
}
.info .start .left .bg
{
	background-image: url('/images/main/start_bike.png');
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center;

	height: 525px;
	width: 426px;

	bottom: -128px;
	left: -166px;

	position: absolute;
}


.info .start .right
{
	z-index: 10;
}
.info .start .right .text
{
	overflow: hidden;
	position: relative;

	width: 100%;
	height: 190px;
}
.info .start .right .text .text-body
{
	width: 100%;
	height: 100%;

	position: relative;
	right: calc(0% + 0%);

	display: flex;
	transition: 1.2s;
}

.info .start .right .text .text-wrap
{
	position: relative;
	flex: 0 0 100%;

	right: 0;
}

.info .start .right .bg-patron-start-leftup
{
	top: -110px;
	left: -100px;

	background-image: url('/images/main/patron_start_leftup.png');

	width: 200px;
	height: 200px;
}
.info .start .right .bg-patron-start-rightdown
{
	bottom: -130px;
	right: -107px;

	background-image: url('/images/main/patron_start_rightdown.png');

	width: 250px;
	height: 250px;
}

.info .start .right
{
	width: calc(50% - 100px);
	padding: 50px;
}
.info .start .right h2
{
	letter-spacing: 2px;
	font-weight: 500;

	font-size: 28px;

	margin-bottom: 20px;
}
.info .start .right span
{
	font-size: 16px;
}

@media screen and (max-width: 1320px)
{
	.info .start .right h2
	{
		font-size: 23px;
	}
	.info .start .right span
	{
		font-size: 14px;
	}
}

.info .start .right .bottom
{
	display: flex;
	align-items: center;

	width: calc(100% - 100px);
	position: absolute;

	bottom: 50px;
}
.info .start .right .bottom a
{
	padding: 15px 40px;
}
.info .start .right .bottom a.button-anim:hover
{
	padding-right: 55px;
}

.info .start .right .bottom .sliders
{
	display: flex;
	margin-left: 50px;
}
.info .start .right .bottom .sliders button
{
	width: 10px;
	height: 10px;

	background-color: #C4C4C4;
	border-radius: 50%;

	margin: 0 5px;

	cursor: pointer;
	transition: 1.2s;
}
.info .start .right .bottom .sliders button.sliders-select
{
	background-color: #FF9F10;
}

@media screen and (max-width: 1382px)
{
	.info .start .right
	{
		width: calc(50% - 50px);
		padding: 25px;
	}

	.info .start .right .bottom
	{
		flex-wrap: wrap;
		justify-content: center;

		bottom: 25px;
		width: calc(100% - 50px);
	}
	.info .start .right .bottom a
	{
		margin-bottom: 20px;
	}
	.info .start .right .bottom .sliders
	{
		width: 100%;

		justify-content: center;
		margin-left: 0;
	}
}


.info .shop
{
	background-image: url('/images/main/shop_bg.png');
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center;

	width: calc(270px - 40px);
	color: white;

	border-radius: 8px;

	padding: 0 20px;
	padding-top: 30px;

	position: relative;
}
.info .shop h2
{
	font-size: 32px;
	font-weight: 500;
}
.info .shop a
{
	background: linear-gradient(267.27deg, #529649 3.29%, #8EC37E 106.11%);

	position: absolute;

	bottom: 30px;
	left: 50%;

	transform: translateX(-50%);
	width: calc(100% - 40px - 20px);
	text-align: center;

	padding: 15px 0;
	font-size: 15px;
}
.info .shop a.button-anim:before
{
	background: linear-gradient(267.27deg, #8EC37E 3.29%, #529649 106.11%);
}
.info .shop a.button-anim:hover
{
	padding-right: 30px;
}



.last-news
{
	margin-top: 30px;
}
.last-news .flex
{
	margin-top: 20px;
}

.last-news .flex .news-error
{
	width: 100%;

	display: flex;
	justify-content: center;
	align-items: center;

	padding: 60px 0;
	font-size: 25px;
}

.last-news .flex .news
{
	display: flex;
	align-items: flex-start;
}
.last-news .flex .news a
{
	position: relative;

	border-radius: 8px;
	overflow: hidden;

	flex: 0 0 230px;
}
.last-news .flex .news a + a
{
	margin-left: 10px;
}
.last-news .flex .news a:hover .news-anim
{
	opacity: 1;
	visibility: visible;
	z-index: 1;
}

.last-news .flex .news a .bg
{
	width: 230px;
	height: 200px;

	background-size: cover;
	background-repeat: no-repeat;
	background-position: center;
}
.last-news .flex .news a .bg-notfound
{
	position: absolute;

	top: 0;
	left: 0;

	width: 100%;
	height: 200px;

	z-index: -1;

	background-image: url(/images/news/news_bg_notfound.png);
	background-size: 60%;
	background-repeat: no-repeat;
	background-position: center;

}

@media screen and (max-width: 1335px)
{
	.last-news .flex .news
	{
		width: 100%;
		overflow-y: auto;
	}
}

.last-news .flex .news .news-anim
{
	width: 100%;
	height: 100%;

	position: absolute;

	top: 0;
	left: 0;

	display: flex;
	justify-content: center;
	align-items: center;
	flex-wrap: wrap;

	backdrop-filter: blur(5px);
	border-radius: 8px;

	opacity: 0;
	visibility: hidden;
	z-index: -1;

	transition: .3s;
}
.last-news .flex .news .news-anim .news-anim-wrap
{
	display: flex;
	flex-wrap: wrap;

	justify-content: center;
}
.last-news .flex .news .news-anim span
{
	width: 100%;
	text-align: center;

	color: white;
	font-size: 28px;
}
.last-news .flex .news .news-anim img
{
	width: 50px;
	height: 50px;
}

.last-news .flex .arrow
{
	width: 100px;
	margin-left: 10px;

	display: flex;
	justify-content: center;
	align-items: center;

	transition: .2s;
}
.last-news .flex .arrow:hover span
{
	animation: news-arrow 2s infinite ease;
}

.last-news .flex .arrow span
{
	width: 30px;
	height: 3px;

	background-color: black;
	transform: rotate(45deg);

	position: relative;

	top: -10px;
	right: 5px;

	transition: .2s;
}
.last-news .flex .arrow span:before
{
	position: absolute;

	display: block;
	content: "";

	width: 100%;
	height: 3px;

	background-color: black;
	transform: rotate(90deg);

	top: 14px;
	left: 15px;
}

.last-news .flex .arrow span:first-child,
.last-news .flex .arrow span:first-child:before
{
	background-color: rgba(0, 0, 0, .4);
}
.last-news .flex .arrow span:first-child
{
	transform: rotate(45deg) translate(10px, -10px);
}

@keyframes news-arrow
{
	from
	{
		right: 5px;
	}
	25%
	{
		right: -5px;
	}
	50%
	{
		right: 5px;
	}
	75%
	{
		right: -5px;
	}
	100%
	{
		right: 5px;
	}
}



.servers
{
	position: relative;
	width: 100%;

	padding-bottom: 40px;
	margin-top: 150px;
}
.servers .wrap
{
	width: 100%;
	min-height: calc(100% - 220px);

	background-color: white;
	clip-path: polygon(50% 11%, 100% 0, 100% 43%, 100% 100%, 50% 90%, 0 100%, 0% 43%, 0 0);

	padding: 110px 0;
}

.servers .wrap h3
{
	width: 100%;
	text-align: center;

	font-size: 28px;
	font-weight: 500;

	margin-bottom: 30px;
}
.servers .wrap .flex
{
	justify-content: center;
	flex-wrap: wrap;

	width: 80%;
	margin: 0 auto;
}

.servers .wrap .flex .srv-info
{
	display: flex;
	align-items: center;

	margin: 5px 50px;

	border-radius: 8px;
	padding: 5px;

	position: relative;
}
.servers .wrap .flex a.srv-info section
{
	position: absolute;

	width: 100%;
	height: 100%;

	background: linear-gradient(267.16deg, #F8CE41 18.28%, #FFA010 88.97%);
	opacity: .9;

	z-index: 10;
	border-radius: 8px;

	display: flex;
	justify-content: center;
	align-items: center;

	overflow: hidden;
	color: white;

	transition: .2s;
	transform: scale(0);

	text-align: center;

	user-select: none;
	cursor: pointer;
}
.servers .wrap .flex a.srv-info:hover section
{
	transform: scale(1);
}
.servers .wrap .flex .srv-info .online-draw
{
	margin-right: 10px;

	border-radius: 100%;
	/*overflow: hidden;*/

	display: flex;
	align-items: center;
	justify-content: center;

	height: 90px;
	width: 90px;

	background: linear-gradient(267.16deg, #F8CE41 18.28%, #FFA010 88.97%);
	text-transform: uppercase;

	position: relative;
}
.servers .wrap .flex .srv-info .online-draw span
{
	position: absolute;

	top: 50%;
	left: 50%;

	transform: translate(-50%, -50%);
	font-size: 12px;
}

.servers .wrap .flex .srv-info .online-draw .online-draw-wrap
{
	width: calc(70px - 20px);
	height: calc(70px - 20px);

	border: 10px solid rgba(255, 255, 255, .3);
	border-radius: 100%;

	position: relative;
}

.servers .wrap .flex .srv-info .online-draw .online-draw-count
{
	position: absolute;

	top: 50%;
	left: 50%;

	transform: translate(-50%, -50%);
	border-radius: 50%;

	width: calc(100% + 20px);
	height: calc(100% + 20px);

	/*background-image: linear-gradient(-30deg, #t 50%, transparent 50%), linear-gradient(90deg, transparent 50%, steelblue 50%);;*/
}
.servers .wrap .flex .srv-info .online-draw .online-draw-count svg
{
	position: absolute;

	top: calc(50% + .2px);
	left: calc(50%);

	transform: rotateY(-180deg) rotate(-90deg) translate(50%, 50%);

	width: calc(100% + 10px);
	height: calc(100% + 10px);
}
.servers .wrap .flex .srv-info .online-draw .online-draw-count svg circle
{
	stroke: white;

    stroke-dasharray: 200, 200;
    stroke-dashoffset: -50;
    /*-126*/
}


.servers .wrap .flex .srv-info .other
{
	font-weight: 500;
}
.servers .wrap .flex .srv-info .other h4
{
	font-size: 25px;
	letter-spacing: .2px;
}
.servers .wrap .flex .srv-info .other .online-text
{
	display: flex;
	align-items: center;
}
.servers .wrap .flex .srv-info .other .online-text div
{
	width: 9px;
	height: 9px;

	background-color: green;
	margin-right: 5px;

	border-radius: 50%;
}

.servers .wrap .flex .srv-info .other .online-text span
{
	font-size: 14px;

	display: flex;
	align-items: center;
}
.servers .wrap .flex .srv-info .other .online-text span span
{
	font-size: 23px;
	margin-left: 5px;
}

.launcherdownload .wrap {
	height: 485px;
}
.launcherdownload .wrap h3 {
	width: 100%;
	text-align: center;

	margin-bottom: 0;
}
.launcherdownload .wrap h4 {
	width: 100%;
	text-align: center;

	font-size: 14px;
	margin-top: 4px;
}
.launcherdownload .wrap .launcher {
	position: relative;

	height: 70%;
	width: 380px;

	margin: 0 auto;
}
.launcherdownload .wrap .launcher .launcher-bg {
	position: absolute;

	top: 0;
	left: 50%;

	transform: translateX(-50%);
}
.launcherdownload .wrap .launcher .launcher-girl {
	position: absolute;

	bottom: -150px;
	right: -280px;

	z-index: 2;
}
.launcherdownload .wrap .launcher .launcher-text {
	position: absolute;

	top: 065px;
	left: 50%;

	transform: translateX(-50%);

	width: 700px;
	height: auto;
}
.launcherdownload .wrap .launcher .button
{
	position: absolute;

	bottom: -50px;
	left: -175px;

	z-index: 5;

	width: 100%;
	padding: 25px 0;

	display: flex;
	justify-content: center;
	align-items: center;

	box-shadow: 0px 0px 19px #FEA313;
	margin-top: 60px;
}
.launcherdownload .wrap .launcher .button span
{
	margin-left: 25px;
}



@media screen and (max-width: 520px)
{
	.servers .wrap .flex
	{
		width: 95%;
	}
}
@media screen and (max-width: 440px)
{
	.servers .wrap .flex .srv-info
	{
		margin: 5px 0;
	}
	.servers .wrap .flex .srv-info .other h4
	{
		font-size: 20px;
	}
	.servers .wrap .flex .srv-info .other .online-text span span
	{
		font-size: 18px;
	}
}



@media screen and (max-width: 1220px)
{
	.info .start
	{
		width: 100%;
		flex-wrap: wrap;

		background-color: transparent;
	}
	.info .start .left
	{
		width: calc(100% - 270px - 20px);
		z-index: 11;
	}
	.info .start .left span
	{
		font-size: 30px;
		white-space: nowrap;
	}
	.info .start .left .bg
	{
		height: calc(525px - 75px);
		width: calc(426px - 75px);

		bottom: -114px;
		left: -95px;
	}

	.info .start .right
	{
		width: calc(100% - 200px);
		background-color: rgba(255, 255, 255, .5);

		margin-top: 20px;
		padding: 35px 100px;
	}
	.info .start .right .text
	{
		height: auto;
	}
	.info .start .right .bottom
	{
		position: static;
		width: 100%;

		margin-top: 35px;
	}

	.info .shop
	{
		position: absolute;

		top: 0;
		right: 0;

		height: calc(350px - 30px);
	}

	.info .start .right .bg-patron-start-rightdown
	{
		bottom: -103px;
		right: -155px;
	}
	.info .start .right .bg-patron-start-leftup
	{
		top: -480px;
		left: -80px
	}
}
@media screen and (max-width: 1000px)
{
	.info .shop
	{
		width: calc(200px - 30px);

		padding: 0 15px;
		padding-top: 30px;
	}
	.info .shop a
	{
		font-size: 13px;
		width: calc(100% - 30px);
	}

	.info .start .left
	{
		width: calc(100% - 200px - 20px);
	}

	.launcherdownload .wrap .launcher .launcher-girl {
		right: -165px;
	}
	.launcherdownload .wrap .launcher .launcher-text {
		width: 600px;
	}
	.launcherdownload .wrap .launcher .button {
		width: 75%;
		left: -120px;
	}
}

@media screen and (max-width: 650px)
{
	.info .shop
	{
		display: none;
	}

	.info .start .left
	{
		width: 100%;
	}
	.info .start .right
	{
		width: calc(100% - 80px);
		background-color: rgba(255, 255, 255, .5);

		margin-top: 20px;
		padding: 35px 40px;
	}

	.launcherdownload .wrap .launcher .launcher-girl {
		width: 200px;
		height: auto;

		right: -55px;
	}
	.launcherdownload .wrap .launcher .launcher-text {
		width: 500px;
	}
	.launcherdownload .wrap .launcher .button {
		width: 55%;
		left: -45px;
	}
}

@media screen and (max-width: 510px)
{
	.info .start .left .bg
	{
		height: calc(525px - 165px);
		width: calc(426px - 165px);

		bottom: -94px;
		left: -110px;
	}
	.info .start .left
	{
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.info .start .left span
	{
		position: static;
	}
}
@media screen and (max-width: 315px)
{
	.info .start .right
	{
		width: calc(100% - 30px);
		padding: 35px 15px;
	}
}
```
</details>

<details>
<summary>Пример кода PUG</summary>
    
```pug
doctype html
html
	head
		meta(charset='utf-8')

		script(type='text/javascript', src='/js/modules/jquery-3.5.1.min.js')

		link(rel='stylesheet', href='/styles/main.css')
		link(rel='stylesheet', href='/styles/header.css')

		link(rel='stylesheet', href='/styles/pages/main.css')

		link(rel='stylesheet', href='/styles/color-themes.css')

		script(type='module', src='/js/main.js')
		script(type='module', src='/js/pages/main.js')

		title Enki Online - Играй в GTA San Andreas по сети по новому
		link(rel='icon', href='/images/favicon.ico', sizes='48x48', type='image/x-icon')

		link(rel="stylesheet", href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css")
		meta(name="viewport", content="width=device-width, initial-scale=1.0")

		meta(name="enot", content="2421661581395VXyLcfGDDgZScbLupFPModrJ40qnAhNn")

		//- script(type='text/javascript', src='https://samp-rating.ru/web/api/13681/')

	body
		script(type='text/javascript', src='/js/modules/loading.js')
		.bg-color

		.color
		.color-menu
			.wrap
				.color-menu-title
					h1 Кастомизация цвета
					span Выберите интересующий вас стиль, для его дальнейшего отображение на сайте!

				.items
					.item(style="background-color: #FFFFFF; color: black;", data-color="FFFFFF") Белый
					.item(style="background-color: #333b62;", data-color="333b62") Синий
					.item(style="background-color: #691717;", data-color="691717") Красный
					.item(style="background-color: #0F0F0F;", data-color="0F0F0F") Черный
					.item(style="background-color: #562762;", data-color="562762") Фиолетовый
					.item(style="background-color: #2D4E18;", data-color="2D4E18") Зеленый
					.item(data-color="all") Многоцветный

		.burger-menu
			.burger-menu-body
				.logo
				menu
					a(href="/").burger-menu-select Главная
					//a(href="http://lk.enki-rp.ru/roulette") Рулетка
					a(href="/news") Новости
					a(href="http://forum.enki-rp.ru", target="_blank") Форум
					a(href="/donate") Магазин
					a.burger-menu-exit Закрыть

				a.button(href="http://lk.enki-rp.ru", target="_blank").lk-btn.lk-btn-burger
					svg(width='30', height='30', viewbox='0 0 30 30', fill='none', xmlns='http://www.w3.org/2000/svg', xmlns:xlink='http://www.w3.org/1999/xlink')
						mask#mask-lk-svg-burger(mask-type='alpha', maskunits='userSpaceOnUse', x='0', y='0', width='30', height='30')
							rect(width='30', height='30', fill='url(#patter-lk-svg-burger)')
						g(mask='url(#mask-lk-svg-burger)')
							rect(width='30', height='30', fill='white' style="transition: .2s;")
						defs
							pattern#patter-lk-svg-burger(patterncontentunits='objectBoundingBox', width='1', height='1')
								use(xlink:href='#image-lk-svg-burger', transform='scale(0.00195312)')
							image#image-lk-svg-burger(width='512', height='512', xlink:href='data:image/png;base64,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')


					span Личный кабинет

		.wrapper
			.bg-patron.bg-patron-leftup
			.bg-patron.bg-patron-rightdown

			.body
				header.header
					a(href="/").logo

					.burger-btn
						span

					menu
						a(href="/").header-menu-select Главная
						//a(href="http://lk.enki-rp.ru/roulette") Рулетка
						a(href="/news") Новости
						a(href="http://forum.enki-rp.ru", target="_blank") Форум
						a(href="/donate") Магазин
					a.button(href="http://lk.enki-rp.ru", target="_blank").lk-btn.lk-btn-header
						svg(width='30', height='30', viewbox='0 0 30 30', fill='none', xmlns='http://www.w3.org/2000/svg', xmlns:xlink='http://www.w3.org/1999/xlink')
							mask#mask-lk-svg(mask-type='alpha', maskunits='userSpaceOnUse', x='0', y='0', width='30', height='30')
								rect(width='30', height='30', fill='url(#patter-lk-svg)')
							g(mask='url(#mask-lk-svg)')
								rect(width='30', height='30', fill='white' style="transition: .2s;")
							defs
								pattern#patter-lk-svg(patterncontentunits='objectBoundingBox', width='1', height='1')
									use(xlink:href='#image-lk-svg', transform='scale(0.00195312)')
								image#image-lk-svg(width='512', height='512', xlink:href='data:image/png;base64,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')


						span Личный кабинет

				.info
					.title Информация
					.flex(style="justify-content: space-between; margin-top: 50px;")
						.start
							.left
								.bg
								span Просто динамично
							.right
								.text
									.text-body
										.text-wrap.text-wrap-show(data-info-text-id="0")
											h2 Начни свою игру на лучшем проекте
											span Enki RolePlay - открывает свои двери для игроков с большими планами!
										.text-wrap(data-info-text-id="50")
											h2 Уникальные работы
											span На проекте разработаны уникальные системы работ, где вы окунетесь с головой в создание автомобилей, одежды и многого другого.
										.text-wrap(data-info-text-id="100")
											h2 Уникальные фракции
											span Хотели бы стать диктатором? Создать полицейское государство? Именно это, да и не только, вы сможете найти на нашем проекте.

								.bg-patron.bg-patron-start-leftup
								.bg-patron.bg-patron-start-rightdown

								.bottom
									a(href="#launcherdownload").button.button-anim Начать игру
									.sliders
										button.sliders-select(data-info-text-id="0")
										button(data-info-text-id="50")
										button(data-info-text-id="100")

						.shop
							h2 Магазин
							a(href="/donate").button.button-anim Перейти к покупкам

				.last-news
					.title Последние новости
					.flex
						.news-error Загрузка новостей...

				//- .scrolling

		.servers
			//- .bg-color
			.wrap
				h3 Список серверов

				.flex

		.servers.launcherdownload#launcherdownload(style="margin-top: 75px")
			//- .bg-color
			.wrap(style="clip-path: polygon(50% 0%, 100% 13%, 100% 38%, 100% 70%, 100% 87%, 50% 100%, 0 87%, 0% 70%, 0% 35%, 0 13%);")
				h3 Установите лаунчер <br />и начните играть прямо сейчас
				h4 Если Вы столкнулись с проблемами при установке лаунчера <br /> или в самой игре через него - <a target="blank" href="https://forum.enki-rp.ru/threads/45/" style="color: #FFC121;">просмотрите данную тему</a>
				.launcher
					img(src="/images/launcherbg.png").launcher-bg
					img(src="/images/launchergirl.png").launcher-girl
					img(src="/images/launchertext.png").launcher-text
					a.button(href="/launcher")
						svg(width='18', height='27', viewbox='0 0 18 27', fill='none', xmlns='http://www.w3.org/2000/svg')
							path(d='M0 26H18', stroke='white', stroke-width='2')
							path(d='M9 0V18M9 18L17 10M9 18L1 10', stroke='white', stroke-width='2')
						span Играть

		.footer
			//- .bg-color

			.wrap
				h2 Наши социальные сети

				a(href="https://vk.com/enkiplay", target="_blank")
						img(src="/images/social/vk.png", alt="ВКонтакте: SAMP Enki Online")
				a(href="/discord", target="_blank")
					img(src="/images/social/discord.png", alt="Discord: SAMP Enki Online")
				a(href="https://www.youtube.com/channel/UCt0cgAO4aZCInlug1GeDQKA", target="_blank")
					img(src="/images/social/youtube.png", alt="Youtube: SAMP Enki Online")
```
</details>

<details>
<summary>Пример пода JS</summary>
    
```javascript
let
	swipingInterval,
	swipingTime = false

const servers = [
	{ hostname: 'Enki Online | Royal', status: 2, ip: '88.208.241.199', port: '7777', maxplayers: 1000, players: 0 }
]

function swipingInfoText(id = null)
{
	if(swipingTime == true)return false

	let targetID = $('.info .text .text-wrap-show').attr('data-info-text-id')
	if(targetID == undefined)
	{
		clearInterval(swipingInterval)
		return false
	}

	if(id != null && id === targetID)return false
	swipingTime = true

	$('.info .text .text-wrap-show').removeClass('text-wrap-show')
	$(`.info .right .bottom .sliders button.sliders-select`).removeClass('sliders-select')

	if(id == null
		&& id >= 0
		&& id < 2)
	{
		if(targetID == 0) targetID = 50
		else if(targetID == 50) targetID = 100
		else if(targetID == 100) targetID = 0

		$(`.info .text .text-body`).css({ 'right': `calc(${targetID}% + ${targetID}%)` })
		$(`.info .text .text-wrap[data-info-text-id="${targetID}"]`).addClass('text-wrap-show')

		$(`.info .text .text-wrap[data-info-text-id="${targetID}"]`).addClass('text-wrap-show')
		$(`.info .right .bottom .sliders button[data-info-text-id="${targetID}"]`).addClass('sliders-select')
	}
	else
	{
		$(`.info .text .text-body`).css({ "right": `calc(${id}% + ${id}%)` })

		$(`.info .text .text-wrap[data-info-text-id="${id}"]`).addClass('text-wrap-show')
		$(`.info .right .bottom .sliders button[data-info-text-id="${id}"]`).addClass('sliders-select')

		clearInterval(swipingInterval)
		swipingInterval = setInterval(swipingInfoText, 7400)
	}

	setTimeout(() => swipingTime = false, 1200)
}

const elementsScroll =
{
	servers: false,
	footer: false
}
$(window).scrollTop(0)

$(document).ready(() =>
{
	swipingInterval = setInterval(swipingInfoText, 7400)
	$(`.info .right .bottom .sliders button`).on('click', elem =>
	{
		const id = $(elem.target).attr('data-info-text-id')
		if(!id)return false

		swipingInfoText(id)
	})

	$.post('/get_servers', {}, results => {
		let serverIPCopied
		JSON.parse(results).forEach((item, i) =>
		{
			let onlineCount = null
			if(item.status !== 0)
			{
				onlineCount = 100 / (item.maxplayers / item.players)
				onlineCount = (126 / 100) * onlineCount
			}

			$(`.servers .wrap .flex`).append(`
				<${item.status === 1 ? "a" : "div"} class="srv-info" id="ip-${i}">
					${item.status !== 0 ? `<input type="text" value="${item.ip}:${item.port}" style="position: absolute; top: -1000; left: -1000; opacity: 0;"/>` : ""}
					<div class="online-draw">
						<div class="online-draw-wrap">
							<div class="online-draw-count">
								${item.status !== 0 ? `<svg id="spinner" viewBox="0 0 50 50">
										<circle id="path" cx="25" cy="25" r="20" fill="none" stroke-width="6" style="stroke-dashoffset: ${-126 + onlineCount};"></circle>
									</svg>` : ""}
							</div>
						</div><span class="online-draw-text">enki</span>
					</div>
					<div class="other">
						<h4>${item.hostname}</h4>
						<div class="online-text">
						${item.status === 0 ? '<div style="background-color: red;"></div><span>Offline</span>' : item.status === 2 ? `<div style="background-color: #ffb64c;"></div><span>${item.date || 'Скоро'}</span>` : `<div></div><span>Online: <span>${item.players} / ${item.maxplayers}</span></span>`}
						</div>
					</div>
					${item.status === 1 || (item.status === 2 && item.date) ? '<section>Подключиться?</section>' : ""}
				</${item.status === 1 ? "a" : "div"}>`)

			if(item.status !== 0)
			{
				$(`#ip-${i}`).on('click', elem =>
				{
					$(elem.currentTarget).find('input').select()
					document.execCommand("copy")

					switch(serverIPCopied)
					{
						case 0:
							$(elem.currentTarget).find('section').text('Скопировано!')
							break
						case 1:
							$(elem.currentTarget).find('section').text('Скопировано! x2')
							break
						case 2:
							$(elem.currentTarget).find('section').text('Скопировано! x3')
							break
						case 3:
							$(elem.currentTarget).find('section').text('Тебе мало?')
							break
						case 4:
							$(elem.currentTarget).find('section').text('Ладно, держи еще раз')
							break
						case 5:
							$(elem.currentTarget).find('section').text('Да ты псих!')
							break
						case 6:
							$(elem.currentTarget).find('section').text('Ну иди играй уже!')
							break
						case 7:
							$(elem.currentTarget).find('section').text('Окей, я вызываю санитаров')
							break
						case 8:
							$(elem.currentTarget).find('section').text('ХВАТИТ!!!')
							break
						case 9:
							$(elem.currentTarget).find('section').text('АААААААААААААААААААААА!!!!!!!11111!!!!11111')
							break
						case 10:
							$(elem.currentTarget).find('section').text('Парни, в 8 майонезную палату его')
							break
					}

					serverIPCopied ++
					if(serverIPCopied > 10) serverIPCopied = 0
				})
				$(`#ip-${i}`).hover(elem =>
				{
					serverIPCopied = 0
					$(elem.currentTarget).find('section').text('Подключиться?')
				})
			}
		})
	})

	$.post('/get_last_news', {}, results =>
	{
		loading.stop()

		if(results === 'notfound') $('.last-news .flex').html('<div class="news-error">Новостей на найдено!</div>')
		else
		{
			results = JSON.parse(results)

			$('.last-news .flex').html(`
				<div class="news"></div>
				<a class="arrow" href="/news">
					<span></span>
					<span></span>
				</a>`)
			results.forEach(item =>
			{
				$('.last-news .flex .news').append(`
					<a href="/news?id=${item.id}">
						<div class="bg-notfound"></div>
						<div class="bg" style="background-image: url(${item.attachments[0].photo ? item.attachments[0].photo.sizes[4].url : ""});"></div>

					    <div class="news-anim">
					        <div class="news-anim-wrap">
					        	<img src="/images/news/look_anim.png" alt="Анимация" />
					        	<span>Смотреть</span>
					        </div>
					    </div>
					</a>`)
			})
		}
	})
})
```
</details>