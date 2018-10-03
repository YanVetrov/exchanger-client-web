<template>
  <div>
  <header class="header">
    <div class="course">
        <ul>
            <li>
                <div>
                    <p class="course-header"><span>nifty bank</span><span>528.80</span></p>
                    <p class="course-footer green"><span><em></em>0.20%</span>67.37</p>
                </div>
            </li>
            <li>
                <div>
                    <p class="course-header"><span>nifty bank</span><span>528.80</span></p>
                    <p class="course-footer red"><span><em></em>0.20%</span>67.37</p>
                </div>
            </li>
            <li>
                <div>
                    <p class="course-header"><span>nifty bank</span><span>528.80</span></p>
                    <p class="course-footer red"><span><em></em>0.20%</span>67.37</p>
                </div>
            </li>
            <li>
                <div>
                    <p class="course-header"><span>nifty bank</span><span>528.80</span></p>
                    <p class="course-footer red"><span><em></em>0.20%</span>67.37</p>
                </div>
            </li>
            <li>
                <div>
                    <p class="course-header"><span>nifty bank</span><span>528.80</span></p>
                    <p class="course-footer red"><span><em></em>0.20%</span>67.37</p>
                </div>
            </li>
        </ul>
    </div>
    <nav>
        <div class="container">

            <div class="burger">
                <div class="burger-icon">
                </div>
            </div>
            
            <ul class="menu">
                <li><a href="news.html">Новости</a></li>
                <li><a href="reviews.html">Отзывы</a></li>
                <li><a href="partner.html">Партнерам</a></li>
                <li><a href="specification.html">Правила</a></li>
                <li><a href="faq.html">Вопросы-Ответы</a></li>
                <li><a href="contact-page.html">Контакты</a></li>
            </ul>

            <ul class="languages">
                <li><a href="/">rus</a></li>
                <li><a href="/">eng</a></li>
            </ul>
            
        </div>
    </nav>

</header>

<script>
    var btnBurgerBloc = document.querySelector(".burger");
    var btnBurger = document.querySelector(".burger-icon");
    var menuMob = document.querySelector(".menu");

    btnBurgerBloc.addEventListener('click', function () {
        btnBurger.classList.toggle('open-burger');
        menuMob.classList.toggle('menu-open');
    });
</script>

