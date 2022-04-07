<script setup>

</script>

<template>
  <div class="header">
    <div class="center-header">
      <div class="box-menus">
        <div class="logo">
          <a href>
            <img src="./assets/img/logo-intercom.png" width="100%" />
          </a>
        </div>
        <div class="box-enlaces">
          <a
            target="_blank"
            rel="noopener"
            href="https://www.intercom.com"
            class="header__home__url"
          >
            <svg width="14" height="14" viewBox="0 0 14 14" xmlns="http://www.w3.org/2000/svg">
              <g
                stroke="#FFF"
                fill="none"
                fill-rule="evenodd"
                stroke-linecap="round"
                stroke-linejoin="round"
              >
                <path d="M11.5 6.73v6.77H.5v-11h7.615M4.5 9.5l7-7M13.5 5.5v-5h-5" />
              </g>
            </svg>
            <span>Ir a Intercom</span>
          </a>

          <select
            name="locale-picker"
            id="locale-picker"
            class="locale-picker"
            data-locale="es"
            style="width: 89px;"
          >
            <option data-locale="de" value="/help/de/">Deutsch</option>
            <option data-locale="en" value="/help/en/">English</option>
            <option data-locale="es" selected="selected" value="Español">Español</option>
            <option data-locale="fr" value="/help/fr/">Français</option>
            <option data-locale="pt-BR" value="/help/pt-BR/">Português do Brasil</option>
            <option data-locale="ja" value="/help/ja/">日本語</option>
          </select>
          <select
            name="hidden_locales"
            id="locale-picker-for-width-calculation"
            class="locale-picker"
            style
          >
            <option value>Español</option>
          </select>
        </div>
      </div>
      <h1 class="header__headline">Consejos y respuestas del Equipo de Productos Digitales</h1>
      <form action autocomplete="off" class="header__form search">
        <input
          type="text"
          autocomplete="off"
          class="search__input js__search-input o__ltr"
          placeholder="Buscar respuestas..."
          tabindex="1"
          name="q"
          value
        />
        <div class="search_icons">
          <button type="submit" class="search__submit o__ltr"></button>
          <a class="search__clear-text__icon">
            <svg
              class="interface-icon"
              xmlns="http://www.w3.org/2000/svg"
              width="16"
              height="16"
              viewBox="0 0 16 16"
            >
              <path
                d="M8.018 6.643L5.375 4 4 5.375l2.643 2.643L4 10.643 5.375 12l2.643-2.625L10.625 12 12 10.643 9.357 8.018 12 5.375 10.643 4z"
              />
            </svg>
          </a>
        </div>
      </form>
    </div>
  </div>
  <div class="container">
    <div class="content educate_content">
      <section class="section">
        <!--caluga 1-->
        <div class="g__space">
          <a href="/help/es/collections/382-que-es-intercom" class="paper">
            <div class="collection o__ltr">
              <div class="collection__photo">
                <svg role="img" viewBox="0 0 48 48">
                  <g id="info-question" fill="none" fill-rule="evenodd">
                    <path d="M24 34a2 2 0 1 0 0 4 2 2 0 0 0 0-4" fill="#818a97" />
                    <path
                      d="M47 24c0 12.703-10.297 23-23 23S1 36.703 1 24 11.297 1 24 1s23 10.297 23 23z"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                    <path
                      d="M18 19a6 6 0 1 1 6 6v6"
                      stroke-width="2"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    />
                  </g>
                </svg>
              </div>
              <div class="collection_meta" dir="ltr">
                <h2 class="t__h3 c__primary">Primeros pasos y preguntas hiper frecuentes</h2>
                <p class="paper__preview"> ¿Cómo empiezo?</p>
                <div class="avatar">
                  <div class="avatar__photo avatars__images o__ltr">
                    <img
                      src="https://static.intercomassets.com/avatars/3246904/square_128/101-1607545843.jpg?1607545843"
                      alt="Damon Alexander avatar"
                      class="avatar__image"
                    />
                  </div>
                  <div class="avatar__info">
                    <div>
                      <span class="c__darker">2 artículos en esta apartado</span>
                      <br />Redactado por
                      <span class="c__darker">Damon Alexander</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
        <!--Fin caluga 1-->
        <!--caluga 2-->
        <div class="g__space">
          <a href="/help/es/collections/382-que-es-intercom" class="paper">
            <div class="collection o__ltr">
              <div class="collection__photo">
                <svg role="img" viewBox="0 0 48 48">
                  <g id="chat-single">
                    <path
                      d="M47 21.766C47 32.13 36.703 40.53 24 40.53c-2.835 0-5.55-.417-8.058-1.183l-13.217 6.15L7.9 35.167C3.643 31.76 1 27.015 1 21.767 1 11.4 11.297 3 24 3s23 8.402 23 18.766z"
                      stroke-width="2"
                      fill="none"
                      stroke-linejoin="round"
                    />
                  </g>
                </svg>
              </div>
              <div class="collection_meta" dir="ltr">
                <h2 class="t__h3 c__primary">Organización y Equipo</h2>
                <p class="paper__preview"> ¿Dónde estoy parado?</p>
                <div class="avatar">
                  <div class="avatar__photo avatars__images o__ltr">
                    <img
                      src="https://static.intercomassets.com/avatars/3246904/square_128/101-1607545843.jpg?1607545843"
                      alt="Damon Alexander avatar"
                      class="avatar__image"
                    />
                  </div>
                  <div class="avatar__info">
                    <div>
                      <span class="c__darker">2 artículos en esta apartado</span>
                      <br />Redactado por
                      <span class="c__darker">Damon Alexander</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
        <!--Fin caluga 2-->
        <!--caluga 3-->
        <div class="g__space">
          <a href="/help/es/collections/382-que-es-intercom" class="paper">
            <div class="collection o__ltr">
              <div class="collection__photo">
                <svg role="img" viewBox="0 0 48 48">
                  <g
                    id="devices-server"
                    stroke-width="2"
                    fill="none"
                    fill-rule="evenodd"
                    stroke-linecap="round"
                  >
                    <path
                      d="M43 11c0 4.418-8.508 8-19 8S5 15.418 5 11s8.508-8 19-8 19 3.582 19 8zm0 8c0 4.418-8.508 8-19 8S5 23.418 5 19m38 9c0 4.418-8.508 8-19 8S5 32.418 5 28"
                    />
                    <path d="M5 11v26c0 4.418 8.508 8 19 8s19-3.582 19-8V11" />
                  </g>
                </svg>
              </div>
              <div class="collection_meta" dir="ltr">
                <h2 class="t__h3 c__primary">Diseño</h2>
                <p class="paper__preview"> Desde como se diseña un botón hasta como hacer research </p>
                <div class="avatar">
                  <div class="avatar__photo avatars__images o__ltr">
                    <img
                      src="https://static.intercomassets.com/avatars/3246904/square_128/101-1607545843.jpg?1607545843"
                      alt="Damon Alexander avatar"
                      class="avatar__image"
                    />
                  </div>
                  <div class="avatar__info">
                    <div>
                      <span class="c__darker">2 artículos en esta apartado</span>
                      <br />Redactado por
                      <span class="c__darker">Damon Alexander</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
        <!--Fin caluga 3-->
        <!--caluga 4-->
        <div class="g__space">
          <a href="/help/es/collections/382-que-es-intercom" class="paper">
            <div class="collection o__ltr">
              <div class="collection__photo">
                <svg role="img" viewBox="0 0 48 48">
                  <g id="chat-user" fill="none" fill-rule="evenodd">
                    <path
                      d="M12 32.395v4.342L4.117 39.56C2.23 40.235 1 42.02 1 44.022V47h30v-2.977c0-2.003-1.232-3.788-3.117-4.463L20 36.737v-4.613"
                      stroke-width="2"
                    />
                    <path
                      d="M23.697 24.105c0 5.232-3.534 9.475-7.895 9.475-4.36 0-7.895-4.243-7.895-9.475 0-5.232 3.535-9.473 7.895-9.473 4.36 0 7.895 4.242 7.895 9.473z"
                      stroke-width="2"
                    />
                    <path
                      d="M23.646 23.25c-.265.032-.47.015-.738.065-2.69.52-4.416-.456-5.897-3.046-.884 1.7-3.66 3.042-5.94 3.042-1.124 0-2.114-.205-3.08-.71M21 13c0-6.628 5.82-12 13-12s13 5.372 13 12c0 4.992-3.302 9.272-8 11.08C38 25 33 30 32 31c0-1 0-5 .007-6.14-1.06-.15-2.08-.42-3.04-.792"
                      stroke-width="2"
                    />
                    <path d="M40 13h-2v2h2v-2zm-5 0h-2v2h2v-2zm-5 0h-2v2h2v-2z" fill="#231F1F" />
                  </g>
                </svg>
              </div>
              <div class="collection_meta" dir="ltr">
                <h2 class="t__h3 c__primary">Desarrollo</h2>
                <p class="paper__preview">Como desarrollamos y con que desarrollamos</p>
                <div class="avatar">
                  <div class="avatar__photo avatars__images o__ltr">
                    <img
                      src="https://static.intercomassets.com/avatars/3246904/square_128/101-1607545843.jpg?1607545843"
                      alt="Damon Alexander avatar"
                      class="avatar__image"
                    />
                  </div>
                  <div class="avatar__info">
                    <div>
                      <span class="c__darker">2 artículos en esta apartado</span>
                      <br />Redactado por
                      <span class="c__darker">Damon Alexander</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
        <!--Fin caluga 4-->
        <!--caluga 5-->
        <div class="g__space">
          <a href="/help/es/collections/382-que-es-intercom" class="paper">
            <div class="collection o__ltr">
              <div class="collection__photo">
                <svg role="img" viewBox="0 0 48 48">
                  <g
                    id="comms-mail"
                    stroke-width="2"
                    fill="none"
                    fill-rule="evenodd"
                    stroke-linejoin="round"
                  >
                    <path d="M47 3L1 22l18 7L47 3z" />
                    <path d="M47 3l-8 37-20-11L47 3zM19 29v16l7-12" />
                  </g>
                </svg>
              </div>
              <div class="collection_meta" dir="ltr">
                <h2 class="t__h3 c__primary">Datos</h2>
                <p class="paper__preview"> ¿Dudas sobre que base de datos usar? Aquí las preguntas mas típicas </p>
                <div class="avatar">
                  <div class="avatar__photo avatars__images o__ltr">
                    <img
                      src="https://static.intercomassets.com/avatars/3246904/square_128/101-1607545843.jpg?1607545843"
                      alt="Damon Alexander avatar"
                      class="avatar__image"
                    />
                  </div>
                  <div class="avatar__info">
                    <div>
                      <span class="c__darker">2 artículos en esta apartado</span>
                      <br />Redactado por
                      <span class="c__darker">Damon Alexander</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
        <!--Fin caluga 5-->
        <!--caluga 6-->
        <div class="g__space">
          <a href="/help/es/collections/382-que-es-intercom" class="paper">
            <div class="collection o__ltr">
              <div class="collection__photo">
                <svg role="img" viewBox="0 0 48 48">
                  <g
                    id="book-bookmark"
                    stroke-width="2"
                    fill="none"
                    fill-rule="evenodd"
                    stroke-linecap="round"
                  >
                    <path d="M35 31l-6-6-6 6V7h12v24z" />
                    <path d="M35 9h6v38H11a4 4 0 0 1-4-4V5" stroke-linejoin="round" />
                    <path d="M39 9V1H11a4 4 0 0 0 0 8h12" stroke-linejoin="round" />
                  </g>
                </svg>
              </div>
              <div class="collection_meta" dir="ltr">
                <h2 class="t__h3 c__primary">Acuerdos de Equipo</h2>
                <p class="paper__preview">Acuerdos generales que hacen la vida del trabajo mas fácil y con mejor entendimiento</p>
                <div class="avatar">
                  <div class="avatar__photo avatars__images o__ltr">
                    <img
                      src="https://static.intercomassets.com/avatars/3246904/square_128/101-1607545843.jpg?1607545843"
                      alt="Damon Alexander avatar"
                      class="avatar__image"
                    />
                  </div>
                  <div class="avatar__info">
                    <div>
                      <span class="c__darker">2 artículos en esta apartado</span>
                      <br />Redactado por
                      <span class="c__darker">Damon Alexander</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="collection_meta" dir="ltr">
                <h2 class="t__h3 c__primary">Glosario Tech</h2>
                <p class="paper__preview">AGP?, CAU?, AA?, SPP, CSC? BFF? Este es tu lugar</p>
                <div class="avatar">
                  <div class="avatar__photo avatars__images o__ltr">
                    <img
                      src="https://static.intercomassets.com/avatars/3246904/square_128/101-1607545843.jpg?1607545843"
                      alt="Damon Alexander avatar"
                      class="avatar__image"
                    />
                  </div>
                  <div class="avatar__info">
                    <div>
                      <span class="c__darker">2 artículos en esta apartado</span>
                      <br />Redactado por
                      <span class="c__darker">Damon Alexander</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </a>
        </div>
        <!--Fin caluga 6-->
      </section>
    </div>
  </div>

  <div class="footer">
    <div class="container">
      <div class="content">
        <div class="u__cf">
          <div class="footer__logo">
            <a href="#">
              <img src="./assets/img/logo-footer.png" />
            </a>
          </div>
          <div class="footer__links">
            <ul class="footer__link-list footer__links__custom">
              <li class="footer__link footer__link__" data-footer-link-type="custom">
                <a
                  target="_blank"
                  rel="nofollow noreferrer noopener"
                  href="https://forum.intercom.com/s/?utm_medium=article&amp;utm_source=help-center"
                >Community</a>
              </li>
              <li class="footer__link footer__link__" data-footer-link-type="custom">
                <a
                  target="_blank"
                  rel="nofollow noreferrer noopener"
                  href="https://www.intercom.com/webinars"
                >Webinars</a>
              </li>
              <li class="footer__link footer__link__" data-footer-link-type="custom">
                <a
                  target="_blank"
                  rel="nofollow noreferrer noopener"
                  href="https://academy.intercom.com/?utm_medium=internal&amp;utm_source=ii-helpcenter&amp;utm_campaign=201911_wc_intercom_academy&amp;utm_content=help_center_footer"
                >Academy</a>
              </li>
            </ul>

            <ul class="footer__link-list footer__links__social">
              <li class="footer__link footer__link__facebook" data-footer-link-type="facebook">
                <a
                  target="_blank"
                  rel="nofollow noreferrer noopener"
                  href="https://facebook.com/intercominc"
                >
                  <svg
                    viewBox="0 0 32 32"
                    version="1.1"
                    xml:space="preserve"
                    xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                  >
                    <path
                      d="M11.848,32h6.612V15.998h4.411l0.584-5.514H18.46l0.007-2.761c0-1.437,0.137-2.209,2.2-2.209h2.757V0h-4.412   c-5.299,0-7.164,2.675-7.164,7.174v3.311H8.545v5.515h3.303V32z"
                    />
                  </svg>
                </a>
              </li>
              <li class="footer__link footer__link__twitter" data-footer-link-type="twitter">
                <a
                  target="_blank"
                  rel="nofollow noreferrer noopener"
                  href="https://twitter.com/intercom"
                >
                  <svg
                    viewBox="0 0 32 32"
                    version="1.0"
                    xml:space="preserve"
                    xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                  >
                    <path
                      d="M31.993,6.077C30.816,6.6,29.552,6.953,28.223,7.11c1.355-0.812,2.396-2.098,2.887-3.63  c-1.269,0.751-2.673,1.299-4.168,1.592C25.744,3.797,24.038,3,22.149,3c-3.625,0-6.562,2.938-6.562,6.563  c0,0.514,0.057,1.016,0.169,1.496C10.301,10.785,5.465,8.172,2.227,4.201c-0.564,0.97-0.888,2.097-0.888,3.3  c0,2.278,1.159,4.286,2.919,5.464c-1.075-0.035-2.087-0.329-2.972-0.821c-0.001,0.027-0.001,0.056-0.001,0.082  c0,3.181,2.262,5.834,5.265,6.437c-0.55,0.149-1.13,0.23-1.729,0.23c-0.424,0-0.834-0.041-1.234-0.117  c0.834,2.606,3.259,4.504,6.13,4.558c-2.245,1.76-5.075,2.811-8.15,2.811c-0.53,0-1.053-0.031-1.566-0.092  C2.905,27.913,6.355,29,10.062,29c12.072,0,18.675-10.001,18.675-18.675c0-0.284-0.008-0.568-0.02-0.85  C30,8.55,31.112,7.395,31.993,6.077z"
                    />
                  </svg>
                </a>
              </li>
              <li class="footer__link footer__link__linkedin" data-footer-link-type="linkedin">
                <a
                  target="_blank"
                  rel="nofollow noreferrer noopener"
                  href="https://linkedin.com/company/2491343/"
                >
                  <svg
                    viewBox="0 0 32 32"
                    version="1.0"
                    xml:space="preserve"
                    xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                  >
                    <rect height="23" width="7" y="9" />
                    <path
                      d="M24.003,9C20,9,18.89,10.312,18,12V9h-7v23h7V19c0-2,0-4,3.5-4s3.5,2,3.5,4v13h7V19C32,13,31,9,24.003,9z"
                    />
                    <circle cx="3.5" cy="3.5" r="3.5" />
                  </svg>
                </a>
              </li>
            </ul>
          </div>
          <div class="footer__advert logo">
            <img src="./assets/img/logo-footer1.png" />
            <a
              href="https://www.intercom.com/intercom-link?company=Intercom&amp;solution=customer-support&amp;utm_campaign=intercom-link&amp;utm_content=We+run+on+Intercom&amp;utm_medium=help-center&amp;utm_referrer=https%3A%2F%2Fwww.intercom.com%2Fhelp%2Fes&amp;utm_source=desktop-web"
            >Usamos Intercom</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import "./assets/css/base.css";
