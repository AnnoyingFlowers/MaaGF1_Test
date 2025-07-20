<!-- markdownlint-disable MD033 MD041 -->

# MaaGF1_Test

</div>

---

**本仓库基于 [MaaFramework](https://github.com/MaaXYZ/MaaFramework) 所提供的项目模板创建，相关MaaFramework具体内容请直接访问该仓库，感谢参与了MaaFramework开发与维护的大佬们。**

**MaaGF1_Test** 为个人测试**少女前线（Steam版本）**的自动化脚本的仓库。由于创建者此前无开发经验、无代码学习历史，该项目可能存在结构混乱、逻辑复杂、可读性极差的屎山代码。如果不介意~~且勇于直面屎山~~，欢迎下载讨论交流学习。

按照少女前线官方的说明，只要是脚本就存在被封号可能，**账号风险由个人判断，本人不承担任何的相应后果。**

>_截止2025.07.20，本人在22年一年纯脚本（按键精灵+模拟器）跑了万把13-4的账号仍健在。_

---

## 脚本说明

### 通用

> 0.（图示将来有空闲时或许会嵌入）
>
> 1.游戏**分辨率**=1680\*1050。
>
> 2.Maa在调用win32的鼠标移动指令时会导致鼠标被移走，意味着此时你无法操作你的电脑。如果屎山代码进入死循环请多次按下 Win + ↓ 直至窗口缩放到最小。（如果有类似按键精灵后台点击的方法还请告诉我）
>
> 3.执行脚本前请阅读相关该脚本的说明
>
> 4._（临时）由于还没学会封装该程序，所以目前的所有脚本均通过[MaaDebugger](https://github.com/MaaXYZ/MaaDebugger)进行测试。_
>
> 5._（临时）我个人在使用MaaDebugger调试时选项如下：_

    Screencap Method = Screencap_GDI

    Input Method = Input_Seize

> 6._(临时)请下载pre-release里的版本，直接下载源码zip会导致文件有缺失无法运行。如需更新请下载源码zip并覆盖（应该管用）_

---

## 现已支持：

> ##### 8-1N双Zas炸狗

> > 见[8-1N双Zas炸狗使用手册](https://github.com/LeonNagant/MaaGF1_Test/blob/main/manual/8-1N%E5%8F%8CZas%E7%82%B8%E7%8B%97%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.md)
>
> ---
>
> ##### 13-4双维克托拖尸
>
> > 见[13-4双维克托拖尸使用手册](https://github.com/LeonNagant/MaaGF1_Test/blob/main/manual/13-4%E5%8F%8C%E7%BB%B4%E5%85%8B%E6%89%98%E6%8B%96%E5%B0%B8%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.md)
>
> ---
>
> ##### 兵棋自动挂机
>
> > 见[兵棋自动挂机使用手册](https://github.com/LeonNagant/MaaGF1_Test/blob/main/manual/%E5%85%B5%E6%A3%8B%E8%87%AA%E5%8A%A8%E6%8C%82%E6%9C%BA%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.md)

---

### 其他功能开发中...

---

## 开发日志



### 2025.07.20（V0.3.0.20250720）

> 0.修复若干bug
>
> 1.增加13-4双维克托拖尸及其[说明书](https://github.com/LeonNagant/MaaGF1_Test/blob/main/manual/13-4%E5%8F%8C%E7%BB%B4%E5%85%8B%E6%89%98%E6%8B%96%E5%B0%B8%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.md)
>
> 2.增加[MaaDebugger的一些个人使用建议](https://github.com/LeonNagant/MaaGF1_Test/blob/main/manual/MaaDebugger%E7%9A%84%E4%B8%80%E4%BA%9B%E4%B8%AA%E4%BA%BA%E4%BD%BF%E7%94%A8%E5%BB%BA%E8%AE%AE.md)

### 2025.07.19（TestV0.2.0.20250719）

> 0.修复若干bug
>
> 1.增加PVE兵棋挂机功能及其说明

---

### 2025.07.18（TestV0.1.2.20250718）

> 0.模块化代码
>
> 1.对8-1N地图点击梯队时莫名其妙长按进入梯队预览界面导致地图移位，后续无法识别的问题打上补丁
>
> 2.修改了宿舍点赞脚本，本希望能领14电，但因为精度不足故暂且放弃
>
> 3.修复了装备强化时卡在点击确定的bug
>
> 4.增加了8-1N的使用说明[8-1N双Zas炸狗使用手册](https://github.com/LeonNagant/MaaGF1_Test/blob/main/manual/8-1N%E5%8F%8CZas%E7%82%B8%E7%8B%97%E4%BD%BF%E7%94%A8%E6%89%8B%E5%86%8C.md)

_测试用的笔记本电脑坏了，调试速度会慢，更新可能受到影响:(_

---

### 2025.07.15（TestV0.1.0.20250715）

> 0.完成8-1N双Zas拖尸、宿舍点赞、点击宿舍内人形爱心的json编写（屎山）。
>
> 1.由于还没学会封装该程序，所以目前的所有脚本均通过[MaaDebugger](https://github.com/MaaXYZ/MaaDebugger)进行测试。

---

有问题或者建议请提issue或联系邮箱 *2554766922@qq.com* ，我会重视每一条反馈。
