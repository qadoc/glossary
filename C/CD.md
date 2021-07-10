
# CD

## Continuous Delivery

中文全称：持续交付

持续交付是一种能力，即将所有类型（包括新特性、配置更改、Bug 修复和实验）的更改以一种**可持续**的方式**安全**、**快速**地交付到**生产环境**或用户手中。

持续交付的目标是让部署（无论是大规模分布式系统、复杂生产环境、嵌入式系统，还是应用程序）成为可预测的、按需执行的日常事务。

我们通过确保我们的代码始终处于可部署状态来实现这一切，即使面对上千名开发人员的团队也是如此。

### 持续交付的特点

1. 软件的更改是随时随地可交付的
1. 交付的软件是经过测试的、质量过关的
1. 交付前的所有阶段（构建、部署、测试）是自动化的

## Continuous Deployment

中文全称：持续部署

持续部署是持续交付的下一步，指的是代码通过自动评审以后，**自动部署到生产环境**。

持续部署的前提是能自动完成构建、测试、部署等步骤。

## CI、CD 区别

![](https://3lsqjy1sj7i027fcn749gutj-wpengine.netdna-ssl.com/wp-content/uploads/2015/12/409-images-for-snap-blog-postedit_image1.png)

虚线框内的 `TEST` 指单元测试。

持续集成示意图：自动完成单元测试、构建过程。

![](https://3lsqjy1sj7i027fcn749gutj-wpengine.netdna-ssl.com/wp-content/uploads/2015/12/409-images-for-snap-blog-postedit_image4-manual.png)

`TEST` 指测试环境。  
`STAGING` 指类生产环境。  
`PRODUCTION` 指生产环境。  

持续交付示意图：持续交付包含了 CI，另外自动完成非生产环境的测试并达到可交付状态。持续交付是一个业务行为，是否上线可根据业务决定，但可以有持续部署的能力，具体表现上：

1. 手动批准 + 手动部署
1. 手动批准 + 自动部署

![](https://3lsqjy1sj7i027fcn749gutj-wpengine.netdna-ssl.com/wp-content/uploads/2015/12/409-images-for-snap-blog-postedit_image3-auto.png)

持续部署示意图：持续部署是一个技术行为，软件更改会通过流水线自动部署到生产环境，即无须明确批准自动上线。

## 参考资料

1. [The Product Managers’ Guide to Continuous Delivery and DevOps](https://www.mindtheproduct.com/what-the-hell-are-ci-cd-and-devops-a-cheatsheet-for-the-rest-of-us/)
1. [What is Continuous Delivery?](https://continuousdelivery.com/)
1. [什么是持续交付？](https://amazonaws-china.com/cn/devops/continuous-delivery/)
1. [持续集成是什么？](http://www.ruanyifeng.com/blog/2015/09/continuous-integration.html)