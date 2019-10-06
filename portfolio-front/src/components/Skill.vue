<template>
  <div class="root">
  <b-container class="skill">
    <!-- <template v-for="data in cardData"> -->
    <b-row>
      <b-col v-for="(data, index) in cardData" :key="index" cols="6" class="mb-4">
        <b-card :class="data.className">
        <b-card-title>{{data.header}}</b-card-title>
        <b-card-text>
          {{index}}
        </b-card-text>
        </b-card>
      </b-col>
    </b-row>
    <!-- </template> -->
  </b-container>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap-vue/dist/bootstrap-vue.css';

@Component
export default class Skill extends Vue {
  private cardData: object[] = [
    {
      header: 'C++',
      headerTag: 'card-header',
      className: 'skill-card',
      cardText: 'this is test',
    },
    {
      header: 'C#',
      headerTag: 'card-header',
      className: 'skill-card',
      cardText: 'this is test',
    },
    {
      header: 'JavaScript/ TypeScript',
      headerTag: 'card-header',
      className: 'skill-card',
      cardText: 'this is test',
    },
    {
      header: 'Java',
      headerTag: 'card-header',
      className: 'skill-card',
      cardText: 'this is test',
    },
  ];
}

</script>

<style scoped>
.card-header {
  text-align: center;
  font-weight: 600;
}
</style>
