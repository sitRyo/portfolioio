<template>
  <div id="app">
    <header>
      <h1>Ryo Portfolio</h1>
      <h2>Enginnering Student</h2>
    </header>
    <nav>
      <ul>
        <li class="nav-element">ホーム</li>
        <li class="nav-element">製作物</li>
        <li class="nav-element">ブログ/Qiita</li>
        <li class="nav-element">連絡先</li>
      </ul>
    </nav>
    <router-view/>
    <footer class="pt-5 pb-3">
      <span class="footer-text">Ryota Gunji Since 2019</span>
    </footer>
  </div>
</template>

<style>
#app {
  background-color: #f8f8f8;
}

header {
  position: relative;
  height: 50vh;
  background: url(./assets/header1.png) center / cover;
}

header h1 {
  position: absolute;
  text-align: left;
	z-index: 1;
	width: 100%;
	margin: 0;
	padding: 0.5em;
	color: #fff;
	font-size: 3rem;
	font-family: "Dosis", sans-serif;
	letter-spacing: .1em;
}

header h2 {
  position: absolute;
  text-align: left;
  z-index: 1;
  top: 15%;
  width: 100%;
  margin: 0;
  padding: .5em 0 0 1em;
  color: #fff;
  font-size: 1.5rem;
}

nav {
  width: 100%;
  background-color: #fff;
  font-family: 'Quicksand', "游ゴシック体", "Yu Gothic", YuGothic,
   "ヒラギノ角ゴシック Pro", "Hiragino Kaku Gothic Pro", 'メイリオ' , 
   Meiryo , Osaka, "ＭＳ Ｐゴシック", "MS PGothic", sans-serif;
  z-index: 10;
  box-shadow: 0px 2px 2px #9999;  
  text-align: center;
  margin-block-start: .2em;
  margin-block-end: .2em;
  padding-block-start: .5em;
  padding-block-end: .5em;
}

.nav-element {
  display: inline-block;
  text-decoration: none;
  font-weight: 600;
  margin-inline-start: 2em;
  margin-inline-end: 2em;
  padding-inline-start: 1em;
  padding-inline-end: 1em;
  padding-block-start: .5em;
  padding-block-end: .5em;
  transition-duration: 1s;
  border-radius: 3px;
}

footer {
  position: relative;
  width: 100%;
  text-align: center;
  margin-block-start: 1em;
  /* margin-block-end: 1em; */
}

.footer-text {
  color: #aaaaaa;
  font-weight: 600;
}

a:hover {
  background-color:#cccccc;
}

</style>
