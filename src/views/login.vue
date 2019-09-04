<template>
  <div>
    <van-nav-bar
      title="标题"
    />
    <van-cell-group>
        <van-field
         v-model="username"
         clearable
         right-icon="question-o"
         placeholder="请输入手机号码"
         />
        <van-field
           v-model="password"
           type = "password"
           placeholder="请输入密码"
        />
    </van-cell-group>
    <div class="btn">
        <van-button
         type="info"
         size="large"
         >登录</van-button>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {}
  },
  methods: {

  }
}
</script>

<style lang = "less" scoped>
.btn {
    padding: 20px;
}
</style>
