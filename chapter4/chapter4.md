
	 
# 第四章  统计在管理研究上的应用


[toc]
## 数据性质及机率的概念
	 
### 断续(discrete)数据的性质

例子：运动鞋的标准尺码和穿各个尺码鞋的人数
鞋子尺码与该尺码人数的频数分布
 	 
### 连续(continuous)数据的性质
例子：人群体重的分布概率密度函数曲线
人群体重的累计分布曲线
	 
### 数据的描述

**中间倾向(Central Tendency)**

- 平均值(Mean; Average)
- 中间值、中位数(Median)
- 众数(Mode)
	 
**分散的程度**

- 标准偏差(Standard Deviation)
- 变异量(方差; Variance)
 
### 连续(continuous)数据的分布
- 正态分布
- 两个偏态分布
 - 卡方分布
 - F分布
 	 
## 信赖区间(confidence interval)的计算
	 
母体/总体(Population) 与样本(Sample)的分别
	 
- 以样本的统计量数(Statistics)估计总体的参数(Parameters) 的工作
>在特定的样本数/样本规模(Sample Size; n)之下， “无限抽样”后知道某一统计量数的分布(Sampling Distribution of the “statistic”)	 
得知某一统计量数的分布后，便可计算参数的信赖区间(confidence interval)  

假设从母体中随机地不停抽一千人(即n=1000)的样本，每一个样本我们都把它的平均值和变异量)记录下来。
如果我们真的抽了无限个样本，便可知道这些样本平均值及变异量的分布，即:

 - 「平均值的抽样分布」(Sampling Distribution of the Means)；  
 - 「变异量的抽样分布」(Sampling Distribution of the Variances）

而这些「样本统计量数的**抽样分布**」（Sampling Distribution of the Statistic)的**标准偏差**称为估计标准误「Standard Error of Estimate」(Se)，或简称**标准误**「Standard Error」，其平方($Se^2$)便是此分布的变异量。
	 
示例：从母体中随机地不停抽样本


|样本  |            平均值 |     标准偏差|
|---|---|---|
|1|                   X1 |      S1|
|2|                   X2 |      S2|
|3|                   X3 |      S3|
|4|                   X4 |      S4|
|5|                   X5 |      S5|
|.|                  ..  |      ..|
|.|                  ..  |      ..|

	 
(X1,X2, X3…..) 的分布是平均数的抽样分布	 
(S1,S2,S3…..) 的分布是标准偏差的抽样分布
	 
信赖区间(confidence interval)的计算(3)
假设统计量的抽样分布服从正态分布
那么在分布的均值正负1.96标准差所累积面积为95%。
	 
信赖区间(confidence interval)的计算(4)
如果样本确实是随机而没有偏差，那么母体的平均值(即μ)会在:
       (1)上限:样本的平均值加上1.96A
       (2) 下限:样本的平均值减去1.96A
       之间的机会将为百分之九十五(95%)。
因为抽到的样本有95%的机会是在μ-1.96A到μ+1.96A之间，只要是在这范围内的样本，μ便一定在样本的平均值加上1.96A 及减去1.96A 之间。
       除非我们那么不幸，所抽的样本刚好在μ-1.96A到μ+1.96A之外，那么μ便不在上述范围之内了，不过，这样的机会只有百分之五(5%)。

## 统计测试(Hypothesis Testing)	 
###  统计测试步骤

1. 建立(保守、原、虚无)假设
2. 抽样: 收集资料
3. 根据信赖区间的知识，估计当所订立的原假设是正确时，此样本出现的机率的 (p值)
4. 下结论:
       - p值大(例如比5%大)，则不能推翻原假设
       - p值小(例如比5%小)，则推翻保守的假设
	 
### 统计测试的限制

1.理论架构
2.机率性的测试(Type I and Type II Errors)
3.样本的代表性
4. 统计方法的假定
5. 数据(数据)的可靠性
	 
## 测量尺度(Measurement Scale)

**数字的精确程度:**

- 类别尺度 (Nominal Scale)
- 等级尺度 (Ordinal Scale)
- 等距尺度 (Interval Scale)
- 等比尺度 (Ratio Scale)

	 
## 统计测试的应用例子-类别变量间的卡方检验

自变项与依变项均为类别尺度 (Nominal Scale) : 性别与是否吸烟的关系。卡方检验。

 1. 订立假设：

       保守假设H0：性别与吸烟无关。
       相反假设H1：性别与吸烟有关。

 2. 抽样:搜集资料 	 
