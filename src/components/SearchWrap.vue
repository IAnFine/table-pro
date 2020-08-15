<template>
  <div class="table-pro-search-wrap content-item">
        <Input search enter-button="Search" placeholder="Enter something..." />
  </div>
</template>

<script>
export default {
  name: 'SearchWrap',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.table-pro-group-button button{
    margin-right: 5px;
}
</style>