<div class="under-header form-index-top-wr">

    
    <div class="logo-sign">
    
        <div class="container">
    
            <div class="logo">
                <a href="/"><img src="img/logo.png" alt=""></a>
            </div>
    
            <div class="registration">
                <ul>
                    <li><a href="#" class="btn-personal-room">Вход</a></li>
                    <li><a href="#" class="btn btn-blue btn-registration">Регистрация</a></li>
                </ul>
            </div>
    
            <div class="user-bloc">
                <div class="user-bloc-date">
                    <div class="user-bloc-date-photo"><div class="user-bloc-date-photo-item"><img src="../assets/img/user.svg" alt=""></div></div>
                    <div class="user-bloc-date-info">
                        <p>Maria Maria</p>
                        <span>maria@maria.ru</span>
    
                    </div>
                    <em class="caret"></em>
                </div>
    
                <ul class="user-bloc-list">
                    <li><a href="/profile.html"><img src="../assets/img/user.svg" alt="">Профиль</a></li>
                    <li><a href="/zayvki.html"><img src="../assets/img/edit.svg" alt="">Мои заявки на обмен</a></li>
                    <li><a href="/requisites.html"><img src="../assets/img/id-card.svg" alt="">Реквизиты</a></li>
                    <li><a href="/personal-room.html"><img src="../assets/img/hand-shake.svg" alt="">Партнерская программа</a></li>
                    <!--<li><a href="/specification.html"><img src="../assets/img/copy-documents-option.svg" alt="">API</a></li>-->
                </ul>
    
            </div>
    
        </div>
    
    </div>
    

    <div class="form-index">

        <div class="container">

            <h1 class="text-center">Единый обмен валют</h1>
            <p class="text-center">Наш сервис помогает производить любой обмен безопасно и быстро</p>

            
            <form action="" class="form">
            
                <div class="form-wr">
            
                    <div class="form-index-top">
            
                        <div class="form-index-item">
                            <h3>Отдаете</h3>
                            <p>Выберите валюту и сумму, которую хотите обменять</p>
            
                            <div class="form-index-bloc form-select">
            
                                <div class="form-index-bloc-item">
                                    <label>
                                        <select name="" id="">
                                            <option value="qiwi-rub">QIWI RUB</option>
                                            <option value="qiwi-usd">QIWI USD</option>
                                            <option value="yandex-usd">YANDEX RUB</option>
                                            <option value="yandex-usd">YANDEX USD</option>
                                        </select>
            
                                    </label>
            
                                </div>
            
                                <p>Валюта</p>
                            </div>
            
                            <div class="form-index-bloc form-input">
            
                                <div class="form-index-bloc-item">
            
                                    <label><span>RUB</span>
                                        <input type="text" placeholder="1000">
                                    </label>
            
                                </div>
            
                                <p>Минимальная сумма: <span>10000 RUR</span></p>
                            </div>
            
                        </div>
            
                        <div class="form-exchange text-center">
                            <img src="../assets/img/exchange.svg" alt="">
                        </div>
            
                        <div class="form-index-item">
                            <h3>Получаете</h3>
                            <p>Выберите валюту для получения</p>
            
                            <div class="form-index-bloc form-select">
            
                                <div class="form-index-bloc-item">
                                    <label>
                                        <select name="" id="">
                                            <option value="qiwi-rub">QIWI RUB</option>
                                            <option value="qiwi-usd">QIWI USD</option>
                                            <option value="yandex-usd">YANDEX RUB</option>
                                            <option value="yandex-usd">YANDEX USD</option>
                                        </select>
            
                                    </label>
            
                                </div>
            
                                <p>Резерв <span>29.76109311</span> <span>BTC</span></p>
                            </div>
            
                            <div class="form-index-bloc form-input">
            
                                <div class="form-index-bloc-item">
            
                                    <label><span>RUB</span>
                                        <input type="text" placeholder="1000">
                                    </label>
            
                                </div>
            
                                <p>Курс обмена: <span>534591.466 RUR</span> <span> - 1 BTC</span></p>
                            </div>
            
                        </div>
                    </div>
            
                    <div class="form-index-item">
                        <h3>Детали обмена</h3>
                        <p>Внимательно введите ваши данные</p>
                    </div>
            
                    <div class="form-index-bottom">
            
                        <div class="form-index-bloc form-input">
            
                            <div class="form-index-bloc-item">
            
                                <input type="tel" placeholder="+7ХХХХХХХХХХ" id="tel">
            
                            </div>
            
                            <label for="tel"><p>С кошелька</p></label>
                        </div>
            
                        <div class="form-index-bloc form-input">
            
                            <div class="form-index-bloc-item">
            
                                <input type="email" placeholder="Your email" id="mail">
            
                            </div>
            
                            <label for="mail"><p>Введите e-mail</p></label>
                        </div>
            
                        <div class="form-index-bloc form-input">
            
                            <div class="form-index-bloc-item">
            
                                <input type="text" placeholder="Your packet" id="packet">
            
                            </div>
            
                            <label for="packet"><p>Кошелек для получения</p></label>
                        </div>
            
                    </div>
            
                    <div class="text-center form-submit">
                        <button class="btn btn-submit">Обменять сейчас!</button>
                    </div>
            
            
                </div>
            
                <div class="form-ruls">
            
                    <p class="text-center">Нажимая на эту кнопку, я соглашаюсь с <a href="">правилами обмена.</a></p>
            
                </div>
            
            
            </form>

        </div>

    </div>

</div>

