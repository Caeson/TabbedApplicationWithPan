## 项目概述

本项目用于演示iOS中UITabbarController左右滑动切换。相关博客请参见[[iOS]iOS中UITabbarController左右滑动切换](https://blog.csdn.net/infant09/article/details/48773281)

## 运行步骤 

* clone整个项目，使用master分支: `git clone https://github.com/Caeson/TabbedApplicationWithPan`
* 使用xcode打开项目（已在Version 9.3 (9E145)版本测试通过）
* 使用模拟器运行即可

## 遗留问题

本项目目前存在一个已知bug：第一次从第一个页面左滑进入第二个页面，由于第二个页面加载存在问题，页面的约束并没有被加载；只有当第二个页面完全呈现后，会引起重新布局。目前本人不再以ios开发为主要工作，如果您有好的想法，请发起issue或pull request，谢谢！
