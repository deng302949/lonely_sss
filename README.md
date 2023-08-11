无聊刷刷算法题
  1. 最长子串，leetcode.3
  思路：
  ```
    比如abcdeabcd
    1.abcde rk =5 ans = 5
    2.bcdea rk =6 ans = 5
    3.cdeab rk =7 ans = 5
    4.deabc rk =8 ans = 5
    5.eabcd rk =9 ans = 5
    6.abcd rk =10 ans = 4
    7.bcd rk =11 ans = 3
    8.cd rk =12 ans = 2
    9.d rk =13 ans = 1
  ```

react优化监听 React Profiler
关键词
Purpose: React profiler是一个性能测量工具，帮助你分析React组件，识别瓶颈，减少不必要的重复渲染
Built in profiler:React dev-tools有一个内置的分析器，它提供了一个可视化的界面来分析组件的渲染性能。您可以将react分析器与开发工具分析器结合使用
Profiler :该分析器组件可用于度量特定组件的性能。分析器组件也可以嵌套。Profiler有两个道具:id和onRenderCallback函数
onRenderCallback:  onRenderCallback是一个传递给 组件的函数。它返回可用于度量性能的各种性能指标
阮一峰：如何读懂火焰图？