<div class="container">


    <div class="services text-center">
        <h2 class="title">Наш сервис помогает производить обмен<br/>
            безопасно и быстро</h2>

        <ul>
            <li>
                <div class="text-center">
                    <span><img src="img/like.svg" alt=""></span>
                    <p><b>Гарантия</b></p>
                    <div class="services-txt">100% гарантия перевода. Надежность
                        нашего сервиса, подтверждают многочисленные отзывы.</div>
                </div>
            </li>
            <li>
                <div class="text-center">
                    <span><img src="img/credit-card.svg" alt=""></span>
                    <p><b>Конфиденциальность</b></p>
                    <div class="services-txt">Мы не храним и не передаем
                        Вашу персональную информацию
                        3-им лицам.</div>
                </div>
            </li>
            <li>
                <div class="text-center">
                    <span><img src="img/telephone.svg" alt=""></span>
                    <p><b>Поддержка</b></p>
                    <div class="services-txt">Вежливая техническая поддержка, круглосуточно готова помочь Вам по
                        любому вопросу.</div>
                </div>
            </li>
        </ul>
    </div>

</div>

    
    <div class="reserves">
        <div class="container">
    
            <h3 class="title">
                Резервы нашего обменника
    
                <a href="" class="btn btn-look">смотреть все</a>
            </h3>
    
            <ul>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-btc.png" alt="">
                        <span>Bitcoin</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>btc</span>
                        <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-etherium.png" alt="">
                        <span>Ethereum</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>eth</span>
                        <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-litecoin.png" alt="">
                        <span>Litecoin</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>ltc</span>
                        <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-dash.png" alt="">
                        <span>Dash</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>dsh</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-dodecoin.png" alt="">
                        <span>Dogecoin</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>xdg</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-zcash.png" alt="">
                        <span>ZCash</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>zec</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-pircoin.png" alt="">
                        <span>Peercoin</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>ppc</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-yandex.png" alt="">
                        <span>Яндекс.Деньги</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>rub</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-qiwi.png" alt="">
                        <span>QIWI RUB</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>rub</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-sberbank.png" alt="">
                        <span>Сбербанк</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>rub</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-tinkoff.png" alt="">
                        <span>Тинькофф</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>rub</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
                <li>
                    <div class="reserves-icon">
                        <img src="../assets/img/reserves-alphabank.png" alt="">
                        <span>Альфа Банк</span>
                    </div>
    
                    <div class="reserves-cost">
                        <b>30</b> <span>rub</span>
                         <p class="order-reserves"><a href="#" class="btn btn-look order-reserves-btn">заказать резерв</a></p>
                    </div>
                </li>
            </ul>
    
        </div>
    </div>

