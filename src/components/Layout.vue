<template>
  <section>
    <mu-appbar title="图像识别平台">
    </mu-appbar>
    <mu-row >
      <mu-col width="27" tablet="27" desktop="27" >
        <mu-list class="list-menu">
          <mu-list-item title="搜索">
            <mu-icon value="search" slot="right">
            </mu-icon>
          </mu-list-item>
          <mu-list-item title="图片训练库" :toggleNested="true">
            <mu-icon value="menu" slot="left">
            </mu-icon>
            <mu-list-item title="服装" slot="nested">
              <mu-icon value="shopping_basket" slot="left">
              </mu-icon>
            </mu-list-item>
          </mu-list-item>
          <mu-list-item>
          </mu-list-item>
        </mu-list>
      </mu-col>
    </mu-row>
  </section>
</template>
<style scoped>
  @import "../css/index.css";
</style>