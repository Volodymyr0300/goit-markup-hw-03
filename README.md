# goit-markup-hw-03
 goit-markup-hw-03


html {
	box-sizing: border-box;
}

*, *::before, *::after {
	box-sizing: inherit;
	outline: 2px solid tomato;
}

<!-- вставляется перед всеми стилями но после шрифтов. Позволяет загружать по ссылке нормализатор отображения элементов сайта на разных браузерах. Ставиться в link в href.	 -->
https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/1.1.0/modern-normalize.min.css



body-container
  width: 1200px;
  padding-left: 15px;
  padding-right: 15px;

.site-nav .item:not(:last-child) {
	margin-right: 40px;
}

or

.site-nav .item + .item {
	margin-right: 40px;
}

.align-items: center;



<!--  -->
h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin: 0;
}

ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

a {
  text-decoration: none;
}

img {
  display: block;
  max-width: 100%;
  height: auto;
}

.container {
  width: 1440px;
  margin: 0 auto;
}

.header {
  background-color: #fafafa;
}
.header-container {
  display: flex;
  align-items: center;
}
.header-logo {
  margin-left: 80px;
  font-family: "Homemade Apple", sans-serif;
}
.header-nav {
  margin-left: 433px;
}
.header-nav-list {
  display: flex;
}
.header-nav-list-item {
}
.header-nav-list-item:not(:first-child) {
  margin-left: 31px;
}
.header-nav-list-item-link {
  padding-top: 47px;
  padding-bottom: 47px;
  display: inline-block;
}
.header-button {
  margin-left: auto;
  margin-right: 34px;
  padding: 10px 22px;
  border: 1px solid #f7941e;
  border-radius: 5px;
  color: #f7941e;
  text-transform: uppercase;
  background-color: transparent;
}

/* Hero */
.hero {
  background-color: #f1f1f2;
}
.hero-container {
  display: flex;
}
.content {
  width: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.content-wrap {
  width: 433px;
}
.hero-title {
  font-family: "Roboto", sans-serif;
  font-size: 56px;
  line-height: 69px;
  margin-bottom: 36px;
}

.hero-text {
  font-family: "Roboto", sans-serif;
  font-size: 20px;
  line-height: 140.62%;
  margin-bottom: 60px;
}

.hero-button {
  font-family: "Roboto", sans-serif;
  font-size: 18px;
  line-height: 22px;
  text-transform: uppercase;
  color: #ffffff;
  background-color: #f7941e;
  border-radius: 5px;
  padding: 19px 25px;
  border: none;
}