|性别| 吸烟 | 不吸 | 小计 |
|::|:--:|:--:|:--:|
| 男性 | 45 | 55 | 100 |
| 女性 | 55 | 45 | 100 |
| 小计 | 100 | 100 | 200 |

  3. 机率的估计。

卡方测试的方程式为：
$$\chi ^2 = \sum\limits_{i =1}^r {\sum\limits_{j = 1}^{c} {\frac{( f_{ij} - e_{ij})^2}{e_{ij}}} } $$                                 
       
而    r = 行的数目; c = 列的数目; f = 观察所得的数目;
       e = 在H0为正确时的期望数目
       
在我们的例子中，当H0是正确，而母体的男女比率为一比一时，及吸烟与非吸烟者的比率也是一比一时，则我们应期望四个观察数目均为50, 所以：
       卡方数值为 2.0

当H0是正确时，我们会观察到这样的一个样本的机率有多大呢(即${\chi ^2}$ 为2.0)?            
要少于百分之五，查证统计图表可知需比3.84大。
4. 下结论：由于2.0少于3.84, 我们不能推翻原来较保守的假设H0：性别与吸烟无关。

	 
## 统计测试的应用例子-组间均值差异


类别尺度的自变项与等距尺度的依变项: 性别与吸烟数量的关系

(1)订立假设:
       原假设H0：男女平均吸烟数目并无分别。
       备择假设H1：男女平均吸烟数目有分别。
	 
(2) 抽样:搜集资料
| 性别 | 样本数 | 每日平均吸烟数 | 标准差s |
|:----:|:-----:|:---------:|:------:|
| 男性 |$n_1=$100人 | $\bar x_1=10.3$ | $s_1=2.2$ |
| 女性 |$n_2=$100人 | $\bar x_2=6.4$ | $s_2=3.5$ |

(3)机率的估计。t测试的方程式，当假设两个母体的标准偏差一样时是：
$$| t | = \left| {\frac{{\left( \bar x_1 -\bar x_2\right)}}{{\sqrt {\left[ {\frac{{\left( {{n_1- 1}} \right)s_1^2 + \left( {{n_2} - 1} \right)s_2^2}}{n_1 + n_2 - 2}} \right]\left[ {\frac{1}{n_1} + \frac{1}{n_2}} \right]} }}} \right|$$
       
所以，这样本的 $|t| = 22.82$

当H0是正确时，我们会观察到这样的一个样本的机率有多大呢(即$ |t|=22.82$)?  
要少于百分之五，查证统计图表可知需比1.99大。
(4)下结论。由于22.82大过1.99，我们可推翻原假设，而接受备择假设H1：男女平均吸烟数目有分别。如果 t 为正值，则男的平均比女的大；如果 t 为负值，则女的平均较大。

	 
## 统计测试的应用例子-相关系数


自变项与依变项均为等距尺度: 收入与吸烟数量的关系

(1)订立假设:

- 原假设H0：每月收入和每天吸烟数目之       间的相关系数为零（即二者无关）。
- 备择假设H1：每月收入和每天吸烟数目之       间的相关系数不是零（即二者有关）。

(2) 抽样：收集资料。例如我们访问200人，得知他们每人的每月收入（自变项X）及每天吸烟数目（依变项Y）。

  |受访者| 每月收入| 每天吸烟数量|
  |-------|------|--------|
  |张三|    $4000|  8枝|
  |李四|  $6000|   7枝|
  |黄五|  $5000|   0枝|
  |.. |   ..|     ..|

(3)机率的估计。样本相关系数 r 的方程式是：
$$|r|=|\frac{\sum\limits_{i=1}^{n}(x_i y_i -n\bar x \bar y)}{\sqrt{\sum\limits_{i=1}^{n}(x_i^2-n\bar x^2) \sum\limits_{i=1}^{n}(y_i^2-n \bar y^2)}}|$$

在这200人的样本我们计算到的 $|r| = 0.45$

当H0是正确时，我们会观察到这样的一个样本(即 |r| = 0.45)的机率有多大呢？
要少于百分之五，查证统计图表可知需比0.1381大。

(4)下结论。由于0.45大过0.1381，我们可推翻原来较保守的假设，而接受备择假设H1：每月收入和每天吸烟数目是有关的。至于它们的关系，如果r为正值，则X愈大，Y愈大；如果r为负值，则X愈大，Y愈小。 
	 
### 相关系数(Correlation Coefficient)的意义

