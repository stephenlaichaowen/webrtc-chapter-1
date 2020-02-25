# 學習筆記

## CSS 的 '*' 是甚麼意思 ?
所有 html 標籤元素

## video 標籤內的 playsinline 是甚麼意思呢 ?
是為了讓某些瀏覽器的預設全螢幕改成內聯播放。

## 把元素水平反轉的方法
transform: scaleX(-1);

## API


## 開啟攝影機的方法
```
navigator.mediaDevice.getUserMedia(options)
```
也可以用 `asysn/await`, 但是必須配合函式

## 關掉攝影機的方法
[MediaStreamTrack.stop()](https://developer.mozilla.org/en-US/docs/Web/API/MediaStreamTrack/stop)
