# 调用系统搜索键盘

## 经过实际测试可以兼容 ios 和 Android 系统

**注意点：ios 上一定要在输入框外加下面这段话，否则无法系统键盘中无法显示”搜索“二字**

```
<form id="formid" action="#"><form>
```

**部分浏览器搜索框自带有叉号样式，请用以下代码去除**

```
input::-webkit-search-cancel-button {
                display: none;
            }
```
