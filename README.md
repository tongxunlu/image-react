＃uni-app-小程序图片实现拖动缩放旋转的插件
模仿火花思维小程序海报生成前的制作个性化海报
https://ext.dcloud.net.cn/plugin?id=5156
最新日期是2023-07-04
# fy-poster

## 属性说明

|属性名|类型|默认值|说明|
| -- | -- | --|--|
| posterPicUrl | String | '' | 可滑动缩放的图片 |
| posterBgImageURL | String | ‘’ | 图片覆盖的透明背景图 |
| width | String | ‘’ | 图片拖动旋转缩放的区域 |



## 使用示例

```html
	//基础用法
	<poster posterPicUrl='https://fuss10.elemecdn.com/e/5d/4a731a90594a4af544c0c25941171jpeg.jpeg'></poster>
	
```

```javascript
import poster from '@/components/fy-poster/poster.vue'
export default {
  components: {
    poster
  }
}
```
