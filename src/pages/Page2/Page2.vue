<template>
  <div>
    Page2
    <a
      open-type="navigateBack"
      :delta="0"
      href="/pages/Page0/main">navigateBack delta 0</a>
    <a
      open-type="navigateBack"
      :delta="-1"
      href="/pages/Page0/main">navigateBack delta -1</a>
    <a
      open-type="navigateBack"
      :delta="-20"
      href="/pages/Page0/main">navigateBack delta -20</a>
    <a
      open-type="switchTab"
      href="/pages/TabBar0/main">switchTab TabBar0</a>
  </div>
</template>

<script>

export default {
  name: 'Page2',
  beforeCreate() {
    console.log('%cPage2 beforeCreate', 'color: #502274');
  },
  created() {
    console.log('%cPage2 created', 'color: #502274');
  },
  onLoad() {
    console.log('%cPage2 onLoad', 'color: #502274');
  },
  onShow() {
    console.log('%cPage2 onShow', 'color: #502274');
  },
  onReady() {
    console.log('%cPage2 onReady', 'color: #502274');
  },
  onHide() {
    console.log('%cPage2 onHide', 'color: #502274');
  },
  onUnload() {
    console.log('%cPage2 onUnload', 'color: #502274');
  },
  beforeMount() {
    console.log('%cPage2 beforeMount', 'color: #502274');
  },
  mounted() {
    console.log('%cPage2 mounted', 'color: #502274');
  },
  beforeUpdate() {
    console.log('%cPage2 beforeUpdate', 'color: #502274');
  },
  updated() {
    console.log('%cPage2 updated', 'color: #502274');
  },
  beforeDestroy() {
    console.log('%cPage2 beforeDestroy', 'color: #502274');
  },
  destroyed() {
    console.log('%cPage2 destroyed', 'color: #502274');
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
