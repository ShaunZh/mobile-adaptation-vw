使用vw进行适配，其原理与使用rem进行适配时是一致的，只不过vw是css直接支持了，而rem需要我们根据视口大小来动态调整html font-size来实现布局；

vw视口单位会根据视口的大小来计算的;

例如，在桌面端浏览器视口尺寸为650px，那么 1vw = 650 * 1% = 6.5px（这是理论推算的出，如果浏览器不支持0.5px，那么实际渲染结果可能是7px）。

参考资料：
- [利用视口单位实现适配布局](https://aotu.io/notes/2017/04/28/2017-4-28-CSS-viewport-units/index.html)
- [再聊移动端页面的适配](https://www.w3cplus.com/css/vw-for-layout.html)
