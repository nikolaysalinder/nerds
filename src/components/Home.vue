<template>
  <div class="home">
    <header class="main-header">
      <div class="container">
       <a href="#" class="top-logo">
         <img src="./../assets/img/nerds-logo.png" height="57" width="139" alt="#">
       </a>
       <nav class="main-nav">
        <ul>
          <li><a href="#">Студия</a></li>
          <li><a href="#">Клиенты</a></li>
          <li><a href="#">Магазин</a></li>
          <li><a href="#">Контакты</a></li>
          <li><a href="#">Корзина</a></li>
        </ul>
      </nav>
    </div>
  </header>
  <main>
    <div class="slider">
      <div class="container">
        <div class="slider-column-left">
          <b>
            Долго, дорого,<br>
            скрупулезно.
          </b>
          <p>Математически выверенный дизайн для вашего сайта или мобильного приложения</p>
          <a href="#">Узнать больше</a>
        </div>
        <div class="slider-column-right">
          <img
          width="500"
          class="slider-img"
          :src="srcSlider"
          alt="#">
        </div>
      </div>
    </div>
    <div class="service">
      <div class="container">
        <div class="service-item">
          <div class="service-img-wrapper">
             <img
            :src="srcImg1"
            width="240"
            height="123"
            alt="">
          </div>
          <h2 class="service-item-title">Веб-сайты</h2>
          <p class="service-item-description">
            Мир никогда не будет прежним после того как увидит ваш сайт!
          </p>
          <a href="#" class="service-item-order red">Заказать</a>
        </div>
        <div class="service-item">
          <div class="service-img-wrapper">
            <img
            :src="srcImg2"
            width="240"
            height="123"
            alt="">
          </div>
          <h2 class="service-item-title">Приложения</h2>
          <p class="service-item-description">
          Покорите топ-10 приложений в AppStore и Google Play</p>
          <a href="#" class="service-item-order green">Заказать</a>
        </div>
        <div class="service-item">
          <div class="service-img-wrapper">
            <img
            :src="srcImg3"
            width="240"
            height="123"
            alt="">
          </div>
          <h2 class="service-item-title">Презентации</h2>
          <p class="service-item-description">Вы даже не подозреваете, насколько вы изумительны!</p>
          <a href="#" class="service-item-order yellow">Заказать</a>
        </div>
      </div>
    </div>
    <div class="features">
      <div class="container">
        <div class="features-column-left">
          <b>
            Мы — маленькая, но гордая<br>
            дизайн-студия из Краснодара.
          </b>
          <p>Исповедуем принципы минимализма и чистоты. Ставим математический расчет
          превыше креатива. Работаем не покладая рук, как роботы.</p>
          <h3>Выполняем заказы на разработку:</h3>
          <ul>
            <li>Веб-сайтов любой сложности</li>
            <li>Мобильные приложения для iOS и Android</li>
            <li>Слайдшоу и видео для корпоративных презентаций</li>
          </ul>
        </div>
        <div class="features-column-right">
          <img
          :src="srcImg4"
          width="330"
          alt="#" class="features-img">
          <h3>С 2004 года любим точность во всем:</h3>
          <ul>
            <li>
              <span>146%</span>
              <p>
                Уровень<br>
                самоотдачи
              </p>
            </li>
            <li>
              <span>100%</span>
              <p>
                Соблюдение<br>
                сроков
              </p>
            </li>
            <li>
              <span>50%</span>
              <p>
                Минимальная<br>
                предоплата
              </p>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="clients">
      <div class="container">
        <div class="clients-item">
          <img :src="srcImg5" alt="#">
        </div>
        <div class="clients-item">
          <img :src="srcImg6" alt="#">
        </div>
        <div class="clients-item">
          <img :src="srcImg7" alt="#">
        </div>
        <div class="clients-item">
          <img :src="srcImg8" alt="#">
        </div>
      </div>
    </div>
    <div id="map">
      <img :src="srcImg10" id="map-img">
      <div class="container">
        <div class="contacts">
          <img
          :src="srcImg9" alt="Nerds Design Studio">
          <p class="adress">
            191186, Санкт-Петербург,<br>
            ул. Б. Конюшенная, д. 19/8
          </p>
          <a
          href="#"
          class="phone">
          тел. +7 (812) 2757575
        </a>
        <a class="feedback" href="#">Напишите нам</a>
      </div>
      <div class="baloon">
      </div>
    </div>
  </div>
