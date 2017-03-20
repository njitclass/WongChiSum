
	 
# 第五章 测量的基本概念及理论

	 
大纲

- 量化构念
- 古典测量理论(classical measurement theory)
- 共同因子(common factor)的概念
- 效度(validity)的相关概念
 - 构念关系网(nomological network)
 - 多元特质和多重方法矩阵(multitrait-multimethod matrix)
 
[toc]
	 
## 量化「离职意向」的构念

请您圈选您对以下描述的同意程度：
       1=极不同意；2=不同意；
       3=没所谓同意或不同意；
       4=同意；5=极同意

- 我常想到辞职。

- 我很可能于明年另寻新的工作。

- 如果能自由选择，我不会喜欢留在这机构工作。

	 
## 古典测量理论
(**classical measurement theory**)

**Observed Score (OS)** 观测分数受三个影响:
 1. 真实得分(True Score; TS)
 2. 独特得分(Unique Score; US)
 3. 误差得分(Error Score; ES)

「离职意向」的例子:

OS1 = TS + US1 + ES1 (第一题)

OS2 = TS + US2 + ES2 (第二题)

OS3 = TS + US3 + ES3 (第三题)
	 
### 变异量(Variance)及共变量(Covariance)
国内称为方差及协方差

- 以变异量及共变量验证构念间之关系
- 样本整体变异量(Observed Variances; O),包括:

(1) 真实差异(True Variance；T)

(2) 独有因素带来的差异(Unique Variance；U)

(3) 随机误差带来的差异(Error Variance；E)

 $$O = T + U + E$$

	 
### 信度(reliability)

(1) 随机误差差异$ E$ 占 观测差异$O$ 的比重
(2) 因为 $E$ 是随机的，信度是测量的工具免于随机误差的程度
(3) 测量结果的一致性或稳定性

	 
### 信度系数的估计:

为了与统计上的相关系数看齐，我们一般会取两次测量的共变量比例的平方根，来合计信度 ，称之为信度系数(reliability coefficient)。

	 
### 信度系数的方程式

$$信度系数 =\sqrt{\frac{T+U}{O}}=\sqrt \frac{O-E}{O}$$

	 
### 信度(reliability)的估计
 两次测量的相关系数:
（a）再测信度(test-retest reliability)
（b）复本信度(alternative forms reliability)
（c）折半信度(split-half reliability)
（d）项目间的一致性(internal consistency reliability) : Coefficient alpha; $\alpha$ (对应SPSS “reliability” 的指令)

- 一般来说信度系数要在0.7以上

	 
### 信度对检定构念关系的影响

两个构念的共变量(假设最理想情况):
两构念在测量时的独有变异量均为零

### 两个构念观察所得的相关系数
$$R_o^2=\frac{C}{\sqrt{O_1*O_2}}$$	 


### 两个构念真实的相关系数
$$R_t^2=\frac{C}{\sqrt{(O_1-E_1)*(O_2-E_2)}}$$	 

### 测量工具的信度系数	 
$$r_1=\sqrt \frac{O_1-E_1}{O_1};r_2=\sqrt \frac{O_2-E_2}{O_2}$$

### Rt 与 Ro的关系
(Correction for Attenuation对衰减的修正)
$$
\frac{R_o^2}{r_1*r_2} = \frac{C}{\sqrt{O_1*O_2}/(\sqrt{\frac{O_1-E_1}{O_1}*\frac{O_2-E_2}{O_2}})}$$ 
$$=\frac{C}{\sqrt{(O_1-E_1)*(O_2-E_2)}}=R_t^2$$

$$|R_t|=\frac{|R_0|}{\sqrt{r_1*r_2}}$$	 
可见，真实相关系数大于观测相关系数。

###影响信度的主要因素

1. 受测量者方面
2. 主持测量者方面
3. 测量内容方面
4. 测量情境方面
5. 时间影响方面
	 
## 共同因子(common factor)的概念

Common Factor = CF

	 
**共同因子(common factor):共变量**

$T =$ 共同因子的变异量
              (各项目的共变量: 没有测量误差的变异量)

	 
**因子的设定:项目的加权总和**
(Linear Combination)

	 
### 负荷量(factor loadings)及特征值(eigenvalues)
负荷量(L值; factor loadings因子载荷)及特征值(eigenvalues)

(1) 每一因子抽取了这九个项目总体变异量的 一部分
(2) 每一因子抽取了九分一的总体变异量，由于不同情况牵涉的项目数不一样，所以我们把这平均值标准化，以1为代表，称为特征值  (eigenvalue)
(3)特征值为该因子的所有L值平方的总和
(4) 因子抽取的总变异量的比率便是特征值除以 测量项目的总数
(5) 负荷量: 由 -1 到 1
	 
**因子的数学背景**
 
- 如有两个项目(V1及V2)，变异量为VA1及VA2，共变量为CA，它们的加权总和(F)的变异量(FA)的方程式是：
$$FA = (L1)^2VA1 + (L2)^2VA2 + (L1)^2(L2)^2CA$$
	 
- (L1及L2小于1，所以FA是包含V1及V2部分的VA1、VA2及CA)。
	 
