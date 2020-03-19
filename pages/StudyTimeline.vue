<style scoped>
  .keyPoint{
    color: #2d8cf0;
    font-size: 16px;
    font-weight: bold;
  }
  .title{
    color: #2db7f5;
    font-size: 16px;
    font-weight: bold;
  }
  .content{
    padding-left: 12px;
  }
</style>

<template lang="pug">
  div
    Timeline(pending)
      TimelineItem
        p(class="keyPoint") 西南大学
        p(class="content") 自 2008 年 09 月 至 2015 年 6 月
      TimelineItem
        p(class="title") 新华中学
        p(class="content") 2005 年 09 月 至 2008 年 06 月
      TimelineItem
        p(class="keyPoint") 新华中学
        p(class="content") 自 2002 年 09 月 至 2005 年 06 月
      TimelineItem
        p(class="title") 小学
        p(class="content") 1996 年 9 月 至 2002 年 06 月
      TimelineItem
        p(class="keyPoint") 幼儿园
        p(class="content") 自 不详 月至 1996 年 06 月
</template>

<script>
export default {
  name: 'StudyTimeline'
}
</script>
