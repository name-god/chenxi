<template>
  <div class="page_hg_header">
    <div class="page_hg_header_img">
      <img src="../../assets/images/home_logo.png" alt />
    </div>
    <div class="page_hg_header_right">
      <router-link to="search" tag="a" class="page_hg_header_put">
        <input type="text" />
        <i class="iconfont icon-fangdajing" style="color:#000;"></i>
      </router-link>
      <router-link to tag="a" class="page_hg_header_car">
        <i class="iconfont icon-shop"></i>
      </router-link>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style lang="scss">
.page_hg_header {
  padding: 10px;

  background-color: #e7e7e9;
  display: flex;
  align-items: center;

  &_img {
    width: 33.3%;
    height: 45px;
  }
  &_right {
    width: 66.6%;
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
  &_put {
    width: 70%;
    display: flex;
    input {
      border: 1px solid #ccc;
      flex: 1;
      border-radius: 20px;
      height: 35px;
      background-color: #fff;
      position: relative;
    }
    i {
      position: absolute;
      top: 19px;
      right: 69px;
      font-size: 25px;
    }
  }
  &_car {
    i {
      font-size: 25px;
    }
  }
}
</style>
