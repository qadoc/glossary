
# Waterfall Model

中文全称：瀑布模型

1970 年，Winston Royce 博士在借鉴其他工程领域思想的基础上，比如建筑工程，在论文 《[Managing the Development of Large Software Systems](https://liyunx.com/download/paper/Managing_the_Development_of_Large_Software_Systems.pdf)》 中提出了一个开发模型。该模型指出软件开发应有完整的周期，软件开发过程可以分为若干个阶段，各阶段之间有明确的线性顺序，完成上一阶段后继续下一阶段。

![](https://img.liyunx.com/m1/TOIMG8473a0711065847N.png ':size=80%')

因为测试只在最后阶段发生，所以 Royce 认为该模型存在风险并可能导致失败，于是在论文中的后面部分提出了一些改进模型。尽管这些改进并未成为主流，但也可以看出 Royce 并非是在倡导软件开发应当采用当今大家熟悉的瀑布模型，而是提出关于软件开发模型的一些思路。

上面的开发过程图在后来经常被用来解释 “瀑布模型”，因此这篇论文也被视作 “瀑布模型” 概念的起源。要说明的一点是，论文中并没有使用 “瀑布” 一词，即 “瀑布模型” 这个词语不是 Royce 提出的，因为这个开发模型像瀑布流水一样从上到下，所以取名 “瀑布模型”。

现在我们所说的瀑布模型，是一个严格、顺序、单次的瀑布生命周期，一个生命周期包含项目活动的多个阶段，从需求分析、软件设计、程序编码、软件测试到运行维护，每一个阶段都依赖于前一个阶段的成果。

![](https://img.liyunx.com/m1/TOIMGa93b40711075824N.jpeg)

**瀑布模型的特点**

- 每个阶段严格有序。
- 生命周期一般只有一次，所以每个阶段的时间较长。

**瀑布模型的优点**

- 简单易行。
- 各阶段划分清晰：可按照阶段检查及时发现问题，前一阶段完成便可重点关注下一阶段。
- 有很好的分工协作，易于确定开发周期中的关键点。
- 对质量有保障。

**瀑布模型的缺点**

- 难以响应需求的变更，当需求发生改变时，越到后期代价越大。
- 工作量分布不均衡，例如开发前期测试人员无法参与，而开发后期测试人员又特别忙碌。
- 前期进度受阻，会一直压缩后续阶段时间，导致延期或影响质量。
- 问题在后期才容易暴露，结果只能最后阶段才能看到。

**瀑布模型的应用场景**

- 适用于要求明确且不模棱两可的项目。
- 可在迭代模型中应用瀑布模型。

**相关词条**

[软件开发测试模型](专题/软件开发测试模型.md)

**参考资料**

1. [软件工程之瀑布模型](https://blog.si-yee.com/2019/10/03/%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E4%B9%8B%E7%80%91%E5%B8%83%E6%A8%A1%E5%9E%8B/)
2. [Waterfall model - Wikipedia](https://en.wikipedia.org/wiki/Waterfall_model)
3. [Managing the Development of Large Software Systems](https://liyunx.com/download/paper/Managing_the_Development_of_Large_Software_Systems.pdf)
4. [回顾 Winston Royce 的瀑布模型](https://www.jianshu.com/p/5a55387ddede)
5. [SDLC - Waterfall Model](https://www.tutorialspoint.com/sdlc/sdlc_waterfall_model.htm)

