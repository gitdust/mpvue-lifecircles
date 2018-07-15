<template>
  <div>
    TabBar0
    <a
      href="/pages/Page0/main">navigate Page0</a>
    <a
      open-type="redirect"
      href="/pages/Page0/main">redirect Page0</a>
    <a
      open-type="reLaunch"
      href="/pages/Page0/main">reLaunch Page0</a>
    <a
      href="/pages/TabBar1/main">goto TabBar1</a>
    <a
      open-type="redirect"
      href="/pages/TabBar1/main">redirect TabBar1</a>
    <a
      open-type="reLaunch"
      href="/pages/TabBar0/main">reLaunch self</a>
    <a
      open-type="reLaunch"
      href="/pages/TabBar1/main">reLaunch TabBar1</a>
  </div>
</template>

<script>
import card from '@/components/card'

export default {
  beforeCreate() {
    console.log('%cTabBar0 beforeCreate', 'color: #F9C22E');
  },
  created() {
    console.log('%cTabBar0 created', 'color: #F9C22E');
  },
  onLoad() {
    console.log('%cTabBar0 onLoad', 'color: #F9C22E');
  },
  onShow() {
    console.log('%cTabBar0 onShow', 'color: #F9C22E');
  },
  onReady() {
    console.log('%cTabBar0 onReady', 'color: #F9C22E');
  },
  onHide() {
    console.log('%cTabBar0 onHide', 'color: #F9C22E');
  },
  onUnload() {
    console.log('%cTabBar0 onUnload', 'color: #F9C22E');
  },
  beforeMount() {
    console.log('%cTabBar0 beforeMount', 'color: #F9C22E');
  },
  mounted() {
    console.log('%cTabBar0 mounted', 'color: #F9C22E');
  },
  beforeUpdate() {
    console.log('%cTabBar0 beforeUpdate', 'color: #F9C22E');
  },
  updated() {
    console.log('%cTabBar0 updated', 'color: #F9C22E');
  },
  beforeDestroy() {
    console.log('%cTabBar0 beforeDestroy', 'color: #F9C22E');
  },
  destroyed() {
    console.log('%cTabBar0 destroyed', 'color: #F9C22E');
  },
}
</script>

<style scoped>
.userinfo {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.userinfo-avatar {
  width: 128rpx;
  height: 128rpx;
  margin: 20rpx;
  border-radius: 50%;
}

.userinfo-nickname {
  color: #aaa;
}

.usermotto {
  margin-top: 150px;
}

.form-control {
  display: block;
  padding: 0 12px;
  margin-bottom: 5px;
  border: 1px solid #ccc;
}

</style>
