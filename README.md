# rxjs-observer

[Edit on StackBlitz ⚡️](https://stackblitz.com/edit/rxjs-observer)

## Functional Reactive Programming 简介

RxJS 指的是 Functional Reactive Programming extensions for JavsScript，


- Functional Reactive Programming 是一种编程思想，并不局限于某一个语言。这种思想的核心就是流，
- RxJS 中的使用的术语是 Observable，但是我觉得这个词不好理解，用流也就是 Stream 更好理解。
- 流代表的是一个随着时间而变化的序列，在这过程中，它可以产生值，或者错误，或者终止信号，只有这三种情况。
`
面向流的编程基本过程就是，创建代表原始输入的流，对它们进行组合、过滤等各种操作，最后生成我们感兴趣的结果流，监听结果流（subscribe）并进行相应操作即可，监听的时候提供三个函数，分别用于处理流产生了值，流产生了错误以及流结束这三种情况
`

[RxJS Marbles](https://rxmarbles.com/#from)