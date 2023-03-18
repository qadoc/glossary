
# Spiral Model

中文全称：螺旋模型

螺旋模型由美国软件工程师巴里·勃姆于 1988 年 5 月在他的文章《[A Spiral Model of Software Development and Enhancement](https://liyunx.com/download/paper/A_Spiral_Model_of_Software_Development_and_Enhancement.pdf)》中提出。螺旋模型借鉴吸收了[快速原型模型](R/Rapid_Prototyping_Model.md)的原型迭代和[瀑布模型](W/Waterfall_Model.md)的生命周期阶段，采用一种周期性的方法来进行系统开发，引入了风险识别、风险分析和风险控制，属于风险驱动的开发模型。

![螺旋模型](https://img.liyunx.com/m1/TOIMGa8cec0714062519N.png)

两个维度：

- 半径：半径代表软件开发的累积成本。
- 角度：在每个螺旋周期内，螺旋线角度代表该周期的进度。

四个象限代表了一个螺旋周期的四个阶段：

- 左上：细化本迭代阶段的目标（如功能、性能、适应变化的能力等），明确备选方案以及应用备选方案的限制。
- 右上：对备选方案进行评估，识别并解决存在的风险，创建原型。
- 右下：当风险得到很好的分析与解决后，应用瀑布模型进行本阶段的开发与测试。
- 左下：评审当前和之前所有周期的产品、下一周期的计划（需求、开发、测试计划）以及执行所需资源，为了确保所有相关人员都为下一阶段做好准备。

软件开发活动的开始和结束：

- 开始：每个螺旋周期的开始都基于这样一个假设，特定的任务可以通过软件来改进，比如新的软件可以解决之前不能解决或暂未解决的问题或需求。
- 结束：在任何时候，如果这个假设没有通过测试（比如，因为开发延迟导致软件产品错过了它的市场窗口，或者是一个更好的商业产品出现了），螺旋过程就终止了。否则，当软件目标完成时终止，即已经没有特定的任务了。通常观察软件对任务的影响来验证假设。

**相关词条**

[软件开发测试模型](专题/软件开发测试模型.md)

**参考资料**

1. [螺旋模型 - Wikipedia](https://zh.wikipedia.org/wiki/%E8%9E%BA%E6%97%8B%E6%A8%A1%E5%9E%8B)
2. [螺旋模型 - 百度百科](https://baike.baidu.com/item/%E8%9E%BA%E6%97%8B%E6%A8%A1%E5%9E%8B/9817820)
3. [A Spiral Model of Software Development and Enhancement](https://liyunx.com/download/paper/A_Spiral_Model_of_Software_Development_and_Enhancement.pdf)