我们说当两个变项均为等距尺度时，可用相关系数来检定它们的关系，为什么呢？
因为相关系数的设计就是为了描述两个变项是否有共同改变的特质，如果我们用面积来代表变异量，那么下图X的变异量便是A+C，Y的变异量是B+C。C的部分我们称为X和Y的共变量(Covariance)，是X和Y变异量中相同的部分。

	 
### 相关系数的图示及方程式


变异量(方差):
$$r^2 = \frac{C}{{\sqrt {(A + C) * (B + C)} }}$$
 
**相关系数的解释**

C占X和Y总体变异量的比重是成正比的，C愈大，r便愈大。在数学上它的平方($r^2$)便是C在X或Y的变异量的比率。例如X和Y的r=0.6，X有36%的变异量是与Y的共变量(Y也一样)。
如果这共变量的比重愈大，X和Y的关系便愈密切，因为我们愈能从一个变项的改变得知另一变项的可能变动。

C也可以是正或负值的，正值代表当一个变项的数值增大时，另一变项的数值也会增加；负值代表当一个变项的数值增大时，另一变项的数值却会减少。
由于相关系数代表了一个比率的平方根，它的可能数值是从-1.00到1.00的。
	 
## SPSS 指令 


可以处理大量数据的计算机软件很多，我们在这里介绍其中一个广为使用的SPSS 软件:
(1) 研究(Wong, Wong, & Law, 2005)
(2) 问卷(Example(SPSS-Questionnaire).doc)
(3) 指令(Example(SPSS-Command-File).sps)

- 在SPSS的软件中，可到「Help」的部分，打开「Syntax Guide」中的「Base」便可见到详细的「SPSS Syntax Reference」

	 
### **“data list”**
数据列表命令规定变量的名称和输入的各变量所在的数据列。
```
data list
/code 1-4 age 6-7 sex 8 tenjob1 9-10 tenjob2 11-12 tenorg1 13-14 tenorg2 15-16 educat 17 married 18 depend 19-20 sat1 to sat5 21-25 life1 to life9 26-34 com1 to com6 36-41 leave1 to leave3 42-44 jc1 to jc3 45-47 eq01 to eq20 48-67 el1 to el6 68-73 job 74. 
```

###**“begin data.”** 和**“end data.”**
 数据输入应放在**“begin data.”** 和**“end data.”**命令之间
```
begin data.
(data according to the data list format)
end data.
```

### **“missing values”**
缺失值命令告知SPSS软件什么数值代表无效数据. 例如，在下面的命令中，当变量**sex**输入值为9，这意味着答辩人没有回答这个问题。
```
missing values sex educat married sat1 to el6 (9)          tenjob1 tenjob2 tenorg1 tenorg2 depend age (99).
```

###  **“value labels”** 
值标签命令通知程序特定变量的每个分数的含义。这是特别针对分类变量的命令。
```
value labels job 1 'bus-drivers' 2 'govt-clerks' 3 'shop-mgrs' 4 'teachers' 5 'programmer' 6 'art-design-computer'.
```
	 
### **“compute”** 
计算命令通过数学公式创建新的（或替换旧的）变量。例如，下面的命令创建一个新变量“tenjob”，它等于“tenjob1”乘以12加上“tenjob2”，之后除以12。
```
compute tenjob=(tenjob1*12+tenjob2)/12.
```
	 
### 不同的compute均值计算
在计算语句中，我们可以创建一个新变量，该变量是一组定义变量的均值。有两种方法可以做到这一点。在下面的例子中，第一个命令将计算出“sat”变量的五个变量的均值（SAT1到sat5）。
若sat1到sat5这5个变量中有缺失值，新的变量将由响应的平均值估计。
若sat1到sat5这5个变量中有缺失值，第二命令将分配新的变量的值也设为缺失值。
```
(1) compute sat=mean(sat1 to sat5).
(2) compute sat=(sat1+sat2+sat3+sat4+sat5)/5.
```

###  **“descriptive vars=”**
“描述性变量=“命令给出声明的变量的均值、标准偏差和变量的取值范围。
```
descriptive vars=ei el sat lifesat oc jc age tenjob educat.
```
	 
### **“frequencies vars=”** 
“频率变量=”命令给出变量的频数。这适用于分类变量。
```
frequencies vars=sex married.
```

### **“crosstabs”**
交叉表命令提供两个分类变量之间的关联关系的卡方检验。
```
crosstabs sex by job/statistics=chisq.
```

### **“ttest”**
t检验命令为术语“groups =”之后的二分变量指定分组的连续变量提供t检验。
```
ttest groups=sex(0,1)/vars=ei.
```
	 
