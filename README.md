# lazyload
图片懒加载，支持动态新增图片

## 使用非常简单

### 步骤一

修改需要懒加载的图片的属性，增加一个名称为lazyload的class

### 步骤二

并把图片的src设置成通用的loading图片或者空白占位符图片

### 步骤三

把图片的真实地址，写入图片的data-img中

经过以上三部，图片的html代码变成如下格式：

```html
//示例
<img src="loading.gif" data-img="a.jpg" class="lazyload">
```

### 步骤四

引入lazyload.js

### 步骤五

增加如下代码
```javascript:;
$.imgLazyLoad()
```
