# 当你编码时

- [当你编码时](#当你编码时)
  - [听从你的直觉](#听从你的直觉)
  - [靠巧合编码](#靠巧合编码)
  - [算法效率](#算法效率)
  - [重构](#重构)
  - [易于测试的代码](#易于测试的代码)
  - [邪恶的向导](#邪恶的向导)

编码不是机械工作。每一分钟都需要做出各种决定，这些决定离不开深思熟虑。

## 听从你的直觉

直觉是针对各种模式的无意识回应。有些是天生的，有些是后天通过重复习得的。

直觉给你带来感受，而不是思考。

与直觉对话：

1. 放下手中的事情，清空自己的大脑，做些无需用脑的工作
2. 允许潜意识中的 idea 慢慢浮现
3. 如果潜意识没有帮助，试着表述你的问题/代码，向同事、向小黄鸭
4. 如果重述没有帮助，告诉自己现在做的东西无关紧要，只是个原型

## 靠巧合编码

你的代码应该依赖文档中的行为。如果没有文档，那么就要将你的假设写入文档。

不要靠巧合编码，你要深思熟虑为什么你的程序可以工作：

1. 总是意识到你在做什么，你能向一个初级工程师解释这段代码吗
2. 不要盲目编程，理解你的代码为何工作
3. 按计划行事
4. 依靠可靠的事物，不要依赖假设
5. 为你的假定建立文档
6. 不要只是测试你的代码，还要测试你的假定
7. 为你的工作划分优先级，把时间花在重要的方面（多数情况下，他们也是难点）
8. 不要做历史的奴隶，**不要受到即有代码的影响**

## 算法效率

估计代码使用的资源：时间、处理器、内存等等。

算法速率：大O表示法，估算你的算法的阶。

但是最好的并非总是最好的。

## 重构

无论代码出现下面哪些特征，都应该考虑重构代码：重复、非正交的设计、过时的知识、性能。

早重构，常重构。

重构时，不要同时增加功能；在开始重构之前，确保你拥有良好的测试，重构过程尽量采用短小的、深思熟虑的步骤。

## 易于测试的代码

测试不仅是为了寻找 bug，更是为了验证：

1. 设计
2. API
3. 解耦

单元测试：在隔离状态下，对每个模块进行测试。

针对合约进行测试，检测前后条件。要为测试而设计。

## 邪恶的向导

不要使用你不理解的向导代码。