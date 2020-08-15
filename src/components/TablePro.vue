<template>
    <Card>
        <div class="table-pro-main-content" style="min-height: 200px;">
            <ButtonGroup />
            <SearchWrap />
            <TableWrap />
        </div>
    </Card>
</template>

<script>

import ButtonGroup from './ButtonGroup';
import SearchWrap from './SearchWrap';
import TableWrap from './TableWrap';

export default {
  name: 'TablePro',
  components: {
    ButtonGroup,
    SearchWrap,
    TableWrap
  }
}
</script>

<style scoped>
.layout{
    border: 1px solid #d7dde4;
    background: #f5f7f9;
    position: relative;
    border-radius: 4px;
    overflow: hidden;
}
.layout-logo{
    width: 100px;
    height: 30px;
    background: #5b6270;
    border-radius: 3px;
    float: left;
    position: relative;
    top: 15px;
    left: 20px;
}
.layout-nav{
    width: 420px;
    margin: 0 auto;
    margin-right: 20px;
}
.layout-footer-center{
    text-align: center;
}

.table-pro-main-content{
  display: flex;
  flex-direction: column;

}

.table-pro-main-content .content-item{
  margin: 0 0 10px 0 ;
}
</style>