html {
  color: #222;
  font-size: 1em;
  line-height: 1.4;
}

::-moz-selection {
  background: #b3d4fc;
  text-shadow: none;
}

::selection {
  background: #b3d4fc;
  text-shadow: none;
}

hr {
  display: block;
  height: 1px;
  border: 0;
  border-top: 1px solid #ccc;
  margin: 1em 0;
  padding: 0;
}

audio,
canvas,
iframe,
img,
svg,
video {
  vertical-align: middle;
}

fieldset {
  border: 0;
  margin: 0;
  padding: 0;
}

textarea {
  resize: vertical;
}

.browserupgrade {
  margin: 0.2em 0;
  background: #ccc;
  color: #000;
  padding: 0.2em 0;
}
h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin: 0;
}

@font-face {
  font-family: "Proxima Nova Rg";
  src: url(./assets/fonts/ProximaNova-Regular.woff2) format("woff2"),
    url(./assets/fonts/ProximaNova-Regular.woff) format("woff");
  font-weight: normal;
  font-style: normal;
  font-display: swap;
}

/* ==========================================================================
   Estilos Generales
   ========================================================================== */
.header {
  color: white;
  padding: 35px 0;
  margin-bottom: 7px;
  flex: none;
  position: relative;
  z-index: 10;
  background-size: cover;
  box-shadow: 0 1px 4px 0 rgb(0 0 0 / 20%);
  background-position: 50%;
  background-image: url(./assets/img/header.jpeg);
}
.center-header {
  width: 900px;
  height: 180px;
  margin: auto;
  /*background-color: red;*/
}
.box-menus {
  width: 100%;
  height: 37px;
  margin-bottom: 15px;
}
.logo {
  width: 252px;
  float: left;
}
.box-enlaces {
  width: 216px;
  height: 20px;
  float: right;
  /*background-color: green;*/
  margin-top: 0px;
}
.box-enlaces a {
  text-decoration: none;
  color: #fff;
  font-family: "Proxima Nova Rg";
  font-weight: 600;
  font-size: 13px;
}
.box-enlaces span {
  margin-left: 5px;
}

