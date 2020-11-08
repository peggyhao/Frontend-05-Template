学习笔记
1.proxy是专门为底层库设计的这样一个特性。
强大也危险。
可以去对内置的一些操作，拦截甚至改变行为。
在使用了proxy之后，对象的可预测性降低。
2.vue的reactivity包
半成品的双向绑定
负责从数据到dom元素的一条线的监听，或者是到native的输入等。
3.mousemove和mouseup要监听在document上而不是draggable上，因为鼠标不小心移动太快了，会导致拖断的现象。
现代浏览器，监听在document上，可以捕捉鼠标，即使鼠标移出浏览器，也依然可以被捕捉到。
4.Range也属于DOM API的一部分。
实现一些视觉效果都离不开CSSOM。
