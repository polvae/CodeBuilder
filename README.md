# CodeBuilder
自动修改/翻新/混淆/OC/iOS代码，自动替换类名，方法名

## 点击查看[更新日志](./更新日志/README.md)

> ## 由来

网上有很多关于如何混淆iOS源码的方法，但是都不够智能，生成的方法类名要么千奇百怪，要么aaaabbbxxx这种完全毫无意义的名称，要么只能修改单个文件，多个文件根本无法关联，我就想有什么方法可以像真人一样去修改源码，符合语义，不是胡编烂造的方法名，还可以自动修改相关联的文件, 还能自己自定义单词库，于是就有了这个工具。

>划重点
#### 1. 该工具可以让你一键翻新代码，但是不是生成完整的xcode项目，需要你自己新建一个xcode项目，然后把翻新的文件拖入到新的项目中。
#### 2. 该工具只支持Object-C, 如果反响好的话，考虑添加swift或者其他语言支持.
#### 3. 虽然工具内置词库，但还是强烈建议配置自己的词库，达到最优的混淆效果。
#### 4. 因为GUI由Python编写，部分电脑上打开程序会慢一些或无反应，请多点击几次，耐心等待片刻，GUI不影响代码解析速度。
#### 5.软件开始运行时会清空目标文件夹内所有文件，请务必新建文件夹作为导出路径。

## 点击查看 [使用说明](./使用说明/README.md)

## 点击查看 [演示视频](https://v.youku.com/v_show/id_XNTkyMDQzMzg2OA==.html)
#### 其他.
###### 虽然工具本身经过了完整的商业项目的考验，但由于每个人的代码风格不一样，工具不可避免会出现解析不了的情况，开发者建议过滤C语言的文件，与第三方库，减少出错的可能性，还是无法运行成功，将源码与问题发到feedback_ios@yeah.net，或根据报错Log自行删减项目文件，其中利弊，自行斟酌。
有问题发邮件，发邮件，发邮件。发issue可能无法及时处理，谢谢。

![界面](./images/app_GUI.png)

>几个效果展示

![自动修改属性名](./images/effection_00.png)

![自动修改类名与文件名](./images/effection_01.png)

![自动修改方法名加局部变量](./images/effection_02.png)

![自动修改方法名加过滤](./images/effection_03.png)

![支持分类，支持方法内部局部变量名修改](./images/effection_04.png)

