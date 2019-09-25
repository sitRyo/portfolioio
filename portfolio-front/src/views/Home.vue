<template>
  <b-container class="home">
    <div>
      <div class="profile pt-5">
      <i class="fas fa-address-card fa-3x pr-3"></i>
      <span class="profile-title">Profile</span>
      <b-row class="pt-4">
        <b-col>
          <img src="../assets/risu.jpg" class="profile-image pt-4" height="229" width="314">
        </b-col>      
        <b-col class="pt-2">
          <div class="profile-text">
            <p class="mt-2">こんにちは. <br>
            私は芝浦工業大学大学院1年 ぐんじと申します.<br>
            </p>
            <p>
            Webやインフラ, ゲームなどのジャンルに興味がある競技プログラマです。
            </p>
            <p>
            最近は特にUnityを使ったゲーム開発を行っています。
            </p>
            <p>
            これからも日々の進捗を挙げていく予定なので、もしよかったら他のページなどものぞいてみてください。(19/9/25)
            </p>
          </div>
        </b-col>
      </b-row>
      </div>
    </div>
  </b-container>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap-vue/dist/bootstrap-vue.css';

export default class Home extends Vue {}
</script>

<style scoped>
.home {
  width: 100%;
}


.profile-title {
  text-align: center;
  font-weight: 900;
  letter-spacing: .05em;
  font-size: 300%;
}

.profile-text {
  font-family: "游ゴシック体", "Yu Gothic", YuGothic,
   "ヒラギノ角ゴシック Pro", "Hiragino Kaku Gothic Pro", 'メイリオ' , 
   Meiryo , Osaka, "ＭＳ Ｐゴシック", "MS PGothic", sans-serif;
  font-weight: 600;
}

</style>