</main>
<footer class="main-footer">
  <div class="container">
    <div class="footer-socials">
      <ul>
        <li><a class="vk" href="#">vkontakte.ru</a></li>
        <li><a class="fb" href="#">facebook.com</a></li>
        <li><a class="in" href="#">instagramm.com</a></li>
      </ul>
    </div>
    <div class="footer-title">
      <b class="profit">Давайте дружить, это выгодно!</b>
      <p>Скидка 10% для друзей из социальных сетей.</p>
    </div>
  </div>
</footer>
</div>
</template>

<script>
export default {
  name: 'Home',
  data() {
    return {
      srcSlider: './static/img/slide1.png',
      srcImg1: './static/img/illustration-1-jpg.jpg',
      srcImg2: './static/img/illustration-2-jpg.jpg',
      srcImg3: './static/img/illustration-3-jpg.jpg',
      srcImg4: './static/img/nerds-illustration-jpg.jpg',
      srcImg5: './static/img/logo-1-png.png',
      srcImg6: './static/img/logo-2-png.png',
      srcImg7: './static/img/logo-3-png.png',
      srcImg8: './static/img/logo-4-png.png',
      srcImg9: './static/img/n-rds-design-studio.png',
      srcImg10: './static/img/map.jpg',
    };
  },
};
</script>

