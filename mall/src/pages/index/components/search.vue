<template>
  <div class="dSearch">
    <div class="iconLf">
      <i class="iconfont">&#xe7f9;</i>
      <p>分类</p>
    </div>
    <div class="inSearch">
      <div class="inWrap">
        <i class="iconfont">&#xe611;</i>
        <input type="text" placeholder="请输入搜索关键词" />
      </div>
    </div>
    <div class="iconRt">
      <i class="iconfont">&#xe61b;</i>
      <p>购物车</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'homeSearch'
}
</script>

<style scoped lang="scss">
.dSearch {
  flex-direction: row;
  margin-bottom: rpx(20);
  .iconLf, .iconRt {
    width: 20%;
    flex-direction: column;
    font-size: .2rem;
    color: #7c801c;
  }
  .inSearch {
    flex: 1;
    background-color: rgba(152, 191, 61, 0.44);
    border-radius: rpx(30);
    color: white;
    padding: 0 rpx(30);
    div {
      flex-direction: row;
      input {
        margin: rpx(10) rpx(20);
        font-size: .3rem;
      }
    }
  }
}
.dSearch, .iconLf, .iconRt, .inWrap {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
