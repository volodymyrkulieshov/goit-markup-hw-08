<!-- old header -->

    <header class="header">
      <div class="header__nav header__container container">
        <nav class="nav">
          <a lang="en" class="logo logo__header link" href="index.html"
            >Web<span class="logo__black">Studio</span>
          </a>
          <ul class="nav__list list">
            <li class="nav__item">
              <a class="nav__link nav__link--current link" href="./index.html">Студия</a>
            </li>
            <li class="nav__item">
              <a class="nav__link link" href="./portfolio.html">Портфолио</a>
            </li>
            <li class="nav__item">
              <a class="nav__link link" href="">Контакты</a>
            </li>
          </ul>
        </nav>
        <ul class="contacts list">
          <li class="contacts__item">
            <a class="contacts__mail link" href="mailto:info@devstudio.com"
              ><svg class="contacts__icon" width="16" height="12">
                <use href="./images/sprite.svg#envelope"></use>
              </svg>
              info@devstudio.com
            </a>
          </li>
          <li class="contacts__item">
            <a class="contacts__tel link" href="tel:+380961111111">
              <svg class="contacts__icon" width="10" height="16">
                <use href="./images/sprite.svg#phone"></use>
              </svg>
              +38 096 111 11 11</a
            >
          </li>
        </ul>
        <ul class="menu-networks list">
            <li class="menu-networks__item"><a class="menu-networks__link" href="">Instagram</a></li>
            <li class="menu-networks__item"><a class="menu-networks__link" href="">Twitter</a></li>
            <li class="menu-networks__item"><a class="menu-networks__link" href="">Facebook</a></li>
            <li class="menu-networks__item">
              <a class="menu-networks__link" href="">LinkedIn</a>
            </li>
          </ul>
      </div>
      <button
          type="button"
          class="menu-button"
          aria-expanded="false"
          aria-controls="header__menu"
          data-menu-button
        >
          <svg width="40" height="40" aria-label="Open mobile menu">
            <use class="icon-close" href="./images/sprite.svg#icon-close-menu"></use>
            <use class="icon-menu" href="./images/sprite.svg#icon-mobile-menu"></use>
          </svg>
        </button>

        <div class="header__menu" id="header__menu" data-menu>
    </header>

    ///////////////OLD HEADER STYLES////////////////////////////

// .header\_\_nav { // @include flex-centered(); // }

// .nav { // @include flex-centered(); // font-weight: 500; // line-height: 1.14; // letter-spacing:
0.02em; // }

// .nav\_\_list { // display: flex; // margin-left: 93px; // }

// .nav\_\_item:not(:last-child) { // margin-right: 50px; // }

// .nav\_\_link { // display: block; // padding-top: 32px; // padding-bottom: 32px;

// color: $title-color; // font-weight: 500; // line-height: 1.14; // letter-spacing: 0.02em; //
transition: color $timing-duration $timing-function;

// &:hover, // &:focus { // color: $brand-accent; // } // }

// .nav\_\_link--current { // position: relative; // color: $brand-accent;

// &:after { // position: absolute; // left: 0; // bottom: -1px; // content: ''; // display: block;
// width: 100%; // height: 4px; // background: $brand-accent; // border-radius: 2px; // } // }

/_ -------------------header-contacts---------------------- _/

// .contacts { // @media screen and (max-width: 767px) { // display: flex; // // margin-bottom:
64px; // flex-direction: column-reverse; // } // @include desktop { // display: flex; //
align-items: center; // } // @include flex-centered(); // padding-top: 32px; // padding-bottom:
32px; // margin-left: auto; // font-weight: 500; // font-size: 14px; // line-height: 1.14; //
letter-spacing: 0.02em; // }

// .contacts\_\_item:not(:last-child) { // margin-right: 40px; // }

// .contacts**tel, // .contacts**mail { // @include flex-centered(); // width: 100%; // height:
100%; // color: $basic-color; // transition: color $timing-duration $timing-function;

// &:hover, // &:focus { // color: $brand-accent; // } // }

// .contacts**icon, // .contacts**icon { // fill: currentColor; // margin-right: 10px; // }
