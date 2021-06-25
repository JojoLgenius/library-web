<template>
  <h1>{{ title }}</h1>
  <p>{{ msg }}</p>

  <h2> Users </h2>

<table class="Users">
<tr>
<td>Id</td>
<td>Name</td>
</tr>
</table>

  <h2> Books </h2>

<table class="Books">
<tr>
<td>Id</td>
<td>Title</td>
<td>Author</td>
</tr>
</table>

</template>

<script>
export default {
  name: "Main",
  data() {
    return {
      msg: null,
    };
  },
  props: {
    title: String,
  },
  created: function () {
    fetch("http://localhost:5000/sort/test")
      .then((response) => response.text())
      .then((data) => {
        this.msg = data;
      });
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
