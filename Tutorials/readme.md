# RxJS/ Tutorials

http://reactivex.io/

ReactiveX

An API for asynchronous programming
with observable streams


https://github.com/Reactive-Extensions/RxJS


http://courses.ultimateangular.com/courses/hello-rxjs/lectures/1605093


https://www.youtube.com/watch?v=5CTL7aqSvJU



函数式反应型编程(FRP) : Functional Reactive Programming


最近对FRP感兴趣，在项目中用了用RxJS，分享一下并不深刻的感受。
RxJS全名Reactive Extensions for JavaScript，Javascript的响应式扩展。
响应式的思路是把随时间不断变化的数据、状态、事件等等转成可被观察的序列(Observable Sequence)，然后订阅序列中那些Observable对象的变化，一旦变化，就会执行事先安排好的各种转换和操作。
RxJS作为一个库，可以和任何框架混用，如果想体验一下函数响应式编程的奇妙之处不妨一用。



Functional Reactive Programming

上面两例中X风格的代码主要描述系统中数据(消息)流的结构关系，至于环境变化如何导致某些数据流变化，这些变化了的数据流又如何导致其它的相关数据流变化，压根儿不需要关心。这是一种编程范式，称之为Reactive Programming。

而主要利用函数式编程(Functional Programming)的思想和方法(函数、高阶函数)来支持Reactive Programming就是所谓的Functional Reactive Programming，简称FRP。

现在可以给X正名了，它就是FRP。









