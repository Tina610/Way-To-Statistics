# [Error Bars](https://www.nature.com/articles/nmeth.2659)

>**误差线（`error bars`）的含义经常被误解成他们的重叠是否是统计显著的。**

这是题注，仅仅是题注就让我伤透脑筋。误差线在我之前的理解中，就是如果两个（我也不知道两个后面应该接什么，所以直接省略了）的误差线如果有重叠，那么这两个（我又省略）就不是显著差异的。

>在上个月的`Points of Significance`中，我们给大家展示了，怎么用`样本`来估计`总体`的统计参数。我们强调了，由于存在随机的因素，所以我们的估计也有不确定性。这个月我们将着重介绍，在科学刊物中，如何表示这种不确定性，还会揭示不确定性经常被错误解释的一些方式。

>在统计估计中的不确定性，一般都会使用`误差线`来表示。尽管大部分的研究者用过或者看见过`误差线`，但`误差线`怎么样能和统计显著性联系起来，仍旧有很多的错误理解。

然后作者引用了一篇很有意思的文献，像是一个问卷调查。

>当受访者被要求估计两个有误差线的点是否显著（p=0.05）分离的时候，仅仅只有22%的受访者考虑到了因素2。

我的理解是，不仅仅要看误差线是否分离，还需要知道，误差线是什么的表示。这也就是上文中的因素2。

就像一杯水不能表示水的多少，只有在明确杯子的大小后，一杯水才可以。

>事实上，`误差线`却是能够帮助我们评估两个值是否显著差异，只是在表面看上去令人不太好理解。

`In light of the fact that error bars are meant to help us assess the significance of the difference between two values, this observation is disheartening and worrisome.`

再次放上原文，感觉又是不太好翻译的。

>在此，我们利用一个简单的例子来展示`误差线`的差异。我们从一个`正态分布`中以相同的`样本容量`进行`抽样`，所获的值的均值就是我们用来展示的数据。

这个真是的很绕。英语不好真是累。同样放上原文。`Here we illustrate error bar differences with examples based on a simplified situation in which the values are means of independent (unrelated) samples of the same size and drawn from normal populations with the same spread.`

>我们使用`2-sample t-test`计算`样本`的`均值`的差异的显著性而且以近似`P value`来展示结果。尽管展示准确`P value`应该更好，但是为了方便，显著性一般都取`阈值`为P=0.05。我们会在后面更加详细的讨论`P value`和`t-test`。
 

意思很好理解，但是要说出来，真的感觉越来越难。

>区分`误差线`的重要性就像[^chap2-1]中所展示的那样。

![chap2-1](http://wx2.sinaimg.cn/mw690/0060lm7Tly1fr4b03jzilj30ci0720u5.jpg)

>图中有三种常用的`误差线`，`标准差（s.d.）`，`标准误（s.e.m）`还有`置信区间（CI）`。图中所展示的就是两个`样本容量`为10的样本的三种`误差线`的范围，以及他们所对应的均值差异的`P value`。在[^chap2-1]的a图中，自建的数据使得对于不同的`误差线`都有相同的长度，并使得2个`样本`的`误差线`毗邻。

>尽管这三对数据还有他们的`误差线`看起来像是一样的。但是他们分别表示了不同的数据情况，并且还有不同的`P value`。

>在[^chap2-1]的图b中，我们更换的展现形式，使得`P value`都是0.05，然后展示不同`误差线`在相同`P value`下不同的长度。在这种情况下，三对数据其实是同一对`样本`，但是`误差线`却因为不同的类型而具有不同的长度，这不同类型的`误差线`也表现的是数据的不同的统计特性。

>在`误差线`不同长度的情况下就很容易哪对样本看起来更不同。一般情况下，`样本`间的`误差线`的空隙并不能说明`显著性`，同样`误差线`重叠也不能说明不显著，这都需要明确指明`误差线`的类型。

>对于你来说，是不是特别惊奇，原来还有这样一个内涵在其中。

有些调皮，但却是让我有了更明确的认识，以前的确不区分这一部分。


![chap2-3](http://wx3.sinaimg.cn/mw690/0060lm7Tly1fr4b0369dmj30cf06fjs3.jpg)
![chap2-2](http://wx4.sinaimg.cn/mw690/0060lm7Tly1fr4b03e6stj30cn096767.jpg)

