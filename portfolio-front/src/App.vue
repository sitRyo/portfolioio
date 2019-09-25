<template>
  <div id="app">
    <header>
      <h1>Ryo Portfolio</h1>
      <h2>Enginnering Student</h2>
    </header>
    <nav>
      <router-link to="/" class="nav-element">ホーム</router-link>
      <router-link to="/about" class="nav-element">製作物</router-link>
      <router-link to="/blog" class="nav-element">ブログ</router-link>
      <router-link to="/contact" class="nav-element">連絡先</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
header {
  position: relative;
  height: 30vh;
  background: url(./assets/header-portfolio2.jpg) center / cover;
}

header h1 {
  position: absolute;
  text-align: center;
	z-index: 1;
	top: 50%;
	width: 100%;
	margin: 0;
	padding: 0.5em;
	color: #fff;
	font-size: 5rem;
	font-family: "Dosis", sans-serif;
	letter-spacing: .1em;
	transform: translateY(-50%);
}

header h2 {
  position: absolute;
  text-align: center;
  z-index: 1;
  top: 70%;
  width: 100%;
  margin: 0;
  padding: 0.5em;
  color: #fff;
  font-size: 2rem;
  transform: translateY(-50%);
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

a:hover {
  background-color:#cccccc;
}

</style>
