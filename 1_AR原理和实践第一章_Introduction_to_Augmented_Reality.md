# 1. AR原理和实践  第一章Introduction to Augmented Reality

*第一章主要讲解了什么是AR，和其他技术的关系，在各行各业中应用和发展的历史*

## 定义

最近**VR(Virtual Reality)**技术和产品变得极其火爆，它将各种计算机生成的媒体映射在一个封闭的虚拟空间里，同时也让人(至少是眼睛)置身其中享受虚拟世界的美好。但是VR技术有着天生的限制，那就是与现实的切割感。我们日常使用手机和电脑也是一样，虽然它们呈现了很多来自现实的情报，但我们需要通过通过非直接(indirectly)的手段来获取，换句话说人们需要付出额外的**认知努力**。(cognitive effort)来使用他们。 *当你打开电脑看新闻时，你需要点击链接。当你去餐馆用支付宝点餐时，你需要打开手机进行扫码，指纹支付等操作等。而且每次的交互需要操作者在现实-虚拟两个互相隔离的世界中不停地转换，不够直接和自然。作者(我也)认为我们还能做得更简单，更自然。这些烦琐的交互不仅需要付出一定的认知努力，还降低了交互的效率(对于终端消费者来说比起转了几个弯的经销商代理销售还是厂家直销更有吸引力吧？)。我自己认为终极的AR应该是没有学习过程的，只需要拥有现实世界的基本生活技能就能自然的操作和运用。*

AR技术就是想要创造一个在虚拟世界和现实世界之间直接，自动和动态的交互界面。目前比较广泛接受的对VR的定义是：

- **虚拟和现实的结合**
- **即时互动(interactive)**
- **存在于3d空间(registered in 3D)** *我的理解是技术上第一项的结合必须是在同一坐标系里，object必须对准*

看到了吗，关于AR眼镜什么的设备完全没有提及，甚至这不一定要来自视觉，这和我们一般对AR的印象并不相同。

关于互动，使用者持续享受着AR场景和体验，这些信息又会作为输入来更新场景。这被称为**基于位置的可视化(situated visualization)**

一个AR系统最少需要包含3个要素，如图：

- **跟踪**
- **对准**
- **可视化**
- **(4)空间**

(4)指的是存储前三要素的数据库模型

![Untitled](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled.png)

另外一些娱乐媒体造成人们从对AR的定义有一些误解，比如侏罗纪公园其实和AR并没有什么关系。1，恐龙都是完全靠电脑合成的虚拟信息(非现实信息)；2，看电影这个行为缺乏互动(interactive)。

## AR发展简短历史

*太长太多。。挑着写。没图的太难理解了直接跳过*

*Ivan Sutherland* 可以说是AR/VR之父，他于1968年发明了世界第一款VR系统。这款设备已经具备头部追踪和透视光学系统。

![Untitled 1](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%201.png)

随着80，90年代计算机性能的快速发展，AR技术也开始真正被应用开来。1992年被称为AR的元年。 *国内搞营销的恐怕不同意哈哈。 Caudell ，Mizell将*AR应用于帮助技术人员装配线缆。1993年也有类似的技术帮助理解如何拆卸和装配某设备![Untitled 2](C:%5CUsers%5Cfan%20baby%5CDesktop%5Cmarkdown%5Cmarkdown_rep%5C1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality%5CUntitled%202.png)

![Untitled 3](C:%5CUsers%5Cfan%20baby%5CDesktop%5Cmarkdown%5Cmarkdown_rep%5C1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality%5CUntitled%203.png)



还有通过AR来模拟孕妇肚子里胎儿的情况。*有点恶心*

![Untitled 4](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%204.png)

1996年世界第一款合作型(collaborative )AR系统被用来用于地理教学。复数使用者各自带上HMD，看到的是不同角度上同样的AR场景。

![Untitled 5](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%205.png)

1997-2001年日本政府和佳能共同开设了Mixed Reality Systems Laboratory 研究AR

![Untitled 6](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%206.png)

