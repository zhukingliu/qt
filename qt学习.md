# 1 修改Windows版Qt Creator界面字体
## 创建样式文件
创建CSS文件，内容如下:

```css
QWidget {
    font: 10pt "Segoe UI Semibold";
}
```

```
10pt: 字体大小
"Segoe UI Semibold": 字体名称
```

在后面追加创建的CSS文件: –stylesheet=CSS文件完整路径，注意stylesheet前面是两个-
例如: C:\Qt\qtcreator-4.13.3\bin\qtcreator.exe --stylesheet=C:\Qt\qtcreator-4.13.3\custom-style.css
