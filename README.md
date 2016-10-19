## 文本溢出处理
```
单行处理
```
```
overflow: hidden;
text-overflow: ellipsis;
white-space: nowrap;
```
```
多行处理（谷歌内核和移动端支持而已）
```
```
display: -webkit-box;
-webkit-box-orient: vertical;
-webkit-line-clamp: 3;
overflow: hidden;
```