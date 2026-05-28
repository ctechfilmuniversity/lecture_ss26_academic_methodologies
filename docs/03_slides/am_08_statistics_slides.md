name: inverse
layout: true
class: center, middle, inverse
---


# Academic Methodologies

#### - Statistics in a Nutshell -

<br /><br />

### Prof. Dr. Lena Gieseke | l.gieseke@filmuniversitaet.de  

#### Film University Babelsberg KONRAD WOLF




---
layout:false

## Statistics?


???
  

* Is what?

--

> The practice or science of collecting and analyzing numerical data in large quantities, especially for the purpose of **inferring proportions in a whole from those in a representative sample**.  
  
\- Apple Dictionary


???
  
We are currently living in the best and worst of times regarding data and its evaluation. 

* The importance of statistics and an awareness about potential problems when using statistics to make general statements is not new. Let's hear what some smart people said about this.

???
  

* Both the power and corruption of statistics are daily on display.
* Machine Learning is a statistical model

---
## Statistics

> The numbers have no way of speaking for themselves. We speak for them. We imbue them with meaning. 

\- [Nate Silver](https://en.wikipedia.org/wiki/Nate_Silver)
  
---
## Statistics

> Like dreams, statistics are a form of wish fulfillment.  
  
\- [Jean Baudrillard](https://en.wikipedia.org/wiki/Jean_Baudrillard)

---
## Statistics
> Figures don't lie, but liars figure.  
  
\- [Samuel Clemens](https://en.wikipedia.org/wiki/Mark_Twain) (alias Mark Twain, 1835 – 1910)


???
  

> If your experiment needs statistics, you ought to have done a better experiment.  
  
  
\- [Ernest Rutherford](https://de.wikipedia.org/wiki/Ernest_Rutherford) (1871 – 1937)


* In this lecture, however, we aim for an accurate display of information, not to obscure it. 
* Let's have a look first on what kind of data we might be working with.
* The process of transforming collected information or observations to a set of meaningful, cohesive categories.
* In the above example, the information on age is numerical and does not need to be coded. The information on gender, highest degree earned, and previous software experience needs to be coded so that statistical software can interpret the input.
* Coding can lead to a deeper understanding and the emergence of relationships, patterns, etc. When coding your data, the most important thing to remember is to ensure the coding is consistent.

---
## Statistics

.center[<img src="../02_scripts/img/statistic/garbage_01.png" alt="garbage_01" style="width:80%;">  .imgref[[[solutions.ait.ac.th]](http://solutions.ait.ac.th/garbage-in-garbage-out/)]]



---
## Statistics

???


* What is the difference between descriptive and inferential statistics?

--

Descriptive statistics 

* Summarizes data 
* Information is presented in a manageable form  


???
  
* Helps to describe and to organize data
* Descriptive statistics *summarizes* data and helps to describe and to organize data. Information is presented in a manageable form.  
* An example for descriptive statistics?

--

<br />

Inferential statistics 

* Anlayses data
* Draws conclusions about a population based on samples
    * Based on rigid requirements on the data and maths

???
  
* Generalizes and makes judgments
* Inferential statistics *draws conclusions* about a population based on samples and helps to analyze data. Inferential statistics is used to generalize and make judgments. For that there are rigid requirements on the data for the maths to work and to allow for such generalizations.


.center[<img src="../02_scripts/img/statistic/statistics_08.png" alt="statistics_08" style="width:50%;">]


---
.header[Descriptive Statistics]

## Graphs

.center[<img src="../02_scripts/img/statistic/statistics_22a.png" alt="statistics_22a" style="width:70%;">].imgref[[[oreilly]](https://www.oreilly.com/library/view/statistics-in-a/9781449361129/ch04.html)]

---
.header[Descriptive Statistics]

## Graphs

.center[<img src="../02_scripts/img/statistic/statistics_22b.png" alt="statistics_22b" style="width:70%;">].imgref[[[oreilly]](https://www.oreilly.com/library/view/statistics-in-a/9781449361129/ch04.html)]

---
.header[Descriptive Statistics]

## Graphs

.center[<img src="../02_scripts/img/statistic/statistics_22c.png" alt="statistics_22c" style="width:80%;">].imgref[[[oreilly]](https://www.oreilly.com/library/view/statistics-in-a/9781449361129/ch04.html)]


---
.header[Descriptive Statistics]

## Graphs

.center[<img src="../02_scripts/img/statistic/statistics_11.png" alt="statistics_11" style="width:70%;">].imgref[[[cellfish]](http://blog.cellfish.se/2014/08/lying-with-statistics.html)]




???
  

* *What might be the problem with the following bar charts?*
* Yes, exactly. One of the most common tricks used is to show small changes as huge by not using zero as the base in a diagram. 
* Looking at the Fox News graph it looks like as if there was a huge increase in the enrollment in Obamacare.  But the difference between the two numbers is only 33,000, which is in regard to the start value of 7,066,000 not that much. But as the graphic cuts off the bottom part of the graphs the increase is greatly exaggerated. Don't ask me what the intentions were, I always thought that Fox News was against Obamacare...

---
.header[Descriptive Statistics]

## Graphs

.center[<img src="../02_scripts/img/statistic/statistics_16.png" alt="statistics_16" style="width:70%;">].imgref[[[spiegel]](https://www.spiegel.de/politik/deutschland/rezo-video-die-youtube-angriffe-auf-die-cdu-im-spiegel-faktencheck-a-1268973.html) *Figure by Rezo*]




???
  

* In regard to the question of *wealth through inheritance*, Rezo showed the following figure:

---
.header[Descriptive Statistics]

## Graphs

.center[<img src="../02_scripts/img/statistic/statistics_17.png" alt="statistics_17" style="width:80%;">].imgref[[[spiegel]](https://www.spiegel.de/politik/deutschland/rezo-video-die-youtube-angriffe-auf-die-cdu-im-spiegel-faktencheck-a-1268973.html) *Original by Alvaredo et al./ Atkinson/ CC BY 4.0*]



???
  

* Not only did Rezo remove the graphs of the other countries in comparison, he also cut the timeline - the oldest and most evil move in regard to graph manipulations! In this case the manipulated figure implies that the historically exceptionally values between the 1960-90 (as it becomes clear from the original figure) were a normal phase. Spiegel calls this in its article about the fact-checking of Rezo's video *ein absolutes No-Go*. This is especially disappointing, as the Spiegel points out, as there is enough valid data to underline the point Rezo was overall trying to make.

---
.header[Graphs]

.center[<img src="../02_scripts/img/statistic/statistics_18.png" alt="statistics_18" style="width:44%;">].imgref[[[gregstevens]](http://gregstevens.com/2011/02/21/lying-with-statistics-101/)]

???
  

* Most people see in the graphic above a huge fall-off in the number of gun deaths after Stand Your Ground was passed. That is what the law was aiming for but that’s not what the graph shows. A quick look at the vertical axis reveals that the gun deaths are counted from top (0) to bottom (800). The highest peaks are the fewest gun deaths and the lowest ones are the most. A rise in the line, in other words, reveals a reduction in gun deaths. The graph below — flipped both horizontally and vertically — is more intuitive to most: a rising line reflects a rise in the number of gun deaths and a dropping a drop.

---
.header[Graphs]

.center[<img src="../02_scripts/img/statistic/statistics_19.png" alt="statistics_19" style="width:44%;">].imgref[[[gregstevens]](http://gregstevens.com/2011/02/21/lying-with-statistics-101/)]


---
.header[Descriptive Statistics]

## Frequency Distributions

Counts the number of times each score occurs.

.center[<img src="../02_scripts/img/statistic/statistics_25.png" alt="statistics_25" style="width:36%;">]

--

<br />

*How can the data be summed up and described with a single value?*  

---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Central Tendency

Calculate a *central tendency* and the *centric point* of a distribution. 


???
  

* Any examples?

---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Central Tendency

Calculate a *central tendency* and the *centric point* of a distribution. 
 


.center[<img src="../02_scripts/img/statistic/statistics_29a.png" alt="statistics_29a" style="width:70%;">]  
[[4]](https://docs.google.com/presentation/d/1cPWa6NqbEot8dBjVC7UKPjF72Q7myYjHqyBYS9HO_qg/edit#slide=id.g5137fefd78_1_189)

---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Central Tendency

Calculate a *central tendency* and the *centric point* of a distribution. 
 


.center[<img src="../02_scripts/img/statistic/statistics_29b.png" alt="statistics_29b" style="width:70%;">]  
[[4]](https://docs.google.com/presentation/d/1cPWa6NqbEot8dBjVC7UKPjF72Q7myYjHqyBYS9HO_qg/edit#slide=id.g5137fefd78_1_189)

---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Central Tendency

Calculate a *central tendency* and the *centric point* of a distribution. 
 


.center[<img src="../02_scripts/img/statistic/statistics_29c.png" alt="statistics_29c" style="width:70%;">]  
[[4]](https://docs.google.com/presentation/d/1cPWa6NqbEot8dBjVC7UKPjF72Q7myYjHqyBYS9HO_qg/edit#slide=id.g5137fefd78_1_189)

---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Central Tendency


.center[<img src="../02_scripts/img/statistic/statistics_38.png" alt="statistics_38" style="width:100%;">]  .imgref[[[taniapouli]](http://taniapouli.me/wp-content/uploads/2016/08/s2010_course.pdf)]


???
  

* What makes the two images different?


---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Central Tendency

![statistics_35](../02_scripts/img/statistic/statistics_35.png)  
.imgref[[[wiki]](https://en.wikipedia.org/wiki/Mean#/media/File:Comparison_mean_median_mode.svg)]


???
  

* If data is symmetrically distributed, the mean and median will be close, especially as n increases. If the data is skewed, mean, median and mode can differ greatly. Depending on our question, that might really matter... we will come back to this.

---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Central Tendency

> When is the mean not representative for a data set and why?


???
  

* For the data set of 5 5 5 5 5, the mean of 5 directly represents the actual values and is therefore a good measurement. However the single values of 6 8 4 1 6 differ quite strongly from the mean of 5, which therefore is not the best representation. This characteristic of how much the single values differ to the mean is reflected by the *variance* of a data set.


---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Spread



.center[<img src="../02_scripts/img/statistic/statistics_39.png" alt="statistics_39" style="width:70%;">]


???
  
To describe how data are situated around the central tendency, we use measures of data spread. 

* What makes them different, once again, is the *distribution* of values.

---
.header[Descriptive Statistics | Frequency Distributions]

## Measures of Spread


???
  

* Do you know one?

--

Mathematically, the variance is exactly the mean squared distance that values have to the mean. 

--

.left-even[<img src="../02_scripts/img/statistic/statistics_40.png" alt="statistics_40" style="width:90%;">]

--

.right-even[<img src="../02_scripts/img/statistic/variance_01.png" alt="variance_01" style="width:90%;">]


???
  

* What is the standard variation?
* As the formula for variance shows, the units of variance are the units of the observation *squared*, *x<sub>i</sub><sup>2</sup>* and in a variance's value can not be directly compared to the value range of the collected data. Hence, to get the metric back into units of the variable, we take the square root of the variance, which is called the *standard deviation σ*.
* A large value means that values are quite different from each other and that the data varies a lot. Hence, the mean is not representative for the data set. A small value means all data points are close to the mean with little variation. Hence, the mean is a valid representation of the data.
* Both *variance* and *standard deviation* measure the accuracy of the mean of data set and the variability of the data. Variance and standard deviation only differ in a scaling factor.

---
.header[Descriptive Statistics]

## Box and Whisker Plots

.center[<img src="../02_scripts/img/statistic/statistics_48.png" alt="statistics_48" style="width:20%;">]

???
  

* For an overview of the most important values, the core of a box and whisker plot, in short *boxplot*, looks as follows:
    * The box is bounded by the two inner quartiles of the data. This is called the *interquartile range* (IQR). Its middle line shows the median and the whiskers extend to the last observation within 1 step (usually 1.5 * IQR) from the end of the box.
* Quantiles are cut points that divide a sample of data into groups containing (as far as possible) equal numbers of observations. 

---
.header[Descriptive Statistics]

## Box and Whisker Plots

.center[<img src="../02_scripts/img/statistic/statistics_49.png" alt="statistics_49" style="width:30%;">]

???
  


.center[<img src="../02_scripts/img/statistic/statistics_50.png" alt="statistics_50" style="width:40%;">]




* Any observations beyond the whiskers are plotted as individual points.

---
.header[Descriptive Statistics |  Box and Whisker Plots]

.center[<img src="../02_scripts/img/statistic/statistics_53.png" alt="statistics_53" style="width:80%;">]


???
  

* What do the histogram plots, meaning the frequency distributions, of the following box and whisker plots look like?

---
.header[Descriptive Statistics |  Box and Whisker Plots]


.center[<img src="../02_scripts/img/statistic/statistics_54.png" alt="statistics_54" style="width:60%;">]


---
## Descriptive Statistics

--

In descriptive statistics we use

* measures of central tendency (mode, median, mean), and
* measures of spread (variance, standard deviation)

to describe and summarize data.

--

<br >

We usually report

* mean and standard deviation values in the accompanying text, and
* a summary of the data as box plots graphically.


???

Hence, we can summarize a <span style="color:blue">sample</span> (meaning a set of data) using its <span style="color:red">mean</span> and we can access the accuracy of that mean using the standard deviation.

![statistics_56](../02_scripts/img/statistic/statistics_56.png)  



But how well does one <span style="color:blue">sample</span> represent the <span style="color:darkorange">population</span>?

![statistics_57](../02_scripts/img/statistic/statistics_57.png)  


Probably not too well…  



We could take several <span style="color:blue">samples</span> from the same <span style="color:darkorange">population</span>, each with its own <span style="color:red">mean</span>.

.center[<img src="../02_scripts/img/statistic/statistics_58.png" alt="statistics_58" style="width:65%;">]



We could take several <span style="color:blue">samples</span> from the same <span style="color:darkorange">population</span>, each with its own <span style="color:red">mean</span>.

.center[<img src="../02_scripts/img/statistic/statistics_58.png" alt="statistics_58" style="width:45%;">]

Then, the question becomes whether the <span style="color:blue">sample distribution</span> is representative for the <span style="color:darkorange">population</span>?


???
  

* This question is answered with *inferential* statistics.


---
template:inverse

# Inferential Statistics

---
## Inferential Statistics

With inferential statistics you can reach to conclusions that extend beyond the immediate data alone but describe a population overall.


---
.header[Inferential Statistics]

## Hypothesis Testing

Determine the likelihood of a hypothesis about some parameter value to be true. 


???
  

* What is the approach here, key word: null hypothesis

--



* Null hypothesis H<sub>0</sub>: Assumes that there is no difference between two conditions
* Alternative hypothesis H<sub>A</sub>: Assumes significant differences between the two conditions



???
  

* Mü

--

We assume the null hypothesis to be true until proven otherwise.  

--

* Reject the null hypothesis (proven by the data)
* Fail to reject the null hypothesis


???
  

* The data is the evidence and we can make one of two decisions:


---
.header[Inferential Statistics]

## Hypothesis Testing

There are a variety of test available, each potentially including several steps.

???
  

* The first test, we need to have a look into is a test that uses a calculated probability to determine whether there is evidence to reject the null hypothesis, hence ideally showing that we have indeed observed an effect.
* There are two common tests for that, the [Critical Value approach](https://online.stat.psu.edu/statprogram/reviews/statistical-concepts/hypothesis-testing/critical-value-approach) and the [p-value approach](https://online.stat.psu.edu/statprogram/reviews/statistical-concepts/hypothesis-testing/p-value-approach). The p-value approach requires only one computation and most statistical software uses it. So let's have a look into that, starting with an example.

--
<br >

Common steps are:

--
* Test if there is an effect in comparison to random results

--
* Test how the data is distributed

--
* Test to quantify the effect

---
template:inverse

## Observed Effect or Random Results?

---
.header[Inferential Statistics]

## P-Value

--

> The probability of obtaining the results by chance.
  
--

It aims to prove statistical significance for a cause and effect!

???

* A small p-value means that the null hypothesis is very unlikely.
* A large p-value means that the  null hypothesis is very likely.

---
.header[Inferential Statistics | P-Value]

## Lady Tasting Tea

![tea](../02_scripts/img/statistic/tea.png)  
.imgref[[[wiki]](http://en.wikipedia.org/wiki/File:Milk_clouds_in_tea.jpeg)]


???
  

* [Dr. Muriel Bristol](https://en.wikipedia.org/wiki/Muriel_Bristol), a female colleague of mathematician [Sir Ronald Fisher](https://en.wikipedia.org/wiki/Ronald_Fisher) claimed to be able to tell whether the tea or the milk was added first to a cup. Fisher didn't believe her and claimed that she was just guessing.
* Fisher proposed to test Lady Bristol's ability with a within-group experiment design. 
* In a within-group design, also called *repeated-measure* design, participants are assigned to *all* conditions. For this type of grouping it is important to also randomize task orders.

---
.header[Inferential Statistics | P-Value]

## Lady Tasting Tea

* Eight cups, four of each variety, in random order
* Dr. Bristol tastes four cups and reports which she thought had milk added first

--

H<sub>0</sub>: The lady has no ability to distinguish the teas. Hence there is no causality, and we assume she is just guessing!


???
  

* Now, Fisher investigated - given the outcome of the experiment - what the probability would be of Dr. Bristol performing the way she did by just guessing?

---
.header[Inferential Statistics | P-Value]

## Lady Tasting Tea

> What are the probabilities for guessed outcomes?

--

* n = 8 total cups
* k = 4 cups chosen
  
Based on the [combination formula](https://en.wikipedia.org/wiki/Combination), these numbers lead to

$\binom{n}{k} = \frac{n (n-1)...(n-k+1)}{k (k-1)...1} = \frac{n!}{k!(n-k)!} = \frac{8 \cdot  7 \cdot 6 \cdot 5}{4 \cdot 3 \cdot 2 \cdot 1}  = 70$

possible answers.



---
.header[Inferential Statistics | P-Value]

## Lady Tasting Tea

| Correct Guesses | Combinations                  | Cases              | Probability                   |
| --------------- | ----------------------------- | ------------------ | ----------------------------- |
| 0               | oooo                          | $\binom {4}{0}=1$  | $\frac{1}{70}\approx 1.4\%$   |
| 1               | ooox,ooxo,oxoo,xooo           | $\binom {4}{1}=16$ | $\frac{16}{70}\approx 22.9\%$ |
| 2               | ooxx,oxxo,oxox,xxoo,xoox,xoxo | $\binom {4}{2}=36$ | $\frac{36}{70}\approx 51.4\%$ |
| 3               | xxxo,xxox,xoxx,oxxx           | $\binom {4}{3}=16$ | $\frac{16}{70}\approx 22.9\%$ |
| 4               | xxxx                          | $\binom {4}{4}=1$  | $\frac{1}{70}\approx 1.4\%$   |

???
  
* Cases: ways to choose k correct cups (while there are 4 cups that truly had milk first)
    * ways to choose  0 milk-first
    * ways to choose  1 milk-first
    * ways to choose all 2 milk-first
    * ways to choose all 3 milk-first
    * ways to choose all 4 milk-first
    * we calculate \binom{4}{k}



* The frequencies of the possible numbers of successes, given in the final column of this table, are derived as follows. For 0 successes, there is clearly only one set of four choices (namely, choosing all four incorrect cups) giving this result. For one success and three failures, there are four correct cups of which one is selected, which by the combination formula can occur in {\displaystyle {\binom {4}{1))=4} different ways (as shown in column 2, with x denoting a correct cup that is chosen and o denoting a correct cup that is not chosen); and independently of that, there are four incorrect cups of which three are selected, which can occur in {\displaystyle {\binom {4}{3))=4} ways (as shown in the second column, this time with x interpreted as an incorrect cup which is not chosen, and o indicating an incorrect cup which is chosen). Thus a selection of any one correct cup and any three incorrect cups can occur in any of 4×4 = 16 ways. The frequencies of the other possible numbers of successes are calculated correspondingly. Thus the number of successes is distributed according to the hypergeometric distribution. The distribution of combinations for making k selections out of the 2k available selections corresponds to the kth row of Pascal's triangle, such that each integer in the row is squared. In this case, k=4 because 4 teacups are selected from the 8 available teacups.

The critical region for rejection of the null of no ability to distinguish was the single case of 4 successes of 4 possible, based on the conventional probability criterion < 5%. This is the critical region because under the null of no ability to distinguish, 4 successes has 1 chance out of 70 (≈ 1.4% < 5%) of occurring, whereas at least 3 of 4 successes has a probability of (16+1)/70 (≈ 24.3% > 5%). 

--
<br >

If the lady is guessing, there is only a *1.4%* chance that she will get all cups correct.


---
.header[Inferential Statistics | P-Value]

## Lady Tasting Tea

Fisher decided to accept that Dr. Bristol's has indeed an ability to taste the difference if she identified all four cups correctly. 


???
  

* Fisher argued that the probability for guessing this case is just too low. Hence, only with the identification of all four cups, Fisher were willing to reject the null hypothesis that Dr. Bristol is guessing.

Dr. Bristol identified all four cups of tea successfully 😀! Apparently, pouring hot tea into cold milk makes the milk curdle, but not so when pouring cold milk into hot tea.

--


<br />
This experiment is an example of the p-value approach to hypothesis testing.  


???
  
  
It uses a calculated probability p to determine whether there is evidence to reject the null hypothesis.  

--

> If the calculated **probability for randomness** is below a certain threshold, also called the *significance level α*, we assume cause and effect in our data. 



---
.header[Inferential Statistics]

## P-Value


Typical alpha levels of significance are

* p < .05 (Fisher-Criterion)
* p < .01
* p < .001

Which α to chose also depends on the discipline.  

???
  
We can reject H<sub>0</sub> if the computed p‐value is ≤ α. 

* The Fisher-Criterion is the most commonly chosen one. It means th experiment results hav the same probability of five correct guesses in a row:

| Number of correct guesses | Probability for consecutive correct guessing |
| ------------------------- | -------------------------------------------- |
| 1x                        | 0.5                                          |
| 2x                        | 0.25                                         |
| 3x                        | 0.125                                        |
| 4x                        | 0.0625                                       |
| 5x                        | 0.03125                                      |

--

> This shows that what we accept as *proven effect* also simply depends on somewhat arbitrary standards a research community decided on.

---
template:inverse

# Data Distribution

???
  

## Parametric Statistics

The factor that we want to investigate is called *parameter* and is some *numerical characteristics* of interest.  

Is there any difference between conditions or groups?
  
> Compare the arithmetic means over the collection of samples.


Usually, we want to find out whether there is any difference between conditions or groups and do so by comparing the arithmetic means over their sample collection.  


Then, the mean μ is the parameter. 


* e.g. patients that took a new drug vs. patients that didn't, etc. 
* Keep in mind that, we don't — or can't — know the real value of a population parameter; we only ever estimate it with applying statistics!

---
.header[Inferential Statistics]

## Parametric Statistics

For parametric tests to work, we have to assume some underlying statistical distributions in the data:

--
1. Normal distribution

--
2. Homogeneity of variance


???
  

* Shows that the mean is representative for the data set.
* Homogeneity of variance is given when all comparison groups have about the same variance, meaning that the data spread is similar enough to make meaningful comparisons between the groups. 


---
.header[Inferential Statistic | Parametric Statistics]

## Normal Distribution

> What is a normal distribution? Why is it important to test whether a data sample is normally distributed?

--

Many statistical computations only work when the data is roughly shaped as such a *bell curve* or *Gaussian curve*.

???
  

* The dependent variable must follow a normal distribution in the population.
* A normal distribution is the most important and widely used distribution in statistics.

---
.header[Inferential Statistic | Parametric Statistics]

## Normal Distribution

.center[<img src="../02_scripts/img/statistic/statistics_62.png" alt="statistics_62" style="width:85%;">]  
[[socialresearchmethods]](http://www.socialresearchmethods.net/kb/statinf.php)  


???
  

* The sampled data is roughly shaped as a bell curve or Gaussian curve. In other words, it is symmetric around its mean, median and mode (which are all equal). The area under the normal curve is equal to 1.0.
* It is important because we have to choose the right significance test and it can only be a parametric tests when the data is normally distributed. The significance test is necessary, so we know wether two or more samples are representative for the population.
* Their importance is partly due to the central limit theorem. It states that, under some conditions, the average of many samples (observations) of a random variable with finite mean and variance is itself a random variable—whose distribution converges to a normal distribution as the number of samples increases. Therefore, physical quantities that are expected to be the sum of many independent processes, such as measurement errors, often have distributions that are nearly normal.[4]
* In probability theory, the central limit theorem (CLT) establishes that, in many situations, for identically distributed independent samples, the standardized sample mean tends towards the standard normal distribution even if the original variables themselves are not normally distributed. 


---
.header[Inferential Statistics]

## Parametric Statistics

For parametric tests to work, we have to assume some underlying statistical distributions in the data:

* Normal distribution
    * [W/S test](http://article.sciencepublishinggroup.com/pdf/10.11648.j.ajtas.s.2017060501.19.pdf)
    * [Jarque-Bera test](https://en.wikipedia.org/wiki/Jarque%E2%80%93Bera_test)
    * [Shapiro-Wilks test](https://en.wikipedia.org/wiki/Shapiro%E2%80%93Wilk_test)
    * [Kolmogorov-Smirnov test](https://en.wikipedia.org/wiki/Kolmogorov%E2%80%93Smirnov_test)
    * [D’Agostino test](https://en.wikipedia.org/wiki/D%27Agostino%27s_K-squared_test)
* Homogeneity of variance
    * [Levene’s test](https://en.wikipedia.org/wiki/Levene%27s_test)


---
template:inverse

# Quantification of the Effect

---
.header[Inferential Statistics]

## Parametric Statistics

> How can we compare the means of two independent groups?

---
.header[Inferential Statistics | Parametric Statistics]

## t-Test

The two-sample test analyses two sample means 𝜇1 and 𝜇2.  


???
  

* Under the assumptions that the data is normal distributed and the homogeneity of variance is given, we then can use, for example a t-test for comparing two populations. The two-sample test analyses two population means 𝜇1 and 𝜇2. The t stands for the difference between means in relation to the variation in the data. It describes the degree to which those means differ by chance alone.

--

> Is there a statistical difference between the means of the two samples?
  
---
.header[Inferential Statistics | Parametric Statistics]

## t-Test
  
 
* One-sample: Compare one group to a give value

???
  

* Du möchtest herausfinden, ob deine Schokoladen-Riegel wirklich 300 Gramm im Durchschnitt wiegen, wie es auf der Packung steht. Um das zu testen, wiegst du 40 Riegel ab und vergleichst das tatsächliche Gewicht mit dem Gewicht, das sie haben sollten (300 Gramm).
* https://www.scribbr.de/statistik/t-test/

--
* Unpaired: Compare two group means from independent groups

???
  

* Du möchtest wissen, ob sich die durchschnittliche Größe von Männern von jener von Frauen unterscheidet.
* An unpaired t-test (also known as an independent t-test) compares the averages of two independent or unrelated groups to determine if there is a significant difference between the two. 

--
* Paired: Compare two group means from groups that are dependent


???


* Du misst die Größe derselben Person im Jahr 2015 und im Jahr 2018. Die dabei ermittelten Werte sind klar voneinander abhängig. Du verwendest einen abhängigen t-Test.
* A paired t-test (also known as a dependent or correlated t-test) compares the averages and standard deviations of two related groups to determine if there is a significant difference between the two groups. 
* Here, the two groups are paired or connected, e.g. participants before and after a treatment or a repeated-measure grouping, where all participants do all tasks.
* https://askanydifference.com/difference-between-t-test-and-p-value/

---
.header[Inferential Statistics | Parametric Statistics]

## t-Test

Most statistical software include p-value and t-test functions. It takes as input the raw data.

---
.header[Inferential Statistics | Parametric Statistics]

## t-Test

.left-even[<img src="../02_scripts/img/statistic/google_01.png" alt="google_01" style="width:45%;">]

.footnote[[Flandorfer, P. 2023. [Den T-Test verstehen und interpretieren mit Beispiel](https://www.scribbr.de/statistik/t-test/). Scribbr]]

???
  

* https://docs.google.com/spreadsheets/d/12dxoiJHh2vN-xhNrPD68xcMYDrZ8A_GTEbpZNP9Pxgc/edit?usp=sharing
* https://www.scribbr.de/statistik/t-test/
* https://docs.google.com/spreadsheets/d/1I3OARNrSNQ0lZqV4hnNj4yJZmBAaoB_jpgeN9-cKLog/edit#gid=997673686
* The independent t-test returns a value for the difference in means of the two conditions, t, with larger t values suggesting higher probability of the null hypothesis being false.  
* In other words, the higher the t value, the more likely the two means are different.

--
.right-even[<img src="../02_scripts/img/statistic/google_02.png" alt="google_02" style="width:100%;">]


???
  

* we get a value for the difference in means of ~-4.3, meaning there is an estimated change of 4.3%.


???
  

* Suppose you want to investigate the effect of caffeine on muscle metabolism.
* You work with 18 male volunteers and randomly assign them to two groups. In one group all men take a capsule containing pure caffeine, the men in the other group receive a placebo capsule. 
* The two groups are independent from each other and the independent-samples t test is appropriate for data analysis.


H<sub>0</sub>: The mean of the caffeine treatment equals the mean of the placebo  
H<sub>A</sub>: The mean of caffeine treatment is not equal to the mean of the placebo treatment.  


.center[<img src="../02_scripts/img/statistic/statistics_75.png" alt="statistics_75" style="width:100%;">]



* Now, all men underwent arm exercise tests. During each exercise the subject's respiratory exchange ratio (RER) was measured. RER is the ratio of CO2 produced to O2 consumed and is an indicator of whether energy is being obtained from carbohydrates or fats.



The independent t-test returns a value for the difference in means of the two conditions, t, with larger t values suggesting higher probability of the null hypothesis being false.  


In other words, the higher the t value, the more likely the two means are different.


---
.header[Inferential Statistics | Parametric Statistics]

## t-Test

Exemplary summary in a paper:

> The average height of women (M = 166.3; SD = 10.03) is lower than that of men (M = 183.1; SD = 11.21) with a significant difference of t(28) = -4.34 and p < 0.001.


.footnote[[Flandorfer, P. 2023. [Den T-Test verstehen und interpretieren mit Beispiel](https://www.scribbr.de/statistik/t-test/). Scribbr]]

???
  

* Bei unabhängigen Stichproben (beim Zweistichproben-t-Test) solltest du dabei auf jeden Fall folgende Parameter angeben:
* Mittelwert und Standardabweichung für beide Gruppen,
* t-Wert mit der Anzahl der Freiheitsgrade und
* Signifikanz (Sig.) des t-Tests.


---
.header[Inferential Statistics | Parametric Statistics]

## t-Test


.center[<img src="../02_scripts/img/statistic/statistics_76.png" alt="statistics_76" style="width:90%;">]  [[15]](http://learntech.uwe.ac.uk/da/Default.aspx?pageid=1438)  

???
  

* If we run an independent-samples t-test using the data set above, we get a value for the difference in means of ~6.4, meaning there is an estimated change of 6.4%.
  
Statistical software generates a summary table for the results, containing both the t-test results, additional test results that examine the data distribution and a p-value. 


---
.header[Inferential Statistics | Parametric Statistics]

## t-Test


.center[<img src="../02_scripts/img/statistic/statistics_77.png" alt="statistics_77" style="width:90%;">]  [[15]](http://learntech.uwe.ac.uk/da/Default.aspx?pageid=1438)  


*But* the p-value is 0.063 and, therefore, the difference between the two means is not statistically significantly different with a 5% level of significance.


???
  

* In this case, we would need to report as result that even though there is a change of 6.4% observed, it is insufficient evidence (p = 0.063) to generally conclude that caffeine does change the mean RER.
* The specific values returned from a software computation and how to use and interpret the given values is highly dependent from the specific package. When needed, decide on a software early on and make sure that you know how to input the data (layout, format?) and what to expect as output. This can take some time and effort, so please make sure to have enough time and brain power left to do this
* Again, keep in mind, that the t-test is only applicable for the comparison of two groups. If you want to test three or more parameter, you have to use a different statistical test.

---
.header[Inferential Statistics | Parametric Statistics]

## One-way ANOVA

???
  

* NOVA steht für Varianzanalyse (engl. Analysis of Variance) und wird verwendet um die Mittelwerte von mehr als 2 Gruppen zu vergleichen.
* Sie ist eine Erweiterung des t-Tests, der die Mittelwerte von maximal 2 Gruppen vergleicht.

* Many studies involve three or more conditions that need to be compared. Due to variances in the data, you should not directly compare the means of the multiple conditions and claim that a difference exists as long as the means are different. Instead, you have to use statistical significance tests to evaluate the variances that can be explained by the independent variables and the variances that cannot be explained by them. The significance test will suggest the probability of the observed difference occurring by chance. If the probability that the difference occurs by chance is fairly low (e.g., less than 5%), we can claim with high confidence that the observed difference is due to the difference in the controlled independent variables.

--
The comparison of more than *two* groups, based on *one* factor.

--
* The difference in height between soccer player, gymnasts, and volleyball players.
    * Factor: height in cm
    * Groups: soccer, gymnastics, and volleyball
--
* The the productivity of three or more employees based on working hours.
    * Factor: the productivity in working hours
    * Groups: three or more employees


???
  

* The one way Analysis of Variance (ANOVA) compares more than *two* groups, based on *one* factor. This means that there is only one independent variable.
* Collected soil uranium concentrations at three locations: Site A, Site B, and Site C.
    * Factor: the uranium concentration
    * Groups: three locations
* The hardness of four blends of paint
    * Factor: the hardness of paint
    * Groups: four blends of paint

---
.header[Inferential Statistics | Parametric Statistics]

## One-way ANOVA

Again, keep in mind that there are various requirements for the data:

* Normally distributed
* Homogeneity of variance
* Samples are independent

--

Then we test the following hypotheses:

H<sub>0</sub>: All means are equal.  
H<sub>A</sub>: *At least one* of the means is different from the others.

---
.header[Inferential Statistics | Parametric Statistics]

## One-way ANOVA


.center[<img src="../02_scripts/img/statistic/statistics_69.png" alt="statistics_69" style="width:70%;">]  


???
  

* https://docs.google.com/spreadsheets/d/1I3OARNrSNQ0lZqV4hnNj4yJZmBAaoB_jpgeN9-cKLog/edit#gid=1929990740
* The ANOVA test is based on the assumption that if the between group variance is much larger than the within group variance, then it seems more likely that the groups are different.  

---
.header[Inferential Statistics | Parametric Statistics]

## Two-way ANOVA

The [two way ANOVA](https://en.wikipedia.org/wiki/Two-way_analysis_of_variance) can compare more than two groups, based on *two* factors. 
  
This means that there are two independent variables, e.g., compare the employee productivity based on the working hours *and* some quality measure of their results.


???
  

* We will not get into this any further. If you need this test at some point, please investigate it properly.

---
.header[Inferential Statistics]

## Non-Parametric Statistics

--

Non-parametric methods make fewer assumptions about the data. They are also called *assumption-free* tests.


???
  

* E.g. if your data is not distributed normally.
* Although nonparametric tests are also called *assumption-free* tests, it should be noted that they are not actually free of assumptions. For example, the [Chi-squared test](https://en.wikipedia.org/wiki/Chi-squared_test), one of the most commonly used nonparametric tests, has specific requirements on the sample size and independence of data points. 
* Non-parametric analysis sacrifices the power to use all available information to reject a false null hypothesis in exchange for less strict assumptions about the data.
* Another important message to note about nonparametric analysis is that information in the data can be lost when the data tested are actually interval or ratio. 
* The reason is that the nonparametric analysis collapses the data into ranks so all that matters is the order of the data while the distance information between the data points is lost. 

---
## Choosing a Statistical Test

--

Planing the statistical analysis should be an integral part of designing a study!

--

You should answer the following questions in advance:

* What kind of data?
* How many independent variables? 
* Independent measure or repeated measure design?
* Is the data parametric or non-parametric?


???
  

* Depending on what you already know, you can easily find guidelines on which statistical test to chose, such as the following for example.

---
## Choosing a Statistical Test

.center[<img src="../02_scripts/img/statistic/statistics_80.png" alt="statistics_80" style="width:64%;">]  

---

## Inferential Statistics

--

> Statistical analysis is a powerful tool that helps us find interesting patterns and differences in the data as well as identify relationships between variables, enabling us to make assumptions about a population. 
  
--
  
Before running significance tests, the data needs to be cleaned up, coded, and appropriately organized to meet the needs of the specific statistical software package. 


???
  

* The nature of the data collected and the design of the study determine the appropriate significance test that should be used.  
  
---

## Inferential Statistics
  

> Do not underestimate the effort you need to put into using methods of inferential statistics!


???
  

* If the data is normally distributed, parametric tests, such as a t-test or an ANOVA, are appropriate. When the normal distribution requirements are not met, nonparametric tests should be considered.  
* This section about inferential statistic left you probably with many open questions and you might now feel a bit scared about inferential statistic. Good 🙃... What I mean with this is that you must be aware of the complexity of inferential statistics and that you need to invest time and effort to use it properly. 
* The topic is, however, absolutely worth it, as it might lead to meaningful results. And ultimately, with this chapter as a starting point, giving you all the important keywords, and with a somewhat structured approach, inferential statistic is quite conquerable after all! 💪🏼







---
template:inverse

## The End

# 👋🏻
