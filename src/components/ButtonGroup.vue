<template>
  <div class="table-pro-group-button content-item">
    <div class="table-pro-grou-button-main">
        <Button>Default</Button>
        <Button type="primary">Primary</Button>
        <Button type="dashed">Dashed</Button>
        <Button type="text">Text</Button>
    </div>
    <div class="table-pro-grou-button-util">
        <Poptip trigger="hover" width="12" content="刷新列表数据">
            <Icon size="20" type="md-refresh" />
        </Poptip>
        <Poptip trigger="hover" content="设置列表字段">
        <Icon size="20" type="ios-settings" />
        </Poptip>
        <Poptip trigger="hover" content="导出列表数据">
        <Icon size="20" type="md-download" />
        </Poptip>
        
    </div>
  </div>
</template>

<script>
export default {
  name: 'ButtonGroup',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.table-pro-group-button{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    flex-wrap: wrap;
}
.table-pro-group-button button{
    margin-right: 5px;
}
.table-pro-group-button i{
    margin-right: 5px;
}
.table-pro-grou-button-util{
    display: flex;
    align-items: center;
}
.table-pro-grou-button-util i:hover{
    background-color: #f3f3f3;
    cursor: pointer;
}
</style>
