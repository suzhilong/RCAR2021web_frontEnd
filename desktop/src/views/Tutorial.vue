<template>
  <div>
    <div class="server-articles">
      <div class=" body-main px-3 bg-white fs-xxl" v-html="models[1].submenus[2].body"></div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {}
  },
  data() {
    return {
      models: {
        submenus: {}
      }
    };
  },
  methods: {
    async fetchArticles() {
      const res = await this.$http.get("articles");
      this.models = res.data;
      console.log(this.models);
    }
  },
  created() {
    this.fetchArticles();
  }
};
</script>

<style>
</style>