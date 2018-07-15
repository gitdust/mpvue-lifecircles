<template>
  <div>
    TabBar1
    <a
      href="/pages/Page2/main">navigate Page2</a>
    <a
      href="/pages/TabBar0/main">navigate TabBar0</a>
    <a
      open-type="redirect"
      href="/pages/TabBar0/main">redirect TabBar0</a>
  </div>
</template>

<script>
import card from '@/components/card'

export default {
  beforeCreate() {
    console.log('%cTabBar1 beforeCreate', 'color: #53B3CB');
  },
  created() {
    console.log('%cTabBar1 created', 'color: #53B3CB');
  },
  onLoad() {
    console.log('%cTabBar1 onLoad', 'color: #53B3CB');
  },
  onShow() {
    console.log('%cTabBar1 onShow', 'color: #53B3CB');
  },
  onReady() {
    console.log('%cTabBar1 onReady', 'color: #53B3CB');
  },
  onHide() {
    console.log('%cTabBar1 onHide', 'color: #53B3CB');
  },
  onUnload() {
    console.log('%cTabBar1 onUnload', 'color: #53B3CB');
  },
  beforeMount() {
    console.log('%cTabBar1 beforeMount', 'color: #53B3CB');
  },
  mounted() {
    console.log('%cTabBar1 mounted', 'color: #53B3CB');
  },
  beforeUpdate() {
    console.log('%cTabBar1 beforeUpdate', 'color: #53B3CB');
  },
  updated() {
    console.log('%cTabBar1 updated', 'color: #53B3CB');
  },
  beforeDestroy() {
    console.log('%cTabBar1 beforeDestroy', 'color: #53B3CB');
  },
  destroyed() {
    console.log('%cTabBar1 destroyed', 'color: #53B3CB');
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