<div class="container dn-mob">
    
    <div class="news-bloc">
    
            <h3 class="title">
                Последние новости
    
                <a href="/news.html" class="btn btn-look">смотреть все</a>
            </h3>
    
            <ul>
                <li>
    
                    <div class="news-bloc-img">
                        <a href="/one-new.html"><img src="img/bg.svg" alt=""></a>
                    </div>
    
                    <div class="news-bloc-info">
    
                        <span>категория</span>
                        <p class="news-bloc-title">Мы запустили обмен Ripple XRP</p>
    
                        <div class="news-bloc-info_item">
                            <div class="news-bloc-info_item-photo-name">
                                <div class="news-bloc-info_item-photo">
                                    <img src="img/user.svg" alt="">
                                </div>
                                <div class="news-bloc-info_item-name">
                                    <p><b>Илья Новиков</b></p>
                                    <span>11 янв. 2018 г.</span>
                                </div>
                            </div>
                            <div class="news-bloc-info_item-data">
    
                                <span><img src="img/visible.svg" alt=""> <span>2354</span></span>
    
                                <!--<a href="" class="news-bloc-flag"><img src="../assets/img/bookmark.svg" alt=""></a>-->
    
                            </div>
                        </div>
    
                    </div>
    
                </li>
                <li>
    
                    <div class="news-bloc-img">
                        <a href="/one-new.html"><img src="img/bg.svg" alt=""></a>
                    </div>
    
                    <div class="news-bloc-info">
    
                        <span>категория</span>
                        <p class="news-bloc-title">Мы запустили обмен Ripple XRP</p>
    
                        <div class="news-bloc-info_item">
                            <div class="news-bloc-info_item-photo-name">
                                <div class="news-bloc-info_item-photo">
                                    <img src="img/user.svg" alt="">
                                </div>
                                <div class="news-bloc-info_item-name">
                                    <p><b>Илья Новиков</b></p>
                                    <span>11 янв. 2018 г.</span>
                                </div>
                            </div>
                            <div class="news-bloc-info_item-data">
    
                                <span><img src="img/visible.svg" alt=""> <span>2354</span></span>
    
                                <!--<a href="" class="news-bloc-flag"><img src="../assets/img/bookmark.svg" alt=""></a>-->
    
                            </div>
                        </div>
    
                    </div>
    
                </li>
                <li>
    
                    <div class="news-bloc-img">
                        <a href="/one-new.html"><img src="img/bg.svg" alt=""></a>
                    </div>
    
                    <div class="news-bloc-info">
    
                        <span>категория</span>
                        <p class="news-bloc-title">Мы запустили обмен Ripple XRP</p>
    
                        <div class="news-bloc-info_item">
                            <div class="news-bloc-info_item-photo-name">
                                <div class="news-bloc-info_item-photo">
                                    <img src="img/user.svg" alt="">
                                </div>
                                <div class="news-bloc-info_item-name">
                                    <p><b>Илья Новиков</b></p>
                                    <span>11 янв. 2018 г.</span>
                                </div>
                            </div>
                            <div class="news-bloc-info_item-data">
    
                                <span><img src="img/visible.svg" alt=""> <span>2354</span></span>
    
                                <!--<a href="" class="news-bloc-flag"><img src="../assets/img/bookmark.svg" alt=""></a>-->
    
                            </div>
                        </div>
    
                    </div>
    
                </li>
            </ul>
    
    </div>
</div>

    <div class="reviews-bloc">
    
        <div class="container">
    
            <h3 class="title">
                Отзывы
    
                <a href="/reviews.html" class="btn btn-look">смотреть все</a>
            </h3>
    
            <ul>
                <li>
                    <div class="reviews-bloc-txt">
                        <p class="reviews-bloc-date">11 янв. 2018 г.</p>
                        <p class="reviews-bloc__">всё класс вывожу тут самые большие суммы, даже не бойтесь всё отлично проходит, не делайте ошибок в цифрах!</p>
                    </div>
    
                    <div class="reviews-bloc-client">
                        <div class="reviews-bloc-photo">
                            <img src="../assets/img/user.svg" alt="">
                        </div>
                        <div>
                            <p><b>Илья Новиков</b></p>
                            <span>&#9733;</span><span>&#9733;</span><span>&#9733;</span><span>&#9733;</span><span>&#9733;</span>
                        </div>
                    </div>
    
    
                </li>
                <li>
                    <div class="reviews-bloc-txt">
                        <p class="reviews-bloc-date">11 янв. 2018 г.</p>
                        <p class="reviews-bloc__">всё класс вывожу тут самые большие суммы, даже не бойтесь всё отлично проходит, не делайте ошибок в цифрах!</p>
                    </div>
    
                    <div class="reviews-bloc-client">
                        <div class="reviews-bloc-photo">
                            <img src="../assets/img/user.svg" alt="">
                        </div>
                        <div>
                            <p><b>Илья Новиков</b></p>
                            <span>&#9733;</span><span>&#9733;</span><span>&#9733;</span><span>&#9733;</span><span>&#9733;</span>
                        </div>
                    </div>
    
    
                </li>
                <li>
                    <div class="reviews-bloc-txt">
                        <p class="reviews-bloc-date">11 янв. 2018 г.</p>
                        <p class="reviews-bloc__">всё класс вывожу тут самые большие суммы, даже не бойтесь всё отлично проходит, не делайте ошибок в цифрах!</p>
                    </div>
    
                    <div class="reviews-bloc-client">
                        <div class="reviews-bloc-photo">
                            <img src="../assets/img/user.svg" alt="">
                        </div>
                        <div>
                            <p><b>Илья Новиков</b></p>
                            <span>&#9733;</span><span>&#9733;</span><span>&#9733;</span><span>&#9733;</span><span>&#9733;</span>
                        </div>
                    </div>
    
    
                </li>
    
            </ul>
    
        </div>
    
    
    
    </div>