- 把共变量愈大的项目在同一个因子中的 L 值加大，这因子便能够同时把这两个项目更多的变异量和共变量都抽取。	 
- 尽量用小数的因子来抽取最多的整体变异量，便会是相互间共变量大的项目在同一因子中的 L 值较大，而共变量大也符合了它们可能受同一原因影响的假定。

	 
###  因子分析的假设
1. 各因子抽取了总体变异量的不同部分
2. 尽量用较少的因子来抽取最大比率的总体  变异量; 假设其他因子代表 U 及 E 的变  异量
3. 集中在少数因子， 使少数项目的L值尽量扩大(rotation):
 - 决定集中在选多少个因子
 - 是否容许这少数因子有相关

	 
### 「探索性因子分析法」的例子
(Exploratory Factor Analysis；EFA)

182名香港的中学教师
三题测量「同意特质」(A1、A2及A3)、
三题「工作满意度」(JS1、JS2及JS3)、及
三题「自评的工作表现」(JP1、JP2及JP3)
	 
### EFA的SPSS指令

在没有特定原因的情况下，我们以特征值等于1来抽取少数因子；另外，由于老师的「同意特质」性格可能与其「工作满意度」及「自评的工作表现」有关，因此在「rotation」时我们不应假定因子之间是无关的，所以用SPSS的指令是：
```
get file=’name of file containing the SPSS save file’.
factor vars=A1 A2 A3 JS1 JS2 JS3 JP1 JP2 JP3   /extraction=paf/rotation=oblimin.
```
	 
**「探索性因子分析法」的结果**

	 
###「探索性因子分析法」的限制

(1) L值的设定及最后抽出特征值大于1 (或其他设定的标准)的因子数目，是完全取决于我们在实证研究所取得样本数据
(2) 虽然我们说第一个因子的主要变异量是来自「工作满意度」的三个测量项目，但它还是包括了其他六个测量项目的部分变异量，严格来说，这是不正确的

	 
### 「确认性因子分析法」的假设关系(Confirmatory Factor Analysis；CFA)

	 
**「确认性因子分析法」的步骤**

 F1 = L11JS1 + L12JS2 + L13JS3
 F2 = L21A1   + L22A2   + L23A3
 F3 = L31JP1 + L32JP2 + L33JP3

-- 其余的 L 值(因子载荷)为零
-- 先对这些构念和它们的测量项目有一 个清楚及符合测量理论的关系假设，然后以实证的样本数据来验证这关系假设
	 
**LISREL (CFA) 指令**
```
Observed Variables: A1 A2 A3 JS1 JS2 JS3 JP1 JP2 JP3
Latent Variables: AGREE JOBSAT JOBPERF
Raw Data From File: (data file name)
Relationships:
A1 A2 A3 = AGREE
JS1 JS2 JS3 = JOBSAT
JP1 JP2 JP3 = JOBPERF
End of Problem
```	 
### CFA 结果

**因子的相关矩阵**(Factor Correlation Matrix)
					AGREE   JOBSAT  JOBPERF
AGREE          1.00
JOBSAT         0.19        1.00
JOBPERF      0.13        0.42        1.00

	 
### 检定是否接受原来关系假设的标准指标
(Goodness of Fit Statistics)

(1) 常用: RMSEA(或RMR; 最好是少于0.08)、NNFI(也称为TLI；最好是大于0.90)和CFI(最好是大于0.90)。
(2) 我们一般会报告Chi-Square及其Degrees of Freedom(它们的比率最好少于2.5)、及GFI(最好是大于0.90)
(3) Chi-Square和GFI与样本数有很大的关系，很多时样本数愈大，它们反而更不理想，所以相对而言，RMSEA、TLI和CFI在判定是否接受原来关系假设更为重要。

## 效度(validity)的概念

1) 测量结果是否正确，便是效度(validity)的问题
(2) 从O=T+U+E的方程式来理解，效度是指T占 O 的比重
(3) 信度是效度的必要条件，而非充分条件
(4) 检定效度的主要方法，最好是检定构念间的关系网(nomological network)

### 检定效度的方法
1. 内容效度(content validity)
2. 效标关联效度(criterion-related validity):
       - 同时效度(concurrent validity);
       - 预测效度(predictive validity);
       - 增加效度(incremental validity)
3. 建构效度(construct validity):
       - 辐合效度(convergent validity);
       - 辨别效度(discriminant validity)

###  多元特质和多重方法矩阵
(multitrait-multimethod matrix)

### 多元特质和多重方法矩阵的分析
- 比较各相关系数的大小
- CFA:
       C1的因子:M1C1,M2C1,M3C1
       C2的因子:M1C2,M2C2,M3C2
       C3的因子:M1C3,M2C3,M3C3
       M1的因子:M1C1,M1C2,M1C3
       M2的因子:M2C1,M2C2,M2C3
       M3的因子:M3C1,M3C2,M3C3
       
### 影响效度的主要因素
- 测量组成方面
- 测量实施方面
- 受测者反应方面
- 效标方面
- 样本方面

## 小结

本章介绍了测量的基本理论和检定信度和效度的方法，由于测量的信度和效度是科学研究的基本和必须的要求，所以在下两章中，我们会用几个真实的例子，说明构念的建立及应用检定信度和效度方法的具体过程


> Written with [StackEdit](https://stackedit.io/).