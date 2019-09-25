<template>
  <div class="root">
  <b-container class="skill">
    <b-row>
      <b-col>
        <b-card
          header="C++"
          header-tag="card-header"
          class="skill-card"
        >
        <b-card-text>
          
        </b-card-text>
        </b-card>
      </b-col>
      <b-col>
        <b-card
          header="JavaScript / TypeScript"
          header-tag="card-header"
          class="skill-card"
        >
        <b-card-text>this is test</b-card-text>
        </b-card>
      </b-col>
    </b-row>
    <b-row class="mt-3">
      <b-col>
        <b-card
          header="Java"
          header-tag="card-header"
          class="skill-card"
        >
        <b-card-text>this is test</b-card-text>
        </b-card>
      </b-col>
      <b-col>
        <b-card
          header="C#"
          header-tag="card-header"
          class="skill-card"
        >
        <b-card-text>this is test</b-card-text>
        </b-card>
      </b-col>
    </b-row>
  </b-container>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap-vue/dist/bootstrap-vue.css';
export default class Skill extends Vue {}

</script>

<style scoped>
.card-header {
  text-align: center;
  font-weight: 600;
}
</style>
