# 01 JavaScript Drum Kit

## 实现效果

模拟一个打鼓的页面。用户在键盘上按下 ASDFGHJKL 这几个键时，页面上与字母对应的按钮变大变亮，对应的鼓点声音响起来。

## 关键要点

1. 键盘事件
   a.如何获得对应的keyCode,
   b.键盘对应的 keydown,keypress,keyup事件
2. 播放声音
   a.声音文件的播放（audio.paly()）
   b.声音文件的停止（audio.pasue();allAudio[i].currentTime = 0）
3. 改变样式
   a.通过keyCode获取对应的dom节点
   b.通过键盘事件增加或者删除相应的样式（palying）