<div class="container">
    
    <div class="our-partner">
        <h3 class="title">Наши партнеры</h3>
    
        <ul>
            <li><img src="img/partner-payer.png" alt=""></li>
            <li><img src="img/partner-sberbank.png" alt=""></li>
            <li><img src="img/partner-best-chang.png" alt=""></li>
            <li><img src="img/partner-perfect-many.png" alt=""></li>
            <li><img src="img/partner-qiwi.png" alt=""></li>
        </ul>
    </div>
</div>




<div class="footer footer-support">

    <div class="container">

        <div>

            <h4>Контактный центр</h4>

            <div class="contact contact-mail">
                <span>e-mail</span>
                <p>support@proexhenger.net</p>
            </div>

            <div class="contact contact-phone">
                <span>телефон</span>
                <p>+7 (386) 574-93-47</p>
            </div>

            <div class="contact contact-telegram">
                <span>telegram</span>
                <p>@proexhenger_test</p>
            </div>

            <div class="contact contact-work-time">
                <span>время работы</span>
                <p>пн-пт с 9:00 до 19:00</p>
            </div>

        </div>

        <div>

            <h4>Онлайн-поддержка</h4>
            <p>Контактный центр поможет Вам в решении любого вопроса!</p>

            <form action="" class="form-footer">

                <div>
                    <input type="email" placeholder="Ваше имя">
                </div>

                <div>
                    <textarea cols="30" rows="3" placeholder="Введите свое сообщение"></textarea>
                </div>

                <button class="btn btn-submit">Отправить сообщение</button>
            </form>

        </div>

    </div>

</div>


<footer class="footer">

    <div class="footer-bottom">
        <div class="container">
            <p>	&copy; 2018 ProExchange.net— сервис обмена электронных валют.</p>
            <ul>
                <li><a href="/about-us.html">О сервисе</a></li>
                <li><a href="/specification.html">Правила сервиса</a></li>
                <!--<li><a href="">Подарки от сайта</a></li>-->
                <li><a href="/contact-page.html">Контакты</a></li>
            </ul>
        </div>
    </div>

</footer>

<div class="popup popup-registration">

    <div class="popup-close-bloc"></div>

    <div class="popup-wr">

        <span class="popup-close-btn">&otimes;</span>

        <div class="popup-wr-item">

                <div class="popup-top">
                    <h5 class="title text-center">Регистрация</h5>

                    <form action="">
                        <div>
                            <label>
                                <input type="text" placeholder="Введите имя и фамилию">
                                <span>Фамилия и имя</span>
                            </label>
                        </div>
                        <div>
                            <label>
                                <input type="email" placeholder="Введите email">
                                <span>Введите e-mail</span>
                            </label>
                        </div>
                       <!-- <div>
                            <label>
                                <input type="tel" placeholder="+3 8 (___) __-__-__">
                                <span>Номер телефона</span>
                            </label>
                        </div>-->

                        <div class="popup-registration_passwords-bloc">
                            <div>
                                <label class="popup-succes">
                                    <input type="password" placeholder="password">
                                    <span>Придумайте пароль</span>
                                </label>
                            </div>
                            <div>
                                <label class="popup-error">
                                    <input type="password" placeholder="password">
                                    <span>Повторите пароль</span>
                                </label>
                            </div>
                        </div>

                        <div class="text-center"><button class="btn btn-submit">Зарегистрироваться</button></div>
                    </form>

                    <div class="popup-personal-date text-center"><p>Нажимая на кнопку “Зарегистрироваться” я даю
                        согласие на обработку <a href="/">персональных данных</a></p></div>
                </div>

                
                <div class="popup-bottom">
                    <p class="popup-bottom-title text-center">Войти через:</p>
                
                    <ul>
                        <li><a href=""><img src="img/google-plus.svg" alt=""></a></li>
                        <li><a href=""><img src="img/facebook.svg" alt=""></a></li>
                        <li><a href=""><img src="img/vk.svg" alt=""></a></li>
                        <li><a href=""><img src="img/twitter.svg" alt=""></a></li>
                        <li><a href=""><img src="img/ok.svg" alt=""></a></li>
                    </ul>
                </div>

        </div>


    </div>