.locale-picker {
  font-weight: 600;
  font-size: 13px;
  line-height: 20px;
  height: 36px;
  color: #737373;
  padding: 0 32px 2px 32px;
  box-sizing: border-box;
  font-family: "Proxima Nova Rg";
  margin: 0 0px 0px 20px;
  border: 1px solid rgba(115, 115, 115, 0.2);
  border-radius: 100px;
  appearance: none;
  -webkit-appearance: none;
  background-color: #fff;
  background-image: url(./assets/img/mundo.svg), url(./assets/img/arrow.svg);
  /*background-image: url(../img/mundo.svg);*/
  background-repeat: no-repeat, no-repeat;
  background-position: 10px center, right 12px center;
  background-size: 14px, 16px;
  transition: border-color 0.25s, outline 0.25s;
  cursor: pointer;
  transition: all 0.3s;
}
.locale-picker:hover {
  opacity: 0.7;
}
#locale-picker-for-width-calculation {
  display: none;
}
.locale-picker {
  color: white;
  border: none;
  background-color: transparent;
  background-image: url(./assets/img/mundo.svg), url(./assets/img/arrow.svg);
  /*background-image: url(../img/mundo.svg);*/
  padding: 0 20px 2px 20px;
  background-position: left center, right center;
  position: relative;
  top: 1px;
  font-family: "Proxima Nova Rg";
}
:focus-visible {
  outline: -webkit-focus-ring-color auto 0px;
}
select {
  font-family: inherit !important;
}
.header__home__url {
  transition: all 0.3s;
}
.header__home__url:hover {
  opacity: 0.7;
}
.header__headline {
  font-family: "Proxima Nova Rg";
  font-size: 28px;
  font-weight: 300;
  margin: 0 0 27px;
  color: inherit;
}
.search {
  position: relative;
}
.search__input {
  width: 90%;
  height: 25px;
  padding: 20px 32px 21px 59px;
  background: rgba(255, 255, 255, 0.2);
  border: none;
  outline: none;
  color: rgba(255, 255, 255, 0.7);
  font-size: 18px;
  border-radius: 4px;
  box-shadow: 0 1px 2px 0 rgb(0 0 0 / 3%);
  transition: background 0.4s, box-shadow 0.2s;
}

