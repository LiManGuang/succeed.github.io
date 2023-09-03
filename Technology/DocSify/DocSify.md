#### DocSify使用教程

##### 1、安装

```
npm i docsify-cli -g
```

##### 2、初始化

```
docsify init ./docs
```

##### 3、预览网站

```
docsify serve docs
```

##### 4、侧栏

1. 在 `index.html` 中加入 `loadSidebar:true`

```
<!-- index.html -->

<script>
  window.$docsify = {
    loadSidebar: true
  }
</script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
```

2. 在网站根目录下创建 `_sidebar.md`

```
<!-- docs/_sidebar.md -->

* [Home](/)
* [Guide](guide.md)
```

