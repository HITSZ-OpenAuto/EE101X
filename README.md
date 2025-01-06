# EE101X - 电路与电子学

<!--
1. 通过 [Shields.io](https://shields.io/) 生成如下的徽章，标注课程的基本信息。
2. 请根据课程的具体内容增删仓库的子文件夹。子文件夹建议使用小写英文，并且添加 README.md。
3. 关于课程的描述可以不止以下几个方面，酌情增删。
4. hoa.moe 生成本课程对应页面后，请将页面链接复制到 GitHub 仓库的 About/Website 中。
5. 可以在 GitHub 页面的 About/Topics 中为课程添加话题名称。
-->

![考试课](https://img.shields.io/badge/%E8%80%83%E8%AF%95%E8%AF%BE-red)
![学分](https://img.shields.io/badge/%E5%AD%A6%E5%88%86-4-moccasin)

![成绩构成](https://img.shields.io/badge/%E6%88%90%E7%BB%A9%E6%9E%84%E6%88%90-gold)
![作业20%](https://img.shields.io/badge/%E4%BD%9C%E4%B8%9A-20%25-wheat)
![考试80%](https://img.shields.io/badge/%E6%9C%9F%E6%9C%AB%E8%80%83%E8%AF%95-80%25-wheat)

注意，电路与电子技术实验（[EE1014](https://hoa.moe/docs/fresh-spring/ee1014/)）是独立设课。

2024年春季起开设的缝合课程，计算机与电子通信、自动化与电气工程、机器人与智能装备大类均开设。

要查找资料及查看学习建议，可以前往以下链接：

- [电路IA](https://hoa.moe/docs/fresh-spring/ee1011a/)
- [模拟电子技术基础](https://hoa.moe/docs/sophomore-spring/ee1007/)
- [数字电子技术基础](https://hoa.moe/docs/sophomore-spring/ee1009/)

## 学时安排
> 文 / [Gaster](https://github.com/WDGaster703), 2025.1

2024年春季学时安排表：

![总学时](https://img.shields.io/badge/总学时-64-gold)
![电路28](https://img.shields.io/badge/电路-28-wheat)
![模电18](https://img.shields.io/badge/模电-18-wheat)
![数电18](https://img.shields.io/badge/数电-18-wheat)

授课内容：包含《电路理论基础》前四章，《模拟电子技术基础》第一、四、五、六、七章，和《数字电子技术基础》第一、二、四、五、六、八章。具体如下：

{{% details title="电路部分" closed="true" %}}
<!--标题-->
<table border="1" cellspacing="10">
<tr>
  <th align="center">章节</th>
  <th align="center">授课内容</th>
  <th align="center">学时安排</th>
  <th align="center">课程要求</th>
</tr>
<tr>
  <td rowspan="2" align="center">电路元件和电路定律</td>
  <td>电流电压与电功率；电容、电感；独立源、受控源</td>
  <td>3</td>
  <td>1.熟练掌握电流、电压与电功率的基本概念和计算方法(重点)；<br>
      2.熟练掌握参考方向的概念(难点)；<br>
      3.熟练掌握各元件的定义、符号表示、外特性及分类(重点)；<br>
      4.熟练掌握各元件的端口特性(重点)；<br>
      5.掌握各元件的功率计算(重点、难点)，电感、电容的储能计算；<br>
      6.熟练掌握各电源元件的定义、符号表示和外特性；<br>
      7.掌握各电源的功率计算。</td>
</tr>
<tr>
  <td>基尔霍夫定律</td>
  <td>2</td>
  <td>1.了解描述电路结构的相关术语；<br>
      2.熟练掌握基尔霍夫电流定律和电压定律的表述(重点)；<br>
      3.熟练运用基尔霍夫定律列写电路方程(重点)；<br>
      4.掌握独立的 KCL、KVL 方程的列写方法(重点、难点)。</td>
</tr>
<tr>
  <td rowspan="3" align="center">线性直流电路</td>
  <td>线性电阻电路的等效变换法</td>
  <td>2</td>
  <td>1.掌握等效的概念；<br>
      2.熟练应用简单电阻网络（串并联等）及复杂电阻网络的等效方法及结论(重点)；<br>
      3.熟练应用含源支路的等效变换条件(重点)；<br>
      4.运用等效变换方法求解简单电路。</td>
</tr>
<tr>
  <td>支路电流法，回路电流法</td>
  <td>2</td>
  <td>1.熟练掌握支路电流法的原理及方程的一般列写规则；<br>
      2.熟练掌握回路电流法的原理及方程的一般列写规则；</td>
</tr>
<tr>
  <td>节点电压法</td>
  <td>2</td>
  <td>1.熟练掌握节点电压法的原理及方程的一般列写规则。</td>
</tr>
<tr>
  <td rowspan="2" align="center">电路定理</td>
  <td>置换定理、齐性定理和叠加定理</td>
  <td>2</td>
  <td>1.透彻理解并熟练掌握置换定理(重点)；<br>
      2.透彻理解并熟练掌握齐性定理和叠加定理(重点、难点)。</td>
</tr>
<tr>
  <td>等效电源定理</td>
  <td>2</td>
  <td>1.透彻理解并熟练掌握戴维宁定理和诺顿定理(重点、难点)；<br>
      2.了解特勒根定理、互易定理和对偶原理。</td>
</tr>
<tr>
  <td rowspan="5" align="center">正弦电路的稳态分析</td>
  <td>正弦电流，正弦量的相量表示法</td>
  <td>2</td>
  <td>1.掌握正弦量的含义及其数学表达式；<br>
      2.透彻理解正弦量的相量表示法及其性质(重点)。</td>
</tr>
<tr>
  <td>电路定律的相量形式，电路元件的 VCR 方程</td>
  <td>2</td>
  <td>1.透彻理解基尔霍夫定律的相量形式特点(重点)；<br>
      2.透彻理解元件约束方程的相量形式特点；<br>
      3.理解阻抗和导纳的概念。</td>
</tr>
<tr>
  <td>正弦电路的相量分析法</td>
  <td>2</td>
  <td>1.熟练掌握正弦电流电路的相量分析法(重点)。</td>
</tr>
<tr>
  <td>正弦电路的功率</td>
  <td>3</td>
  <td>1.熟练掌握正弦电流电路功率的定义和功率计算，并体会其相互关系(重点、难点)；<br>
      2.了解功率因数提高的原理、意义和方法；<br>
      3.正确理解并应用最大功率传输定理(重点)。</td>
</tr>
<tr>
  <td>耦合电感；理想变压器</td>
  <td>4</td>
  <td>1.理解耦合电感、理想变压器的概念；<br>
      2.熟练掌握含耦合电感的电路分析、列写相应方程(重点)；<br>
      3.熟练掌握含理想变压器的电路分析、列写相应方程(重点)。</td>
</tr>
</table>
{{% /details %}}

{{% details title="模电部分" closed="true" %}}
<!--标题-->
<table border="1" cellspacing="10">
<tr>
  <th align="center">章节</th>
  <th align="center">授课内容</th>
  <th align="center">学时安排</th>
  <th align="center">课程要求</th>
</tr>
<tr>
  <td rowspan="2" align="center">常用半导体器件</td>
  <td>PN结；半导体二极管；</td>
  <td>2</td>
  <td>1.了解本征半导体、杂质半导体和PN结的形成；熟练掌握PN结的单向导电性（重点）；<br>
      2.熟练掌握半导体二极管的结构类型、伏安特性、参数、模型和基本应用电路。</td>
</tr>
<tr>
  <td>晶体三极管；场效应管</td>
  <td>2</td>
  <td>1.正确理解双极型晶体管的结构、类型和电流放大作用；熟练掌握共射特性曲线和参数；<br>
      2.正确理解场效应管的类型、结构、工作原理；熟练掌握场效应管的特性曲线、参数和型号。</td>
</tr>
<tr>
  <td rowspan="2" align="center">运算放大器的基本应用电路</td>
  <td>运算放大器概述；远算放大器的线性应用电路；</td>
  <td>2</td>
  <td>1.正确理解运算放大器的组成、符号和电压传输特性；<br>
      2.熟练掌握理想运算放大器的技术指标、工作在线性区和非线性区的特点(重点)；<br>
      3.熟练掌握比例运算电路的组成、特点和分析方法(重点)；<br>
      4.熟练掌握加减运算电路的组成、特点和分析方法(重点)；<br>
      5.熟练掌握积分和微分运算电路的组成、特点和分析方法；<br>
      6.一般了解对数和指数运算电路的组成、特点和分析方法。</td>
</tr>
<tr>
  <td>运算放大器的非线性应用电路</td>
  <td>2</td>
  <td>1.熟练掌握单限比较器(重点)；熟练掌握滞回比较器(重点、难点)；<br>
      2.熟练掌握窗口比较器。</td>
</tr>
<tr>
  <td rowspan="2" align="center">放大电路中的反馈</td>
  <td>反馈的基本概念；反馈的判断方法；反馈的基本方程式</td>
  <td>2</td>
  <td>1.熟练掌握反馈的基本概念；<br>
      2.熟练掌握反馈组态和极性的判断方法(重点)；<br>
      3.熟练掌握反馈基本方程式及负反馈、深度负反馈的概念(重点)。</td>
</tr>
<tr>
  <td>四种负反馈放大电路的分析；负反馈对放大电路性能的影响</td>
  <td>2</td>
  <td>1.熟练掌握四种交流负反馈放大电路的组态特点；<br>
      2.熟练掌握四种交流负反馈放大电路的反馈系数及深度负反馈条件下放大倍数的计算方法(重点、难点)；<br>
      3.正确理解负反馈对放大电路性能的影响，包括：稳定增益、改变输入输出电阻、展宽频带、抑制失真和噪声(重点)。</td>
</tr>
<tr>
  <td rowspan="2" align="center">信号发生电路</td>
  <td>正弦波振荡电路的组成及振荡条件；正弦波振荡电路的组成、特点和分析方法</td>
  <td>2</td>
  <td>1.熟练掌握正弦波振荡电路的组成及振荡条件(重点)；<br>
      2.掌握 RC 振荡电路的组成、特点和分析方法；<br>
      3.了解 LC 正弦波振荡电路的组成、特点和分析方法。</td>
</tr>
<tr>
  <td>非正弦波发生电路</td>
  <td>2</td>
  <td>1.熟练掌握矩形波、三角波和锯齿波发生电路的结构、原理和参数计算方法(重点、难点)；</td>
</tr>
<tr>
  <td rowspan="2" align="center">信号的处理与变换</td>
  <td>频率特性；无源滤波器</td>
  <td>1</td>
  <td>1.熟练掌握频率特性的概念；<br> 
      2.熟练掌握滤波器的分类与分析方法(重点)；<br>
      3.熟练掌握无源滤波器的结构、特点和分析方法。</td>
</tr>
<tr>
  <td>有源滤波器</td>
  <td>1</td>
  <td>1.熟练掌握一阶、二阶有源低通滤波器的结构、特点和分析方法(重点)；<br>
      2.正确理解简单有源高通、带通、带阻滤波器的结构、特点和分析方法(重点)。</td>
</tr>
</table>
{{% /details %}}

{{% details title="数电部分" closed="true" %}}
<!--标题-->
<table border="1" cellspacing="10">
<tr>
  <th align="center">章节</th>
  <th align="center">授课内容</th>
  <th align="center">学时安排</th>
  <th align="center">课程要求</th>
</tr>
<tr>
  <td rowspan="2" align="center">逻辑代数基础</td>
  <td>数制和码制；逻辑运算；逻辑代数的基本定理和基本规则；最小项和最大项的概念</td>
  <td>4</td>
  <td>1.熟练掌握几种常用的数制和编码(重点)；<br>
      2.熟练掌握逻辑运算(重点)；<br>
      3.熟练掌握逻辑代数的基本定理和基本规则(重点)；<br>
      4.掌握最小项和最大项的概念和性质(重点)</td>
</tr>
<tr>
  <td>逻辑函数的卡诺图化简法；具有无关项的逻辑函数化简</td>
  <td>2</td>
  <td>1.熟练掌握逻辑函数的卡诺图化简法(重点)；<br>
      2.熟练掌握具有无关项的逻辑函数卡诺图化简法(重点、难点)。</td>
</tr>
  <tr>
  <td rowspan="2" align="center">组合逻辑电路</td>
  <td>组合逻辑电路的分析方法；组合数字电路的设计方法</td>
  <td>1</td>
  <td>1.熟练掌握组合逻辑电路的特点和功能描述(重点)；<br>
      2.熟练掌握组合逻辑电路的分析方法(重点)；<br>
      3.熟练掌握组合逻辑电路的设计方法(重点)。</td>
</tr>
<tr>
  <td>译码器 74LS138 及应用；数据选择器 74LS151 及应用；</td>
  <td>2</td>
  <td>1.熟练掌握译码器 74LS138 及应用(重点、难点)。<br>
      2.了解数据选择器 74LS151 及应用；</td><br>
</tr>
<tr>
  <td rowspan="3" align="center">时序逻辑电路</td>
  <td>触发器的基本概念</td>
  <td>2</td>
  <td>1.掌握 RS 触发器的结构与功能，掌握电平触发、边沿出发和脉冲触发的特点；<br>
      2.熟练掌握 RS,JK,D,T 等各类触发器功能。</td>
</tr>
<tr>
  <td>同步时序逻辑电路的分析</td>
  <td>2</td>
  <td>1.了解时序逻辑电路的特点和功能描述，掌握 Moore 型和 Mealy 型电路的定义和特点；<br>
      2.熟练掌握同步时序逻辑电路的分析方法(重点)；</td>
</tr>
<tr>
  <td>同步时序逻辑电路的设计</td>
  <td>3</td>
  <td>1.熟练掌握同步时序逻辑电路的设计方法(重点)；</td>
</tr>
<tr>
  <td rowspan="1" align="center">数模和模数转换</td>
  <td> A/D 和 D/A 转换器</td>
  <td>2</td>
  <td>1.熟练掌握 AD 与 DA 转换的基本概念(重点)；<br>
      2.了解倒 T 型电阻解码网络 D/A 转换器；<br>
      3.熟练掌握集成 D/A 转换器 AD7524 (重点)；<br>
      4.熟练掌握 D/A 转换器的转换精度与转换时间(重点、难点)。</td>
</tr>

</table>

{{% /details %}}

> 文 / [Gaster](https://github.com/WDGaster703), 2024.12

## 授课教师

二/三位老师分别按顺序讲解一部分课程——但老师并不一定有讲授这节课的经历

> 文 / [IcyDesert](https://github.com/IcyDesert), 2024.5

23级的授课老师如下：
- 电路部分：王毅,孙丽,和军平,詹瀚林，王灿；
- 模电部分：王立欣,谷雨,梁仲明,吴婷,潘学伟；
- 数电部分：王立欣,梁亮,梁仲明,朱荣伍,喻锦程；
- 三个部分的老师可以分别参考原《电路IA》《电路IB》《模拟电子电路基础》《数字电子电路基础》对应老师的介绍。
- 24级据说授课老师会有变化，具体以实际授课为准。

## 关于考试

- 考试由电路、模电、数电三部分题目按顺序组合而成，分数占比4:3:3，题型为填空题和计算题，其中计算题3题电路，2题模电，2题数电，填空题4题电路，3题模电，3题数电。
- 23级的考试计算量很大，且模电部分考察了许多概念性填空，考试时注意时间安排。

> 文 / [Gaster](https://github.com/WDGaster703), 2024.12

## 学习建议

如果大家有预习的需求，下图所示预习顺序可供参考

```mermaid
graph LR
A(电路1-4章)
B(数电1-2章)
C(模电第1章)
A<-->B
A-->C
D(数电第3章)
C-->D
B-->E
E(数电第4-6章)
A-->F
F[电路8-9、12章]
```

上图中，方框中为选学内容（在预习的有限时间里优先级较低），圆框中为必学内容；标有双箭头的框之间可同步学习，标有单箭头的框之间有承接关系。

> 文 / [Oliver Wu](https://github.com/OliverWu515), 2024.3

电路部分学有余力建议自学频率响应（第七章）和暂态电路（第八、九章）的内容，在模电部分对这部分知识有要求但是电路部分学时没有安排。电路和数电总体按体系讲解，可以跟着教学计划学习，学有余力可以自学跳过的内容。模电授课内容较为零碎，建议跟着上交大zzy或者清华hcy对模电整本书进行初步的学习，至少对分立元件搭成的放大电路有一点基本的认知。

> 文 / [Gaster](https://github.com/WDGaster703), 2024.12

### 网课推荐

- [电路 哈工大 - Bilibili](https://www.bilibili.com/video/BV19x411x7We/?spm_id_from=333.337.search-card.all.click)
- [模拟电子技术基础 上海交通大学 郑益慧主讲 - Bilibili](https://www.bilibili.com/video/BV1Gt411b7Zq)
- [模拟电子技术基础 清华大学 华成英主讲 - Bilibili](https://www.bilibili.com/video/BV1M7411b7Wb)
- [数字电子技术基础 清华大学 王红主讲 - Bilibili](https://www.bilibili.com/video/BV18p411Z7ce)

> 建议正常听课时关闭弹幕，有任何不懂的地方才打开，看看弹幕里的解答（这也是 B 站的一大好处，解答非常及时）