.search__submit {
  width: 22px;
  height: 22px;
  border: none;
  background: transparent;
  position: absolute;
  top: 50%;
  left: 19px;
  margin-top: -10px;
  outline: none;
  cursor: pointer;
  transition: transform 0.1s linear;
}
.search__submit:before {
  content: " ";
  border: 2px solid white;
  border-radius: 50%;
  position: absolute;
  top: 0;
  left: 0;
  width: 16px;
  height: 16px;
}
.search__submit:after {
  content: " ";
  border-top: 2px solid white;
  position: absolute;
  bottom: 5px;
  right: 6px;
  width: 12px;
  height: 1px;
  transition: width 0.1s linear;
  transform-origin: 100% 50%;
  transform: rotate(-135deg);
}
.search__clear-text__icon {
  position: absolute;
  right: 0;
  top: 50%;
  width: 32px;
  height: 32px;
  box-sizing: border-box;
  margin-top: -14px;
}
.interface-icon {
  width: 25px;
  height: 25px;
  display: inline-block;
  vertical-align: middle;
  text-align: center;
}
.interface-icon path {
  fill: #9fa0a8 !important;
  fill-opacity: 0.01;
}
.search__input:active,
.search__input:focus {
  box-shadow: 0 10px 20px rgb(0 0 0 / 14%);
  background: white;
  color: #3a3c4c;
}
.search__input:hover {
  /*background: rgba(255, 255, 255, 0.27);*/
  box-shadow: 0 10px 20px rgb(0 0 0 / 3%);
}
.search__input:focus + .search_icons .search__submit:before,
.search__input:focus + .search_icons .search__submit:after,
.search__input:active + .search_icons .search__submit:before,
.search__input:active + .search_icons .search__submit:after {
  border-color: #9fa0a8;
}
.search__input:focus + .search_icons .search__submit:before,
.search__input:focus + .search_icons .search__submit:after,
.search__input:active + .search_icons .search__submit:before,
.search__input:active + .search_icons .search__submit:after {
  border-color: #9fa0a8;
}
::placeholder {
  color: rgba(255, 255, 255, 0.7);
}