### **“correlation vars=”**  
“correlation vars =”命令提供语句中指定的变量之间的相关系数。
```
correlation vars=ei el sat lifesat oc jc age tenjob educat sex married.
```
	 
### **“anova”** 
anova命令为指定的连续和分类变量提供ANOVA方差分析。以下示例的第二个命令是ANCOVA，因为控制变量在关键字“with”之后指定。
```
(1) anova ei by job(1,6).
(2) anova ei by job(1,6) with jc age tenjob educat sex married.
```
	 
### **“reliability”**.
“reliability”命令为指定的变量提供α系数（内部一致性可靠性）。
```
reliability vars=sat1 to sat5.
```
	 
### **“factor vars=”**.
“factor vars =”命令为指定的变量提供因子分析。在以下示例的第一个命令中，将提供主成分分析。该分析假设q潜在因素不相关。在以下示例的第二个命令中，因子分析假设潜在因素可以相关。
```
(1) factor vars=eq01 to eq16/rotation=varimax.
(2) factor vars=eq01 to eq16  /extraction=paf/rotation=oblimin.
```
	 
###**“regression”**
“回归”命令提供回归分析。我们需要指定（1）将用于回归分析的所有变量; （2）因变量（“dep =”之后）;和（3）输入自变量的顺序。在以下示例的第一个命令中，sat是因变量，所有变量都放入回归。在第二个命令中，变量在三个步骤中分级输入。
```
(1) regression vars=sat ei el inter jc tenjob sex age married educat oc/dep=sat/method=enter.
(2) regression vars=sat ei el inter jc tenjob sex age married educat oc/statisics coeff outs r cha/criteria=pin(.05) pout(.10)/noorigin/dep=sat/method=enter jc tenjob sex age married educat oc/method=enter ei el/method=enter inter.
```
	 
###**“means tables =”**
命令提供在关键字“by”之后指定的子组的均值和标准偏差统计量。
```
means tables=ei el sat lifesat oc jc age tenjob educat sex married by job.
```
	 
### **“if”**
命令提供了创建符合某种条件的新变量（或旧变量的变换）。以下命令创建一个名为“Holland”的新变量，当原始变量“job”等于1时，它等于1。除等于（eq），我们可以指定（1）小于（lt）; （2）小于或等于（le）; （3）大于（gt）;或（4）大于或等于（ge）。
```
if (job eq 1) Holland=1.
```
### **选择保存没有缺失值的个案到新文件**
以下命令集计算新变量“allvar”，它是16个“eq”变量的总和。然后它重新编码“allvar”的缺失数据等于999. 然后选择“allvar”小于900的个案。这意味着它删除了“allvar”中有缺失值的个案。 **“write”命令**要求软件将16个eq变量写入到名为“cfa.txt”的文件到计算机的“a”驱动器。 “16（1x，F2.0）”指定要写出的格式：“1x”表示空白; “F2.0”表示两个空格，一个用于十进制。
```
compute allvar=eq01+eq02+eq03+eq04+eq05+eq06+eq07+eq08+                         eq09+eq10+eq11+eq12+eq13+eq14+eq15+eq16.
recode allvar (missing=999).
select if (allvar lt 900).
write outfile='a:\cfa.txt'/eq01 to eq16 (16(1x,F2.0)).
execute.
```
	 
### **“save outfile =”**
存盘命令要求计算机将此命令之前创建的所有变量保存到特定的SPSS格式文件。以下示例要求计算机将数据保存到计算机的“a”驱动器的名为“hksample.sav”的文件。
```
save outfile=’a:\hksample.sav’.
```
	 

### **“get file =”**
读取命令要求计算机从正式保存的SPSS格式文件中获取数据。以下示例要求计算机读入“a”驱动器中名为“hksample.sav”的文件中的数据。
```
get file=’a:\hksample.sav’.
```
	 
## 进一步的参考文献


本章的重点是说明统计学对组织行为及人力资源管理研究非常重要的基本概念，学员应进一步参考社会科学研究中统计方法的标准教课书，例如：

 1. Moskowitz, H., & Wright, G.P. (1985). Statistics for management and   economics. Columbus, Ohio: Charles E. Merrill Publishing Company.
 2. Neter, J., Wasserman, W., & Kutner, M. (1985). Applied linear
    statistical models: Regression, analysis of variance and
    experimental designs, 2nd edition. Homewood, Illinois: Richard D.
    Irwin, Inc.

> Written with [StackEdit](https://stackedit.io/).