<style>
/*стили для разработки*/
a, div, li, nav, ul, header,
footer, .container, figure, form,
label, h1, h2 {
  outline: 1px solid green;
}
/*стили для разработки*/
body{
  min-width: 900px;
  margin: 0;
  padding: 0;
  background-color: white;
  color: black;
  font-family: Roboto, Arial, sans-serif;
  font-weight: 500;
  font-size: 16px;
  line-height: 22px
}
.container {
  display: flex;
  width: 880px;
  padding: 0 10px;
  margin: 0 auto;
}
.main-header{
  display: flex;
  background: #eeeeee;
}
.top-logo {
  display: block;
  padding-top: 25px;
}
.main-nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
  display: flex;
  margin-left: 160px;
  margin-top: 50px;
}
.main-nav li:last-child {
  margin-left: 47px;
}
.main-nav li:last-child a{
  padding-right: 0;
  padding-left: 25px;
  background: url('./../assets/img/icon-cart.png');
  background-repeat: no-repeat;
  background-position: -1px 0;
}
.main-nav a {
  font-size: 14px;
  line-height: 30px;
  text-decoration: none;
  text-transform: uppercase;
  color: black;
  padding-left: 22px;
  padding-right: 23px;
}
.slider {
  height: 350px;
  background: #eee;
}
.slider-column-left{
  width: 380px;
  font-size: 30px;
  padding-top: 68px;
}
.slider-column-left b {
  font-size: 36px;
  line-height: 36px;
}
.slider-column-left p {
  font-size: 16px;
  margin-top: 19px;
}
.slider-column-left a {
  display: block;
  font-size: 16px;
  margin-top: 30px;
  text-transform: uppercase;
  text-decoration: none;
  font-size: 12px;
  padding-top: 7px;
  padding-left: 68px;
  padding-right: 70px;
  padding-bottom: 7px;
  color: #fff;
  background: #fb565a;
  width: 100px;
  border-radius: 4px;
  transition: background .5s;
}
.slider-column-left a:hover {
  background: #d6494d;
}
.slider-column-right {
  width: 500px;
  height: 350px;
}
.service {
  height: 430px;
}
.service .container {
  justify-content: space-between;
}
.service-item {
  padding: 0;
  width: 240px;
  margin-top: 50px;
}
.service-img-wrapper {
  width: 143px;
  height: 123px;
}
.service-item-title {
  text-transform: uppercase;
  font-size: 18px;
  margin-top: 20px;
}
.service-item-description {
  margin-top: 19px;
  font-size: 15px;
}
.service-item-order {
  display: block;
  background: red;
  text-transform: uppercase;
  color: #fff;
  text-decoration: none;
  font-size: 12px;
  padding-left: 39px;
  padding-top: 10px;
  padding-bottom: 9px;
  width: 61px;
  padding-right: 39px;
  margin-top: 24px;
  border-radius: 4px;
}
.red {
  background: #fb565a;
  transition: background .5s;
}
.red:hover {
  background: #d6494d;
}
.green {
  background: #00ca74;
  transition: background .5s;
}
.green:hover {
  background: #01a25e;
}
.yellow {
  background: #efc84a;
  transition: background .5s;
}
.yellow:hover {
  background: #d6ae2c;
}
.features .container {
  flex-wrap: wrap;
}
.features {
  height: 475px;
}
.features-column-left {
  width: 570px;
}
.features-column-left b {
  display: block;
  margin-top: 70px;
  line-height: 36px;
  font-size: 36px;
}
.features-column-left h3 {
  display: block;
  margin-top: 46px;
  margin-left: -2px;
  text-transform: uppercase;
  font-size: 16px;
}
.features-column-left ul {
  list-style: none;
  padding-left: 36px;
  margin-top: 22px;
}
.features-column-left li {
  margin-bottom: 23px;
  position: relative;
}
.features-column-left li::before {
  content: '';
  position: absolute;
  left: -38px;
  top: 9px;
  background: red;
  width: 27px;
  height: 2px;
}
.features-column-right {
  width: 310px;
}
.features-column-right h3 {
  display: block;
  margin-top: 46px;
  margin-left: -2px;
  text-transform: uppercase;
  font-size: 15px;
}
.features-column-right ul {
  margin: 0;
  padding: 0;
  list-style: none;
  display: flex;
  justify-content: space-between;
  margin-top: 28px;
}
.features-column-right span {
  font-size: 44px;
}
.clients {
  display: block;
  margin-top: 50px;
  padding-top: 50px;
  padding-bottom: 85px;
}
.clients .container {
  justify-content: space-between;
}
.clients-item {
  width: 220px;
}
.clients-item img {
  width: 220px;
}
#map{
  height: 415px;
  margin-top: 50px;
  position: relative;
  background-repeat: no-repeat;
}
#map .container {
  height: 415px;
}
#map #map-img {
  position: absolute;
  top: 0;
  left: 0;
  height: 100%;
  width: 100%;
}
#map .contacts {
  display: block;
  position: absolute;
  width: 220px;
  padding-top: 30px;
  padding-bottom: 28px;
  padding-left: 20px;
  top: 90px;
  left: 280px;
  background: #fff;
}
.contacts .adress {
  margin-top: 10px;
  font-weight: normal;
}
.contacts .phone {
  text-decoration: none;
  color: #000;
}
.contacts .feedback {
  display: block;
  margin-top: 30px;
  margin-left: 3px;
  text-decoration: none;
  padding-top: 7px;
  padding-left: 49px;
  padding-bottom: 9px;
  font-size: 12px;
  width: 120px;
  padding-right: 26px;
  text-transform: uppercase;
  border-radius: 4px;
  background: #fb565a;
  color: #fff;
  transition: background .5s;
}
.contacts .feedback:hover {
  background: #d6494d;
}
.baloon {
  display: block;
  position: absolute;
  right: 400px;
  top: 120px;
  background: gray;
  width: 160px;
  height: 200px;
  background: url('./../assets/img/map-marker-png.png');
  background-repeat: no-repeat;
}
.footer-socials {
  width: 240px;
}
.footer-socials ul {
  margin: 0;
  padding: 0;
  margin-top: 75px;
  display: flex;
  list-style: none;
  justify-content: space-between;
}
.footer-socials a {
  display: block;
  font-size: 0;
  width: 60px;
  height: 60px;
  border-radius: 50%;
}
.footer-socials a:hover {
  background: #eb4a59;
}
.footer-socials .vk {
  background: #ccc url('./../assets/img/vk-icon.png');
  background-repeat: no-repeat;
  background-position: 50%;
  background-position: 50%;
}
.footer-socials .vk:hover {
  background: #eb4a59 url('./../assets/img/vk-icon.png');
  background-repeat: no-repeat;
  background-position: 50%;
  background-position: 50%;
}
.footer-socials .fb {
  background: #ccc url('./../assets/img/fb-icon.png');
  background-repeat: no-repeat;
  background-position: 50%;
  background-position: 50%;
}
.footer-socials .fb:hover {
  background: #eb4a59 url('./../assets/img/fb-icon.png');
  background-repeat: no-repeat;
  background-position: 50%;
  background-position: 50%;
}
.footer-socials .in {
  background: #ccc url('./../assets/img/insta-icon.png');
  background-repeat: no-repeat;
  background-position: 50%;
  background-position: 50%;
}
.footer-socials .in:hover {
  background: #eb4a59 url('./../assets/img/insta-icon.png');
  background-repeat: no-repeat;
  background-position: 50%;
  background-position: 50%;
}
.footer-title {
  padding-left: 76px;
}
.footer-title .profit {
  margin-top: 75px;
  display: block;
  font-size: 36px;
}
</style>
