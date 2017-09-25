# VueImgSlider

> A simple Img slider component

  - 提供简单跑马灯效果
  - 循环无间歇滚动
  - 水平和垂直


>[demo](https://hk-kevin.github.io/vueImgSlider/)

## 如何使用

```
 <vue-img-slider
      style="width: 400px;height: 400px;"
      :type="'left'"  //跑马灯方向
       margin="'20px'" //每张图片的间隔
       :speed="20"    //图片华东的速度
      :imgData="demoData" //图片和文字数据
      :txtPos="['40%','10%']" //图片文字位置
    >
 </vue-img-slider>

  demoData: [
           {
             img: 'http://f12.baidu.com/it/u=1981748892,3031683197&fm=72',
             title: '图片1'
           },
           {
             img: 'http://f10.baidu.com/it/u=3243370105,1125765815&fm=72',
             title: '图片2'
           }]
```


## 例子
``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
