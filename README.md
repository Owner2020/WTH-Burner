# WTH-Burner
适用于小型 Vorons 的缩小版 Stealthburner

![](pictures/WTH_Burner.png)
 <img src="pictures/V24.jpg" width="30%"/>  <img src="pictures/print.jpg" width="50%"/>

### 正在进行的工作

这仍在进行中，还没有准备好打印，但我认为我可以已经启动 Repo 来收集一些信息。所以 Wth-Burner 的一些规格：

80% 缩放的 Stealthburner 适合像 V0 这样的微型 Vorons（更多信息见下文）
4020 用于部分冷却（如从加力燃烧室）和 3007 用于热端冷却
CW2 挤出机，具有合适的内部结构，以适应小尺寸
全尺寸喷嘴 LED - 与他的大哥相同（徽标 LED 在待办事项上）
与 Phaethus Dragon、Red lizard 和 Dragonfly-BMO 兼容（由于空间狭小，我会推荐陶瓷加热器）
重量 265 克（Phaethus Dragon SF + 17 毫米 10T Moons）


#### 进展

##### 30.07.2023 - CAD Beta Release (B1)

30.07.2023 - CAD 测试版 （B1）
由于对 WTH-Burner 的高度兴趣，我决定发布 CAD 文件 - 我仍然想改进各种东西，所以还没有任何 STL。您可以将 CAD 用作任何要在 :) 上使用 WTH 燃烧器的参考我将在下一次更新中制作一个受 V0.2 安装孔限制较少的定制 X-Carriage - 我还必须在这里和那里修复壁厚，并在热端周围增加一些空间（Red Lizard K1 Pro 似乎是这个小空间的最佳解决方案）。不过，主程序集应该是功能性的。

##### 11.06.2023 - 将 Dragon 换成 Red Lizard，陶瓷加热器似乎是这个小空间的更好选择
 <img src="pictures/IMG_2882.jpg" width="49%"/>  <img src="pictures/IMG_2883.jpg" width="49%"/>

##### 5.06.2023 - 首次使用 MGN9h 进行测试安装，仍在等待我的 MGN7h
 <img src="pictures/IMG_2895.jpg" width="49%"/>  <img src="pictures/IMG_2907.jpg" width="49%"/>

### CAD 预览

这只是一个 Web 预览，一旦我确认它:)工作正常，我将共享所有文件

Link: https://a360.co/43DYPun


### 有什么问题?

...Y 行程。Wth-Burner 比 Mini SB 厚 9 毫米，这可能会限制 Y 轴行程。

#### Voron V0.2

当喷嘴位于最前部时，[V0.2](https://github.com/VoronDesign/Voron-0) 与前面板的间隙为 ~1 毫米。这意味着您将损失 8 毫米的 Y 形行程 - 只有您才能判断是否打印到床的最边缘

##### 解决方案：Pandora Gantry:

一个非常简单的解决方案是 Pandora Gantry，它为您提供更多的 Y 行程。 [Pandora Gantry](https://github.com/MasturMynd/Pandora), 这样，您应该没有任何空间限制 （untested）。我将在我的 V0 中使用 Pandora Gantry，因此一旦我完成构建，我将能够确认这一点。

#### Voron Micron

[Micron](https://github.com/PrintersForAnts/Micron) 的 Y 行程比需要的要多一点 - 据我从 CAD 中可以看出，一旦我构建了我的，我将不得不看看它如何适用于真实的东西。


1: Stealthburner - Wth-Burner - Mini-Stealthburner |  2: Wth-Burner - Mini SB |  3: Wth-Burner in TriBall (my V0 with kinematic triple z)
:-------------------------:|:-------------------------:|:-------------------------:
![](pictures/Render.PNG)  |  ![](pictures/comp_mini.png)  |  ![](pictures/WTHBurner_TriBall.png)
