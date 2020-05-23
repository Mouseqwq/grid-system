@media
早期CSS2用法
/* 打印的时候，页面文字是20px */
@media print {
body { font-size: 20px; }
}
/*屏幕展示的时候页面文字是16px */
@media screen {
body { font-size: 16px; }
}
@media
CSS3用法
/* 浏览器宽度小于等于990px时， 内部的CSS生效 */
@media screen and (max-width: 990px) {
body { font-size: 16px; }
}
/* 上面的写法可以如下简写 */
@media (max-width: 990px) {
body { font-size: 16px; }
}
/* 浏览器窗口宽度大于等于768时，内部CSS生效 */
@media (min-width: 768px) {
body { font-size: 16px; }
}