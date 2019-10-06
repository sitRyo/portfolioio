<template>
  <b-container class="blog">
    <b-row class="blog-row pb-3">
      <b-col>
        <div class="qiita">
          <span class="subtitle pl-2">Qiita</span>
          <b-card class="mt-3">
            
          </b-card>
        </div>
      </b-col>
      <b-col>
        <div class="hatena-blog">
          <span class="subtitle pl-2 pb-3">Blog</span>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Blog extends Vue {}
</script>

<style>
.subtitle {
  font-weight: 600;
  font-size: 1.5rem;
}

</style>