</div>

<div class="popup popup-personal-room">

    <div class="popup-close-bloc popup-close-bloc-personal-room"></div>

    <div class="popup-wr">

        <span class="popup-close-btn popup-close-btn-personal-room">&otimes;</span>

        <div class="popup-wr-item">

                <div class="popup-top">
                    <h5 class="title text-center">Войти в личный кабинет</h5>

                    <form action="">
                        <div>
                            <label>
                                <input type="email" placeholder="Введите email">
                                <span>Ваш e-mail</span>
                            </label>
                        </div>

                        <div>
                            <label>
                                <input type="password" placeholder="password">
                                <span>Повторите пароль</span>
                            </label>
                        </div>

                        <div class="text-center"><button class="btn btn-submit">Зарегистрироваться</button></div>
                    </form>

                    <div class="popup-personal-date text-center"><p>Нажимая на кнопку “Зарегистрироваться” я даю
                        согласие на обработку <a href="/">персональных данных</a></p></div>
                </div>

                
                <div class="popup-bottom">
                    <p class="popup-bottom-title text-center">Войти через:</p>
                
                    <ul>
                        <li><a href=""><img src="img/google-plus.svg" alt=""></a></li>
                        <li><a href=""><img src="img/facebook.svg" alt=""></a></li>
                        <li><a href=""><img src="img/vk.svg" alt=""></a></li>
                        <li><a href=""><img src="img/twitter.svg" alt=""></a></li>
                        <li><a href=""><img src="img/ok.svg" alt=""></a></li>
                    </ul>
                </div>

        </div>


    </div>

</div>


<div class="popup popup-order">

    <div class="popup-close-bloc popup-close-bloc-order"></div>

    <div class="popup-wr">

        <span class="popup-close-btn popup-close-btn-order">&otimes;</span>

        <div class="popup-wr-item">

                <div class="popup-top">
                    <h5 class="title text-center">Заказ резерва</h5>

                    <div class="form-information-sent-received-wr">

                        <div class="form-information-sent-received_img">
                            <img src="../assets/img/pb.png" alt="">
                        </div>

                        <div class="form-information-sent-received_info">
                            <p class="title">Privat24 UAH</p>
                            <p class="title"><span>419.91</span></p>
                        </div>

                    </div>

                    <form action="">
                        <div>
                            <label>
                                <input type="text" placeholder="0,00">
                                <span>Введите необходимую сумму</span>
                            </label>
                        </div>
                        <div>
                            <label>
                                <input type="email" placeholder="Введите email">
                                <span>Ваш e-mail</span>
                            </label>
                        </div>

                        <div>
                            <label>
                                <textarea placeholder="Хотите что-то добавить?"></textarea>
                                <span>Комментарий</span>
                            </label>
                        </div>

                        <div class="text-center"><button class="btn btn-submit">Запросить</button></div>
                    </form>

                </div>

        </div>


    </div>

</div>
</div>
</template>

<script>

export default {

}
</script>

<style lang='scss'>
    @import "~/assets/sass/style.scss";
</style>
