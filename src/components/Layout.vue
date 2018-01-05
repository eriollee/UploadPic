<template>
  <section>
    <mu-appbar title="图像识别平台" :zDepth="2">
      <mu-icon value="settings_input_svideo" color="#0091ea" slot="left">
      </mu-icon>
    </mu-appbar>
    <mu-row :column="2">
      <mu-col width="25" tablet="25" desktop="25" class="row-left ">
        <mu-list class="list-menu">
          <mu-list-item title="搜索" class="menu-active">
            <mu-icon value="av_timer" slot="left">
            </mu-icon>
          </mu-list-item>
          <mu-list-item title="图片训练库" :toggleNested="true">
            <mu-icon value="art_track" slot="left">
            </mu-icon>
            <mu-list-item title="服装" slot="nested">
              <mu-icon value="border_color" slot="left">
              </mu-icon>
            </mu-list-item>
            <mu-list-item title="手机" slot="nested">
              <mu-icon value="folder" slot="left">
              </mu-icon>
            </mu-list-item>
          </mu-list-item>
        </mu-list>
      </mu-col>
      <mu-col width="75" tablet="75" desktop="75">
        <mu-row :column="1">
          <mu-col width="100" tablet="100" desktop="100">
            <mu-sub-header>
              仪表盘
            </mu-sub-header>
          </mu-col>
        </mu-row>
      </mu-col>
    </mu-row>
  </section>
</template>

<style scoped>
  @import "../css/index.css";
</style>
