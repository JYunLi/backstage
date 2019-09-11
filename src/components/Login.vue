<template>
    <div class="login_container">
        <!-- 这是登录页面class      -->
        <div class="login_box">
        </div>
        <dir class="login_icon">

        </dir>
    </div>
</template>

<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<style lang="less" scoped>
    .login_container{
        height: 100%;
        // background: #2b4b6b;
    };
    .login_box {
      width: 450px;
      height: 300px;
      background-color: #fff;
      border-radius: 8px;
      position: absolute;
      left: 50%;
      top: 50%;
      transform: translate(-50%, -50%);
            
    }
</style>
