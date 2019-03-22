# Statistics

**Statistics** is the science of **changing your mind under uncertainty**. 

If you have all the data you’re interested in, there’s no need for fancy [statistical methods](http://bit.ly/quaesita_statistics). 
Making decisions based on facts (parameters) is hard enough as it is, but sometimes we don’t even have the facts we need. Instead, what we know (our sample) is different from what we wish we knew (our [population](http://bit.ly/quaesita_popwrong)). That’s what it means to have [uncertainty](http://bit.ly/quaesita_savvy).

## Types of data: Qualitative vs. Quantitative

We have two types of data:
- qualitative (e.g. words)
- quantitative (numerical information e.g. result on a test or rating your satisfaction with Airbnb service on a scale of 1 to 5)

## Research design

How are you going to go & analyse data you have depends on:

**The research design**

This is the first and most important step. It means you will think about all possible questions, problems, or obstacles you might run into in your experiment.

### 1. Independent vs. Dependent variable

You have to think about what you want to measure. _What are your independent variables?_

- **Independent variable** is the one that experimenter changes (in literature you will often see the word manipulates) with assumption it will have a direct effect on the dependent variable
- **Dependent variable** is the one that experimenter measures. It is the outcome/result of the study.

### 2. Direct vs. Indirect measures

Are you measuring your variables directly or indirectly?
- **Directly** would mean you are for ex. interested in how many times a day a person uses the sentence “Thank you”. You would just count all the times you would hear the person say these words. 
- **Indirectly** would be when you would count the number of times the person uses this sentence. But in this case you would actually be interested in how agreeable is this person. You would hypothesis that they are more agreeable if they use the sentence often. 

### 3. Between vs. Within Groups & Matched pairs
In what kind of conditions are you measuring independent measures? 
- Are you measuring between or within groups? Are your measures independent or repeated/within groups? Or are you measuring with matched pairs?
  - Between / independent = each condition of the independent variable uses different participants
  - Within / repeated = the same participants take part in each condition of the independent variable
  - Matched pairs: Each condition uses different participants, but they are matched in terms of important characteristics, e.g., gender, age, intelligence, etc.

**4. Are you measuring change over time or one-time event?**

### 5. The type of variables you have**
- Categorical
  - Nominal: two or more categories (e.g. gender, race, …)
  - Ordinal: also presents categories, but this is a variable with categories that can be put in logical order (e.g. the highest level of education completed, age group, …) 
- Continuous: any score or value within a measurement scale
  - Interval: a variable that can be ordered & in which the distance/level between each category is equal and static
    - Example: temperature
  - Ratio: this one is similar to an interval variable, but with one difference. A ratio variable needs to have a clear “zero” point.
    - Example: height, weight, distance, age
    - _Someone who weights 60kg is twice as heavy as someone with 30kg._

### 6. The distribution of the data

- **normal distribution** means that “most people” score results around the middle
- **non-normal distribution** means that your data doesn’t fit into the bell curve
  - Example from nature: bacteria growth in nature follows exponential growth. This potentially means that first you have a small number of bacteria and the growth is slow. Once the number “hit” a threshold this growth will become exponential or better said it will “fly through the roof”. But … I’m pretty sure you know what exponential means ;)
  - Sometimes this is also due to outliers that skew your data. 
    - For ex. outliers: you have 5 people in the company earning ridiculous money & it will look like your average salary of 200 people in the company is 3x higher as it would be if you would eliminate these 5 people.

_All right … back to the original point. (I promise this long introduction will help you understand the following better)._

## Hypothesis

**_Hypotheses_ are descriptions of what the world might look like.**
[For example](http://bit.ly/quaesita_fisher): “We can walk to class together (default action) if you usually take under 15 minutes to get ready (null hypothesis), but if the evidence (data) suggests it’s longer (alternative hypothesis), you can walk by yourself because I’m outta here (alternative action).”
All of [hypothesis testing](http://bit.ly/quaesita_damnedlies) is all about asking: _"Does our evidence make the null hypothesis look ridiculous?"_

Statistics rarely give a simple Yes/No type answer to the question under analysis. Interpretation often comes down to the level of statistical significance and often refers to the probability of a value accurately rejecting the null hypothesis (sometimes referred to as the [p-value](https://en.wikipedia.org/wiki/P-value)).ž

### How do we test hypothesis?

#### Difference between the means of variables
This includes tests such as **_t_-test & ANOVA**.

**_Example:_** You have a group of girls and a group of boys. You want to check if boys are on average taller than girls. For this you will use independent t-test.

#### Correlations between two variables
_Do two things have a mutual connection or relationship, in which one thing affects or depends on another?_

_**Example:**_ height is positively correlated with weight. This means that taller people are usually also heavier than short people.

#### _p_-value

When you look it p-value, and if it is low it tells "there is something that you didn't expect”. The lower the _p_-value, the more the data are yelling, _“Whoa, that’s surprising, and you need to update your beliefs!"_

## Descriptive statistics
... tell us about the basic qualities of the data. 

Some statistics that are part of the “descriptives” are:
- Minimum (the lowest/smallest score in a data set)
- Maximum (the highest/largest score in a data set)
- Range (the difference between the min & max)
- Frequency (the number of times a certain value appears)
- Measures of Central Tendency
  - Mean (the average or the sum of values divided by the number of values)
  - Median (the value separating the higher half from the lower half of a dataset; so it is the middle value after you set your numbers in order)
  - Mode (the most frequent value in a dataset)
  - _Examples:_ your dataset consists of seven scores or data points {1, 2, 3, 3, 4, 5, 9}
    - Mean: (1+2+2+3+4+5+9)/7 = 3,71 … 
    - Median: (1+2+2+3+4+5+9) => 3
    - Mode: (1+2+2+3+4+5+9) => 2

## Multivariate Analysis

The multiple linear regression explains the relationship between one dependent variable/predicter (y) and two or more independent variables (x1, x2, x3… etc).

**_Example:_** we want to know what predicts team effectiveness. We have collected data on how well every member is at recognizing emotions of others, how well they understand their own emotions, and how empathic they are. At the same time, we measured how well they collaborate together & what is their level of team effectiveness. 

Our regression model/receipt would look something like this: 
Team effectiveness = constant + beta1*recognising_emotions +beta2*understanding_own_emotions + b3*empathy + b4*collaboration + error

So recognising emotions, understanding them, ability to empathise and collaborate would all be predictors (so in total four predictors). For each predictor we would get approx. percentage of how much of team effectiveness they can explain & how good the model will predict the effectiveness of the team. 

**Non-parametric tests** are used when data doesn’t meet the rules (e.g. data is not distributed normally) to use parametric tests but are measuring more or less the same thing.

**_Myth:_**  Stat is magic that makes certainty out of uncertainty. There’s no magic that can do that; you can still make mistakes. 

## Chosing the right statistical test

When choosing statistical tests in psychology _(or anywhere really :))_ you have to account for:
- Sample size
- Number of independent & dependent variables
- Normality of the distribution
- Everything we mentioned earlier! (research design, type of variables, …) 

## The important aspect of psychological measuring

What are the most important aspects of measuring any fuzzy stuff _"correctly"_ & repeatably or measurement characteristics of psychophysical methods:

1. **Objectiveness:** it means the results are dependent only on reactions of our participant (and not on how we interpret it)

2. **Sensitivity of the method:** we have chosen the right method for measuring the problem we are interested in (e.g. we are not going to do 1000 interviews to understand what kind of personality someone has - instead we are going to develop an assessment for it) & we are able to efficiently differentiate between the characteristics we are measuring. 

3. **Reliability:** it is connected to objectiveness & sensitivity of the method. We say that the method is more reliable when we get similar results in repeated measuring of the same characteristic. It presents the variability of the results in time.
    - How is the sensitivity connected to reliability? If we have completely insensitive method (so we are measuring the construct in a completely wrong way) this method will give the same results every time we measure e.g. personality traits, and we are going to be to fast to conclude that our method is super reliable when in reality it isn't.

4. **Validity of the method:** it comes after all later three. The method is only valid when it actually measure the thing it is supposed to measure. This is why in psychology the most important part is to know the theory behind it well & be awesome in operationalizing your variables/concepts/constructs/etc. 