.search__input:active::placeholder,
.search__input:focus::placeholder {
  color: #9fa0a7;
}

.container {
  padding-left: 40px;
  padding-right: 40px;
  flex: 1 0 auto;
}
.content {
  width: 900px;
  margin-left: auto;
  margin-right: auto;
}
.section {
  padding-top: 26px;
}
.paper {
  background-color: white;
  border: 1px solid transparent;
  border-radius: 4px;
  padding: 30px;
  position: relative;
  z-index: 3;
  text-decoration: none;
  overflow: hidden;
  width: 840px;
  display: block;
  outline: none;
  box-shadow: 0 3px 8px 0 rgb(0 0 0 / 3%);
  transition: border 0.15s linear, transform 0.15s linear,
    background-color 0.15s linear, box-shadow 0.15s linear, opacity 0.15s linear;
}
a.paper {
  background-color: #fff;
}
a.paper:hover {
  border: 1px solid rgba(136, 149, 162, 0.2);
  background-color: #fcfcfc;
}
.collection {
  position: relative;
  padding-left: 150px;
}
.collection__photo {
  position: absolute;
  left: 0;
  top: 0;
  width: 120px;
  height: 100%;
  transition: all 0.3s linear;
}
.collection__photo svg {
  stroke: #818a97;
}
.collection__photo svg {
  position: relative;
  width: 48px;
  height: 48px;
  transition: stroke 0.1s linear;
  top: 50%;
  left: 50%;
  margin: -24px 0 0 -24px;
}
.paper .c__primary {
  transition: -webkit-filter 0.15s;
}
.paper__preview {
  margin: 5px 0 11px;
  color: #565867;
  text-decoration: none;
  display: block;
  max-width: 630px;
  line-height: 1.4;
}
.avatar {
  font-size: 13px;
  color: #8f919d;
  margin-top: 4px;
}
.avatar:before,
.avatar:after {
  content: " ";
  display: table;
}
.avatar:after {
  clear: both;
}
.avatar__info,
.avatar__photo {
  line-height: 1.4;
}
.avatar__photo {
  margin-right: 10px;
  float: left;
}
.c__darker {
  color: #4f5e6b;
}
.avatar__image {
  width: 32px;
  height: 32px;
  vertical-align: bottom;
  border-radius: 50%;
  box-shadow: 0 0 0 2px white;
  position: relative;
  z-index: 4;
}

