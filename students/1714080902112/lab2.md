# 实验二：用例建模

## 1.实验目标

-学会使用StarUML画用例图

## 2.实验内容

-在StarUML画出和自己选题相关的用例图  
-完成实验报告

## 3.实验步骤

-将画出瑜伽爱好者、打卡功能、发布消息功能，再将瑜伽爱好者与打卡功能、发布消息功能相连  
-将图传到Github,完成实验报告

## 4.实验结果

![用例图](./Lab2-UseCaseDiagram.jpg)

图1：瑜伽交流社区的用例图

## 表1：打卡
用例编号  | UC01 | 备注 
-|:-|-  
用例名称  | 打卡  |  
前置条件  | 用户登入系统  | *可选*  
后置条件  |   | *可选*  
基本流程  | 1. 用户点击打卡按钮  |  
~| 2. 系统检查到今日未打卡  |  
~| 3. 打卡记录表进行打卡标记，提示打卡成功  |  
扩展流程  | 2.1 系统出错或网络断开，系统提示打卡失败  | *用例执行失败*  
~| 2.2 今日已打卡，提示请勿重复打卡  | *用例执行失败*  

## 表2：发布消息
用例编号  | UC02 | 备注 
-|:-|-  
用例名称  | 发布消息  |  
前置条件  | 用户登入系统  | *可选*  
后置条件  |   | *可选*  
基本流程  | 1. 用户点击发布信息按钮  |  
~| 2. 用户输入信息 |
~| 3. 系统检查到输入框不为空  |
~| 4.用户点击确认发布按钮 |
~| 5. 保存消息，提示发布消息成功  |
~| 6. 显示已发布的消息  |
扩展流程  | 3.1 系统检测到输入框为空，提示消息不能为空  | 
~| 5.1 系统出错或网络断开，系统提示发布消息失败 | *用例执行失败*  