1997年*Feiner*开发了第一款户外AR系统，同时使用了HMD和GPS来追踪定位。因为需要大算力来呈现AR图像，使用者需要将计算系统背在后背。

![Untitled 7](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%207.png)

1998年*Thosmas*发布了一款户外AR导航系统，但这款系统真正被知道是因为被用来开发了ARQuake (AR版雷神之锤)，人们从此可以在自己的停车场里杀僵尸了。

![Untitled 8](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%208.png)

1999年*Kato,Billinghurst*发布了ARToolKit,第一款开源AR平台。技术上通过识别黑白图案来定位追踪现实物体。这是现在我们经常看到的AR平台的先驱（从下图也可以看到很像现在手机上一些AR应用）

![Untitled 9](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%209.png)

2000年后手机计算技术飞速发展。2003年*Wagner ,Schmalstieg*发布了第一款用于移动设备的AR系统。

![Untitled 10](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2010.png)

## 举例(行业应用)

### 工业和建筑业

工业设施变得越来越复杂，当想要更换，更新设备设施时变得越来越难想象和计划。传统上需要从当初的设计(CAD)上修改设计后来模拟更换后的设计，但这非常费时也不利于直观理解。专门针对此类问题的的AR系统无需从CAD返工，直接在现场再现修正案的前后效果，在前期的可行性调查和计划中非常有效

![Untitled 11](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2011.png)![Untitled 12](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2012.png)![Untitled 13](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2013.png)

### 维护和训练

在很懂行业需要员工理解产品如何工作，如何装配，分解产品。传统的电子或者纸质手册欠缺直观性，培训员工是一件很头疼的事(然而其实并不是因为操作很难，仅仅是因为描述起来很难)。一些AR技术帮助培训员工通过直接映射某些部件的构成和操作提示在实物上。

![Untitled 14](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2014.png)![Untitled 15](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2015.png)

如何无论如何都需要一个老师，通过AR技术老师可以实现直观的远程指示和教学。

![Untitled 16](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2016.png)

## 医学

通过同时应用AR映射X成像和相机彩色图片，医生可以更直观，快速的了解到患者的病情。

![Untitled 17](C:%5CUsers%5Cfan%20baby%5CDesktop%5Cmarkdown%5Cmarkdown_rep%5C1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality%5CUntitled%2017.png)

## 个人用AR显示器

除了以上专业领域，在普通的个人消费领域也有很多应用。比如yelp(美国的大众点评网)使用GPS和地图信息将商店信息直接映射到现实世界里。

![Untitled 18](C:%5CUsers%5Cfan%20baby%5CDesktop%5Cmarkdown%5Cmarkdown_rep%5C1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality%5CUntitled%2018.png)

Goolge将翻译后的文本直接覆盖在元物体上。

![Untitled 19](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2019.png)

## 导航

传统的导航地图和现实是分离的。通过AR技术，将导航信息直接映射到现实成像中非常的直观。另外流行的倒车辅助技术也是将倒车轨迹通过AR技术映射到了后置摄像头的成像中。

![Untitled 20](C:%5CUsers%5Cfan%20baby%5CDesktop%5Cmarkdown%5Cmarkdown_rep%5C1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality%5CUntitled%2020.png)![Untitled 21](C:%5CUsers%5Cfan%20baby%5CDesktop%5Cmarkdown%5Cmarkdown_rep%5C1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality%5CUntitled%2021.png)

## 电视节目

现在已经有很多节目应用了AR技术。特别是体育运动的节目中常常使用虚拟的线条描述轨迹，界限等信息。当然现场观众是看不到的

![Untitled 22](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2022.png)



## 广告和商业

通过电子设备扫描纸质媒体上特殊的图案后跳转到包含更加详细的广告视频网页等，广告商业领域也有不少应用AR技术的例子。

![Untitled 23](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2023.png)

对于一些比较复杂的设备，AR技术帮助顾客快速直观的理解各种信息