.article a,
.c__primary {
  color: #3047ec;
  font-size: 16px;
}
.g__space + .g__space {
  margin-top: 16px;
}
.footer {
  margin-top: 35px;
  padding: 40px 0;
  text-align: left;
  font-size: 14px;
  flex-shrink: 0;
  background: #ffffff;
  color: #a3abb5;
}
.u__cf:before,
.u__cf:after {
  content: " ";
  display: table;
}
.footer a {
  color: #909aa5;
  text-decoration: none;
}
.footer__logo img {
  max-height: 32px;
  filter: grayscale(100%) contrast(80%);
}
.footer__links {
  margin-top: 14px;
  margin-bottom: 28px;
}
.footer__link-list {
  padding: 0;
  text-align: center;
}
.footer__link {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  list-style-type: none;
}
.footer__advert a {
  padding-left: 5px;
  color: #a8b6c2;
  vertical-align: middle;
}
.footer__advert img {
  height: 14px;
  vertical-align: middle;
}
.footer__logo {
  height: 50px;
  line-height: 30px;
  text-align: center;
  vertical-align: middle;
}
.footer__advert {
  text-align: center;
  font-size: 14px;
  float: inherit;
  margin: auto;
}
.footer__links__social svg {
  width: 16px;
  height: 16px;
  fill: currentColor;
}
</style>
