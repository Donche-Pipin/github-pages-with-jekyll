<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<link rel="stylesheet" type="text/css" href="style.css">
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js"></script>
		<script src="script.js"></script>
		<link rel="stylesheet" type="text/css" href="./slick/slick.css"/>
		<link rel="stylesheet" type="text/css" href="./slick/slick-theme.css"/>	
		<script type="text/javascript" src="./slick/slick.min.js"></script>			
		<title>Главная страница</title>
	</head>
	<body>
		<header class="header">
			<div class="header-content">
				<div class="logo header-content__logo">
					<a class="logo__link" href="./index.html">
						<img class="logo__img" src="./images/logo1.png" alt="Логотип">
					</a>
				</div>
				<div class="phone header-content__phone">
					<p><a  class="phone__number" href="tel:+78005553535">+7 (800) 555-35-35</a><p>
				</div>
				<div class="hamburger">
		          <span class="line"></span>
		          <span class="line"></span>
		          <span class="line"></span>
		        </div>
			</div>
			<nav class="menu menu_theme_primary">
				<ul class="menu__list">
					<li class="menu__item">
						<a href="construction.html" class="menu__link menu__link_color_dark"><span class="list-border">Строительство и монтаж</span></a>
					</li>
					<li class="menu__item">
						<a href="control.html" class="menu__link menu__link_color_dark"><span class="list-border">Контроль</span></a>
					</li>
					<li class="menu__item">
						<a href="energy.html" class="menu__link menu__link_color_dark"><span class="list-border">Энергосервис</span></a>
					</li>
					<li class="menu__item">
						<a href="#" class="menu__link menu__link_color_dark"><span class="list-border">О нас</span></a>
					</li>
					<li class="menu__item">
						<a href="#" class="menu__link menu__link_color_dark"><span class="list-border">Контакты</span></a>
					</li>	
				</ul>
			</nav>
		</header>
		<main class="main-content">
			<div class="welcome-block welcome-block_background_primary">
				<div class="welcome-block-container welcome-block-container_theme_dark">
					<h1 class="welcome-block-container__title welcome-block-container__title_size_s">Реализуем проекты любой сложности</h1>
					<p class="welcome-block-container__text welcome-block-container__text_size_s">в области промышленного строительства, развития инженерной и дорожно-транспортной инфраструктуры</p>
					<div class="button button_size_s button_theme_red">
						<a class="button-link button-link_color_light" href="#">Оставить заявку</a>
					</div>
				</div>
			</div>
			<div class="activities">
				<div class="activities-container">
					<div class="activities-item activities-item_theme_blue">
						<div class="activities-wrapper-img">
							<img src="./images/work2.svg" class="activities-item__img" alt="">
						</div>
						<div class="activities-wrapper-title">
							<p class="activities-item__title">Строительно-монтажные работы</p>
						</div>
					</div>
					<div class="activities-item activities-item_theme_red">
						<div class="activities-wrapper-img">
							<img src="./images/work1.svg" class="activities-item__img" alt="">
						</div>
						<div class="activities-wrapper-title">
							<p class="activities-item__title activities-item__title_text_center">Лаборатория неразрушающего контроля</p>
						</div>
					</div>
					<div class="activities-item activities-item_theme_beige">
						<div class="activities-wrapper-img">
							<img src="./images/work3.svg" class="activities-item__img" alt="">
						</div>
						<div class="activities-wrapper-title">
							<p class="activities-item__title activities-item__title_text_centerBlue">Реализация энергосервисных контрактов</p>
						</div>
					</div>
				</div>
			</div>
			<div class="mission">
				<div class="mission-container">
					<div class="mission-values">
						<h1 class="mission-values__title">Ценности и миссия</h1>
						<h3 class="mission-values__title-sub">Как мы работаем</h3>
					</div>
					<div class="values-container">
						<ul class="values">
							<li class="values__item">- Реализация высококачественных и долговечных проектов в&nbsp;сфере промышленного строительства</li>
							<li class="values__item">- Внесение весомого вклада в развитие инженерной и&nbsp;дорожно-транспортной инфраструктуры по всей территории&nbsp;РФ</li>
							<li class="values__item">- Высокие стандарты нашей работы обеспечены многолетним&nbsp;опытом, бережной кадровой политикой, инновационным подходом к уровню технических работ и&nbsp;квалификационным требованиям</li>
						</ul>
						<div class="button button_size_s button_theme_red">
							<a class="button-link button-link_color_light" href="#">Оставить заявку</a>
						</div>
					</div>
					<div class="point-image">
						<img src="./images/img1.png">
					</div>
				</div>
			</div>
			<div class="experience">
				<div class="experience-container">
					<div class="experience-container__first-block"></div>
					<div class="experience-container-second-block">
						<h1 class="experience-container-second-block__title">Почему<br>выбирают нас?</h1>
					</div>
					<div class="experience-container-block-experience">
						<img class="experience-icon experience-page" src="./images/fl1.png" alt="иконка">
						<h3 class="experience-title experience-left experience-top">Опыт</h3>
						<p class="experience-text experience-left" id="second_line_first_block">15 лет успешной работы, множество благодарных заказчиков. Репутация работает на нас!</p>
					</div>
					<div class="experience-container-block-professionalism">
						<img class="experience-icon experience-page" src="./images/fl2.png" alt="иконка">
						<h3 class="experience-title experience-left experience-top">Профессионализм</h3>
						<p class="experience-text experience-left">Наши сотрудники – <br>профессионалы высокой квалификации в своей области.</p>
					</div>
					<div class="experience-container-block-approach">
						<img class="experience-icon experience-page" src="./images/fl3.png" alt="иконка">
						<h3 class="experience-title experience-left experience-top">Подход</h3>
						<p class="experience-text experience-left">Только индивидуальный подход <br>к каждому заказчику <br>и каждому объекту.</p>
					</div>
					<div class="experience-container-block-quality">
						<img class="experience-icon experience-page" src="./images/sl1.png" alt="иконка">
						<h3 class="experience-title experience-left experience-top">Качество</h3>
						<p class="experience-text experience-left" id="second_line_first_block">Выполняем работы любой <br>сложности с неизменно превосходным результатом.</p>
					</div>
					<div class="experience-container-block-control">
						<img class="experience-icon experience-page" src="./images/sl2.png" alt="иконка">
						<h3 class="experience-title experience-left experience-top">Контроль</h3>
						<p class="experience-text experience-left">Обеспечиваем постоянный контроль качества работ и материалов на всех этапах ведения проекта.</p>
					</div>
					<div class="experience-container-block-development">
						<img class="experience-icon experience-page" src="./images/sl3.png" alt="иконка">
						<h3 class="experience-title experience-left experience-top">Развитие</h3>
						<p class="experience-text experience-left">Постоянно совершенствуемся, <br>как в области технологий, <br>так и в квалификации сотрудников.</p>
					</div>
					<div class="experience-container__last-block"></div>
				</div>
			</div>
			<div class="form-block form-block_theme_red">
				<div class="form-block-container">
					<div class="form-block-left">
						<div class="form-block-left-container form-block-left-margin">
							<h2 class="form-block-left-container__title">Получить коммерческое предложение</h2>
							<form class="form" name="request" metod="post" action="#">
								<h6 class="form__field-title">E-mail</h6>
								<input class="form__input" type="email" name="email">
								<h6 class="form__field-title">Номер телефона</h6>
								<input class="form__input" type="number" name="phone">
								<h6 class="form__field-title">Комментарий</h6>
								<textarea class="form__comment" name="comment" value="#"></textarea>
								<input class="button button_size_m button_theme_blue" type="submit" value="Оставить заявку">
							</form>
						</div>
					</div>
					<div class="form-block-right activities-page">
						<img class="form-block-right__img" src="./images/img2.png">								
					</div>
				</div>
			</div>
			<div class="map-block">
				<div class="map-block-item">
					<div class="map"><script type="text/javascript" charset="utf-8" async src="https://api-maps.yandex.ru/services/constructor/1.0/js/?um=constructor%3A0e37ad1a2cbeb37cb5221ec3c9e1a2419632bb82407667a76fa923242d5154df&amp;width=100%&amp;height=490&amp;lang=ru_RU&amp;scroll=false"></script></div>
					<div class="contact-block">
						<h2 class="contact-block__title">Контакты</h2>
						<p class="contact-block__text">Санкт-Петербург, ул. Пушкина, 42 <a class="phone__number" href="tel:+78005553535">8-800-555-35-35</a> <a class="email" href="mailto:info@esmp.ru">info@espm.ru</a></p>
					</div>
				</div>
			</div>
		</main>
		<footer class="footer">
			<div class="footer-container">
				<div class="rights-icon">
					<p>© 2019 ESPM</p>
				</div>
				 <div class="footer-menu">
					<ul class="footer-menu-list">
						<li class="footer-menu-list__item"><a href="construction.html" class="footer-menu-list__link">Строительство и монтаж</a></li>
						<li class="footer-menu-list__item"><a href="control.html" class="footer-menu-list__link">Контроль</a></li>
						<li class="footer-menu-list__item"><a href="energy.html" class="footer-menu-list__link">Энергосервис</a></li>
						<li class="footer-menu-list__item"><a href="#" class="footer-menu-list__link">О нас</a></li>
						<li class="footer-menu-list__item"><a href="#" class="footer-menu-list__link">Контакты</a></li>	
					</ul>
				</div>
				<div class="button-up">
					<p>Наверх↑</p>
				</div>
			</div>
		</footer>
	</body>
</html>