![Untitled 24](C:%5CUsers%5Cfan%20baby%5CDesktop%5Cmarkdown%5Cmarkdown_rep%5C1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality%5CUntitled%2024.png)

虚拟试穿可能会成为下一个风口。

![Untitled 25](C:%5CUsers%5Cfan%20baby%5CDesktop%5Cmarkdown%5Cmarkdown_rep%5C1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality%5CUntitled%2025.png)

## 游戏

第一款AR商业游戏登录于PS3, The Eye of Judgment. 类似于游戏王，抽卡召唤对战。

Vuforia SmartTerrain推出了一款塔防游戏，而游戏里场景都来自于真实的场景。

![Untitled 26](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2026.png)

常见的游戏被限定在电视，显示器等虚拟屏幕里，而AR技术可以将整个室内甚至是室外作为游戏的空间。微软的IllumiRoom就是一个结合显示设备和周围场景的游戏原型。某些3D模型会被映射到真实场景中。

![Untitled 27](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2027.png)

## 相关领域

*这一篇主要讲述了AR，VR， MR等相同点和不同点，以及它们的联系。*

*另外还讲到了无处不在(Ubiquitous)的数据和计算和AR的亲和性*

### 混合现实(MR)

MR指的是现实和虚拟混合的体系。从完全的现实到完全的虚拟，混合程度的不同，就有了以下不同的名称。AR是属于更关注现实的技术。 *个人觉得这些名字都很容易混淆。。另外MR这个词也被微软玩坏了*

![Untitled 28](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2028.png)

### VR

VR需要使用者处于一个完全虚拟(计算机生成)的环境中。从某种意义上开发不需要对现实做过多考虑所以会更加容易。现在市面上也有很多VR头盔像是Oculus Rift，HTC Vive. 这些设备也适用于AR场景。从MR的定义中可以法相VR和AR是可以共存的。

无处不在的计算(Ubiquitous Computing)

*这个词我在不同行业的英文，日文文献，书籍里都见过，总之就是类似于大数据，IOT一类的词吧，但是好像很少进入大众视野？*

这个词指的就是在未来数字技术，数据也会被量产，潜移默化的存在于生活中的点点处处。移动互联网让我们对这个概念有了更深一步的理解，但还不够。这里有句引用语：

The most profound technologies are those that disappear. They weave themselves into the fabric of everyday life until they are indistinguishable from it.

就是说极度发达的科技都是隐藏于表象的，存在于各处却又让人感受不到。无处不在的计算也是指的这种“沉默的计算”，人们并不需要也不会主动意识到便利背后的科技。但是即使如此，总有什么时候需要一个可以交互的窗口，而AR技术就能很好的胜任这种场景。

题外话，VR是违反这种场景的，因为VR是一种必须让使用者意识到其存在的技术。

下图总结了各种相关技术的属性。轴上的名字忽视掉吧。

![Untitled 29](https://raw.githubusercontent.com/spicyoil/markdown_rep/main/1_AR%E5%8E%9F%E7%90%86%E5%92%8C%E5%AE%9E%E8%B7%B5%E7%AC%AC%E4%B8%80%E7%AB%A0_Introduction_to_Augmented_Reality/Untitled%2029.png)

Source1: [https://arbook.icg.tugraz.at/](https://arbook.icg.tugraz.at/) 原作者网站 

Source2: [日亚](https://www.amazon.co.jp/AR%E3%81%AE%E6%95%99%E7%A7%91%E6%9B%B8-Dieter-Schmalstieg/dp/4839965366/ref=pd_lpo_14_t_0/358-3651351-1172009?_encoding=UTF8&pd_rd_i=4839965366&pd_rd_r=4a8f48ff-eb9f-4a83-8fe6-43239a4556b9&pd_rd_w=08k4K&pd_rd_wg=PKnul&pf_rd_p=43793539-bb55-42ca-a906-e224e71aa7fd&pf_rd_r=CT192GKQN2A4F8JYTEEA&psc=1&refRID=CT192GKQN2A4F8JYTEEA) 日文翻译版 **英语不好结合着在看**