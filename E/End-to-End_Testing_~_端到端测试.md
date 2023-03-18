
# End-to-End Testing

英文简写：E2E Testing  
中文全称：端到端测试，或 E2E 测试

在英文中，`End-to-End` 表示包括一个过程的所有阶段，在计算机中也表示一个应用程序工作所需的一切（包括它的依赖）。

端到端测试是一种软件测试方法，用于测试应用程序流是否自始至终都如预期一样正确。

端到端测试的目的是模拟真实的用户场景并验证被测系统及其组件的集成性和数据完整性。另一种说法是，端到端测试的目的是识别系统依赖关系，并确保在各种系统（包括外部依赖和多个内部系统）之间传递正确的信息。

![端到端测试](https://img.liyunx.com/m1/TOIMG0c9b00710013447N.png ':size=80%')

<!-- tabs:start -->

<!-- tab:水平端到端测试 -->

该测试要求测试者从模拟用户的角度出发，从头到尾完整地执行一个用户场景并验证，有时也叫全链路测试。比如，一个在电子商务平台购买商品的用户场景：

- 登录网站
- 输入商品关键字搜索商品
- 导航至商品详情页（也许您停下来阅读有关功能或产品规格的信息）
- 将所需的商品添加到购物车
- 点击“结算”
- 进入付款页面，选择支付方式
- 点击“提交”
- 完成购买
- 收到来自供应商的“谢谢”电子邮件

在多个应用程序（或多个子系统）中进行的水平端到端测试是与端到端测试最相关且使用最频繁的类型，当然水平端到端测试也可以在单个应用程序中进行。

**水平端到端测试的特点**

1. 在实际环境中执行，实际环境是指和正式环境保持一致性（应用版本、中间件版本、配置等）的环境。
2. 通常在完成任何应用程序的功能和系统测试之后执行。

**水平端到端测试的关键步骤**

作为一种测试方法，端到端测试由许多不同的部分组成，但是在设置端到端流程时将采取的最常见步骤如下：

- 查看您将使用端到端测试进行验证的要求
- 设置测试环境并概述硬件/软件要求
- 定义系统及其集成子系统的所有过程
- 描述每个系统的角色和职责
- 概述您计划使用的测试方法和任何测试标准（即语言，工具）
- 创建跟踪和设计测试用例的要求
- 列出每个系统的输入和输出数据

**水平测试的先决条件和优势**

对于水平测试，由于您要验证多个应用程序的整个工作流程，因此必须预先设置系统及其所有子系统的测试环境，这一点至关重要。

优点

- 高业务逻辑覆盖率
- 需要将测试重点放在用户角度（即从用户视角进行测试）
- 防止问题进入生产
- 对系统一切正常更有信心

<!-- tab:垂直端到端测试 -->

该测试要求对应用程序架构的每一层进行测试，有时也叫分层测试（测试金字塔）。

**垂直测试的先决条件和优势**

对于垂直测试，由于您将测试重点放在单个应用程序的体系结构上，因此需要测试或开发策略的支持，例如行为驱动的开发，测试驱动的开发或连续测试。您需要确保每个主要利益相关者（例如开发人员，测试人员，产品所有者）都参与该项目。

优点

- 高代码覆盖率
- 更快的测试执行
- 更集中的测试
- 对安全关键软件有用

<!-- tabs:end -->

**端到端测试实践**

1. [Testing on the Toilet: What Makes a Good End-to-End Test?](https://testing.googleblog.com/2016/09/testing-on-toilet-what-makes-good-end.html)

**参考资料**

1. [Meaning of end-to-end in English](https://dictionary.cambridge.org/us/dictionary/english/end-to-end)
1. [End-to-End Testing](https://www.tutorialspoint.com/software_testing_dictionary/end_to_end_testing.htm)
1. [How is End-to-End Testing Performed?](https://smartbear.com/learn/automated-testing/how-to-perform-end-to-end-testing/)
1. [END-To-END Testing Tutorial: What is E2E Testing with Example](https://www.guru99.com/end-to-end-testing.html)
1. [What is End-to-End (E2E) Testing? All You Need to Know](https://www.katalon.com/resources-center/blog/end-to-end-e2e-testing/)
1. [End to End Test Automation for Both Horizontal and Vertical Scale (Erdem Yildirim, Turkey)](https://www.youtube.com/watch?v=23-aghMoLg0)
1. [What Is End To End Testing: E2E Testing Framework With Examples](https://www.softwaretestinghelp.com/what-is-end-to-end-testing/)