<template>
  <div class="topNav">
    <div class="topleft">
      <svg class="icon" aria-hidden="true">
        <use xlink:href="#icon-caidan1"></use>
      </svg>
    </div>

    <div class="topContent">
      <span @click="$router.push('/infoUser')">我的</span>
      <span class="active">发现</span>
      <span>云村</span>
      <span>视频</span>
    </div>
    <div class="topRight">
      <svg class="icon" aria-hidden="true" @click="$router.push('/Search')">
        <use xlink:href="#icon-sousuo1"></use>
      </svg>
    </div>
  </div>
  
</template>
<style lang="less" scoped>
    .topNav{
        width: 100%;
        height: 1rem;
        padding: .2rem;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .topContent{
            width: 65%;
            height: 100%;
            display: flex;
            justify-content: space-around;
            // align-items: center;
            font-size: .36rem;
            .active{
                font-weight: 900;
            }
        }
    }
</style>