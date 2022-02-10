# Investing for retirement

Hopefully this section can illustrate the impressive power of compounding growth which makes comfortable retirement possible. Let's start with a broad overview of how to think about long-run investing and retirement.

Factors over which you exercise some control include:  
* Income during your working years and changes in income over time;  
* Allocation and timing of investments;  
* Use of [tax-advantaged accounts](https://github.com/investindex/Guidelines#tax-advantaged-accounts);  
* At what age you may merge finances with a long-term partner;  
* At what age you may have children;  
* Support you expect to provide to and receive from your family;  
* How much you will spend, save, and invest during working years;  
* How much you will change your spending after retirement;  
* How you will change your investment approach after retirement;  
* Age of retirement;  
* Whether you retire suddenly or continue earning a smaller income for some time;  
* Personal goals such as charitable donations or leaving money for your children.

Factors over which you exercise little or no control include:  
* [Asset class](https://www.investopedia.com/terms/a/assetclasses.asp) returns for stocks and bonds;  
* Inflation rates;  
* Interest rates;  
* Tax rates;  
* Government benefits like Social Security, which may change by the time you retire.

The daunting scope of retirement planning may provoke some people who haven't thought much about the arc of their life plan to start to consider some important questions. What do you value about money and what do you want to do with it? How much is enough? How much time and how many years do you want to spend working for pay? After approaching financial independence, is there something you would enjoy doing that pays less or nothing at all? 

Although there are variables you cannot control, like federal tax rates, you can adjust variables which are under your control, like savings rates, to make it more likely that you’ll be prepared for an uncertain future. There are also factors which are under your control to a great degree, except in rare situations. Health is a perfect example: most people have the opportunity to reduce expected health care costs by keeping themselves healthy, but it is always possible to be dealt an unavoidable illness or injury. As discussed in the [previous section](https://github.com/investindex/Guidelines/tree/main#minimize-risk-of-catastrophic-loss), this falls in the category of potentially catastrophic risks you can insure yourself against.

Many of these variables can be entered into an online retirement calculator like [this one](https://www.bankrate.com/retirement/calculators/retirement-plan-calculator/). Basic calculators give you an idea of how your saving and investing will add up in the long run, and whether they can sustain you during retirement. There are many factors that can't be explicitly included in these calculators, like unexpected support you may need to provide to children or aging parents in middle age, and potentially [very high](https://newsroom.fidelity.com/press-releases/news-details/2021/Fidelitys-20th-Annual-Retiree-Health-Care-Cost-Estimate-Hits-New-High-A-Couple-Retiring-Today-Will-Need-300000-to-Cover-Medical-Expenses-an-88-Increase-Since-2002/default.aspx) medical costs in old age. These calculations are inevitably based on rough assumptions. But working out imprecise numbers is far better than the vague assumptions that would take their place. Planning your future will also demonstrate how useful it is to keep track of your spending. Exactly how much do you spend on food? How much does car maintenance cost? You will be able to project future spending far more accurately if you record and categorize your current spending. You may also be able to target areas in which you’re spending more than you thought.

I don't recommend relying on calculators like the one above (or rules of thumb like [this](https://www.fidelity.com/viewpoints/retirement/how-much-do-i-need-to-retire)). Some of the math needed for retirement planning is more advanced than many people are used to, but it's important to understand the assumptions behind the numbers that guide your saving and investing. So we'll review the calculations needed for retirement planning in detail.

&nbsp;

### Les mathématiques

We can begin with a simple matter of computing average return. If over three years our investments provide annual returns of 7%, 15.5%, and -2%, what is the average annual return? We must convert these percentage changes to multipliers: 1.07, 1.155, and .98. The geometric mean is calculated as (1.07×1.155×.98)^(1/3) = 1.0659, a 6.59% average annual return. See this footnote for why it must be calculated that way.<sup id="fn1">[1](#f1)</sup>

Second, how does [inflation](https://www.investopedia.com/terms/i/inflation.asp) work when calculating returns? We can calculate growth over time based on an anticipated average rate of return. If we assume a 9% average annual return over 40 years, the asset will be multiplied by 1.09^40 = 31.4. This is our nominal return, which is distinguished from the real return — that which remains after accounting for inflation. With average 2.5% inflation, it is calculated as 1.09/1.025 = 1.0634, or a 6.34% real return. This gives us a real multiplier over 40 years of (1.09/1.025)^40 = 11.7. So instead of imagining that your money will multiply by 31.4, remember that your dollars will be worth less in 40 years, and the multiplier will feel much more like 11.7. If this shrinking multiplier is discouraging, imagine how your dollars would decay if you didn't invest at all: (1/1.025)^40 = .372. They would lose 63% of their purchasing power over 40 years! A 9% nominal return converts that multiplier of .37 to 11.7.

Finally, how can we find the savings needed to spend a given amount during retirement, while accounting for inflation and investment earnings? Let's imagine that we want an annual "income" of $60,000 in today's dollars by drawing from our investments and receiving Social Security payments. The $60K accounts not only for discretionary spending, but also for increased health care costs and other potentially large expenses in old age. Keep in mind that this is for an individual — a married couple would need to spend more, but probably not twice as much. We've used the government's [calculator](https://www.ssa.gov/benefits/retirement/estimator.html) and estimated that our middle-class income will entitle us to about $15K per year from Social Security. We'll rely on our investments for the remaining $45K. These amounts are expressed in today's dollars, because that's what we can relate to — $161K of inflated dollars 40 years in the future is not intuitive. We decide that we'll commit to withdrawing an average of 3.5% of the nest egg per year, reducing withdrawals slightly when our investments drop in value and potentially increasing them when our investments perform very well. An average 3.5% withdrawal of $45K translates to a nest egg of 45,000×(100/3.5) = 1,285,714. Assuming 2.5% average inflation for 40 years, $1.29M in today's dollars would be multiplied by 1.025^40 to give $3.45M. That's the actual dollar amount we're aiming for in 40 years to provide a standard of living similar to $45K/year today. How can we reach it?

There are many ways of doing so. We'll describe the simplest first. We save and invest $7,167 the first year, and every year we increase that amount by our anticipated average inflation rate, 2.5%. So in the second year we save $7,346, and so on until we save $18,774 in the 40th year (calculated as 7,166.97×1.025^39). If our nominal returns are 9% as expected, then we'll have saved [$483,072](https://www.wolframalpha.com/input/?i=Sum%5B7166.97*1.025%5EY%2C+%7BY%2C+0%2C+39%7D%5D) and built a nest egg of $3.45M by the end of the 40th year. See this footnote<sup id="fn2">[2](#f2)</sup> for how to calculate the first year's target using this approach as well as the next one. You can do so easily by changing the variables in a [formula](https://www.wolframalpha.com/input/?i=ReplaceAll%5B%28D%2F%28W*R%5ET%29-A%29+%2F+Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%2C+%7BR+-%3E+1.09%2F1.025%2C+G+-%3E+1%2C+T+-%3E+40%2C+D+-%3E+45000%2C+W+-%3E+.035%2C+A+-%3E+0%7D%5D) I typed into WolframAlpha.

The figure below illustrates this process. It shows our cumulative contributions to retirement savings (purple) as well as the value of our nest egg as it grows over time (red). Notice how the value of the nest egg explodes in the last ten years. This is how any exponential process looks, but it underlines the importance of beginning as early as possible. Every year delayed is one year less of that ever-growing explosion at the end. Of course, there will be a great deal of volatility in the red line — stock market returns are not smooth.

&nbsp;

<p align="center">
<img src="https://github.com/investindex/Retirement/blob/main/Retirement%20Plot.png" width="630" height="540"/>
</p>

&nbsp;

A variation on the first approach is to increase savings each year by last year's inflation, rather than an assumed long-term average inflation rate like 2.5%. This is a good idea, but of course when planning you will find yourself doing the same calculations because you cannot know what each year's inflation will be. If a given year has unusually low inflation, you may want to adhere to your assumed long-term rate anyway, to be safe.

This first approach could be called time-invariant or flat: you contribute the same inflation-adjusted amount every year. This is advantageous because the more you frontload your retirement savings, the less you need to save overall. In the example above, we contributed only 14% of the final nest egg and investment took care of the rest. In other words, six out of every seven dollars were the fruits of investing! If you could put away even more in your early life than this approach would suggest, that would be great. But many people need to do the opposite: they cannot save much until later in life. So we could design an approach in which we increase savings each year in addition to inflation, to acknowledge the growth in ability to save.

Imagine the same conditions as described above, but we increase savings each year by 2% on top of 2.5% for inflation. Our target savings in the first year will be only $5,531, a 23% reduction from the flat approach above. In the second year we save $5,531×1.02×1.025 = $5,783. In the 40th year we need to save $31,366, a 67% increase compared to the first example (calculated as 5,531.23(1.02×1.025)^39). Investment still does most of the work for us: we save about 17% of the $3.45M. But it turns out to be a lot more in absolute terms: we had to put away [$599,163](https://www.wolframalpha.com/input/?i=Sum%5B5531.23%281.02*1.025%29%5EY%2C+%7BY%2C+0%2C+39%7D%5D) using this approach, an increase of $116,000 or about 24%. We worked harder to build the same wealth in this example, but it is a more realistic model for many people. An interesting twist for people who can frontload their savings would be to _decrease_ inflation-adjusted savings each year. For example, someone who frontloads so that each year's inflation-adjusted decrease precisely counteracts their 2.5% increase for inflation would need to save only [$9,374](https://www.wolframalpha.com/input/?i=ReplaceAll%5B%28D%2F%28W*R%5ET%29-A%29+%2F+Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%2C+%7BR+-%3E+1.09%2F1.025%2C+G+-%3E+1%2F1.025%2C+T+-%3E+40%2C+D+-%3E+45000%2C+W+-%3E+.035%2C+A+-%3E+0%7D%5D) each year, for all 40 years! The total savings needed to reach the $3.45M goal would be only [$374,944](https://www.wolframalpha.com/input/?i=Sum%5B9373.61%281%2F1.025*1.025%29%5EY%2C+%7BY%2C+0%2C+39%7D%5D) (less than 11% of the total).

You may find it useful to reverse this process and convert certain savings patterns into retirement income. This footnote<sup id="fn3">[3](#f3)</sup> explains how to use the WolframAlpha calculator [here](https://www.wolframalpha.com/input/?i=ReplaceAll%5BW*R%5ET*%28A%2BS*Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%29%2C+%7BS+-%3E+5531.23%2C+G+-%3E+1.02%2C+R+-%3E+1.09%2F1.025%2C+T+-%3E+40%2C+W+-%3E+.035%2C+A+-%3E+0%7D%5D). Anyone interested in how the equation is derived can click [here](https://github.com/investindex/Retirement/blob/main/Retirement.pdf).

We can use the first method to illustrate how important it is to start early. Our first year savings target is $7,167 if we have a 40-year horizon, but with 30 years the figure is $14,398; with 20 years it is $31,680; and with 10 years it is $90,267. If someone started very early in life and had 50 years until retirement, their first savings target would be a mere $3,716. When you start late, you give your capital less time to appreciate. In addition, allowing yourself more time implies that your average return will tend to revert to long-term expected returns. The average return of someone with a timeline of only 10 or 15 years will be strongly influenced by idiosyncratic trends and events; their results may be fantastic or underwhelming. For example, someone investing in the cap-weighted US market only from 2000-2009 would have been disappointed, whereas someone investing only from 2010-2019 would have experienced a dazzling run-up. The average return of someone with a timeline of 30 or 40 years is more predictable, in the neighborhood of [8% for the stock market](https://github.com/investindex/Risk#f1). We will discuss in the [next section](https://github.com/investindex/Portfolio) how to improve expected returns through diversification beyond the cap-weighted total market.

The assumptions of the examples above are open to question: someone might object that a 3.5% average withdrawal rate is overly conservative, or that 2.5% anticipated inflation is not conservative enough. Indeed, a 3.5% withdrawal rate is conservative and, as long as you allocate mostly to stocks, means that your assets are likely to grow over time despite withdrawals. Withdrawals as high as 5% in early retirement may be considered. See [these](https://www.youtube.com/watch?v=z7rH7h7ljHg&ab_channel=BenFelix) [videos](https://www.youtube.com/watch?v=3BScK-QyWIo&ab_channel=BenFelix) on safe withdrawal rates. And indeed, you should calculate what your retirement plan looks like in a future with poor returns and high inflation. Imagine 7.5% nominal stock market returns and 3.5% inflation, yielding a real annual return of 3.86% (1.075/1.035 = 1.0386). The 40-year real multiplier drops from 11.7 in our example above to only 4.6. This is a very pessimistic projection, but it is important to test the limits of your retirement planning with unlikely yet possible futures like these.

&nbsp;

There are some notes to keep in mind.

<b>(1)</b> Annual savings targets like $7,167 don't all come from your paycheck. Employer matching in your 401(k) might account for several hundred to some thousands of dollars, depending on your income. Once you add your own contributions, this minimum 401(k) activity can put a large dent in the savings you need.

<b>(2)</b> It is hard to predict the spending levels you'll desire decades in advance, as well as the funds you'll need to set aside for health care and beneficiaries. One reminder may be comforting. Because you no longer need to save money once you've retired, the "income" you require from investments and Social Security for a particular standard of living is inherently lower than the income needed during working years. If a 68-year-old retires and was making $75K/year while saving $25K/year for retirement, they need only $50K/year to support the same lifestyle (in fact, slightly less due to taxes). Many retirement experts find that overall retirement spending tends to be around 70-80% of pre-retirement spending.

<b>(3)</b> Many people cannot psychologically tolerate the volatility of a 100% stock portfolio, even in a retirement account they won't touch for 20 years. If you choose to include bonds in your portfolio, projections for its long-term growth must be lowered accordingly. Of course, as you approach within eight or ten years of retirement, it's a good idea to begin adding bonds to the portfolio. The goal might be a 60/40 allocation by retirement, so someone could convert 5% of the portfolio to bonds each year for eight years. But a sensible composition depends on many factors, and 60/40 is not appropriate for everyone. The lower expected returns due to this transition were not considered in the simple examples above, but they could be accounted for by doing calculations for multiple periods.

<b>(4)</b> Taxes are an essential part of retirement planning. When investing in a taxable account, take advantage of tax rates for [long-term capital gains](https://github.com/investindex/Taxes) as often as possible. If your taxable investing returns 10% annually and you pay 15% on the gains, your actual returns were 8.5%. Your projections have to account for this. Set aside as much as possible in tax-advantaged accounts, because the investment earnings will not be undercut by taxation during your working years. At the same time, remember that money in your traditional IRA is pre-tax, so using withdrawals from a traditional IRA to generate a $45K "income" is very different than doing the same with a Roth IRA. In the process of deciding on the income and nest egg size you want, you need to estimate how much you plan to contribute to (and withdraw from) Roth and traditional accounts. The order in which you withdraw from different accounts can also matter, because people don't tend to spend uniformly throughout retirement. The [retirement smile](https://retirementresearcher.com/retirement-spending-smile) describes the tendency for spending to slowly decline, and then rise in very old age. It matters if you withdraw variable amounts in different years because the total amount you pay in tax will be affected. Accounting for all this is not easy, and there's no expectation that anyone will do it with precision. But awareness of these factors is better than ignorance.

<b>(5)</b> During retirement, investments are highly subject to [sequence risk](https://www.forbes.com/advisor/retirement/sequence-of-returns-risk/), whereby poor returns are more harmful to a portfolio if they occur early rather than after some period of positive returns.<sup id="fn4">[4](#f4)</sup> If depleting your assets is a concern, then flexible spending during retirement is important. In particular, reducing withdrawals when stocks have fallen enhances the longevity of your assets. A large allocation to bonds early in retirement is one way to defend against sequence risk. Another is to continue earning income for some time. Even 10% or 15% of your pre-retirement income made doing something you enjoy augments the compounding of your investments because it reduces your need to withdraw from them. I recommend this [interview with Michael Kitces](https://www.youtube.com/watch?v=5dbPdCdFRrs&ab_channel=TheRationalReminderPodcast) on a variety of retirement topics, including sequence risk and approaches to spending.

&nbsp;

[Click here for the next section — Building a stock portfolio](https://github.com/investindex/Portfolio)

&nbsp;

All sections:

* [Cover page](https://github.com/investindex/Intro)
* [Introduction to index funds](https://github.com/investindex/Index)
* [Thinking about risk](https://github.com/investindex/Risk)
* [Your psychology](https://github.com/investindex/Psychology)
* [Guidelines for financial planning](https://github.com/investindex/Guidelines)
* [Investing for retirement](https://github.com/investindex/Retirement)
* [Building a stock portfolio](https://github.com/investindex/Portfolio)
* [Fund proposals](https://github.com/investindex/Fund/blob/main/README.md)
* [Concerns for the small investor](https://github.com/investindex/Small)
* [Concerns for the large investor](https://github.com/investindex/Large)
* [Practical information for execution](https://github.com/investindex/Practical)
* [Taxes](https://github.com/investindex/Taxes)
* [Vocabulary and further resources](https://github.com/investindex/Vocab)

&nbsp;

&nbsp;

Footnotes:

<sup id="f1"> 1 </sup> For some people it may not be obvious why the more common arithmetic mean is unsuitable. Perhaps we could have found the average return like this: (7+15.5-2)/3 = 6.83 or (1.07+1.155+.98)/3 = 1.0683. To consider this, we can imagine an unlikely sequence of returns, in which we double our money the first year and halve it the following year. Multiplying an asset by 2 and then .5 returns it to its original value. We can calculate the geometric mean of these multipliers, which we know intuitively should be 1: (2×.5)^(1/2) = 1. That's right, but the arithmetic mean gives us an incorrect answer, (2+.5)/2 = 1.25. Another way of checking this is finding that the average return matches the actual return. 1.07×1.155×.98 = 1.21, which equals 1.0659^3. The arithmetic mean of 1.0683 does not satisfy this test. Because we are averaging multiplicative factors, the geometric mean must be applied. [↩](#fn1)

&nbsp;

<sup id="f2"> 2 </sup> You can [click here](https://www.wolframalpha.com/input/?i=ReplaceAll%5B%28D%2F%28W*R%5ET%29-A%29+%2F+Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%2C+%7BR+-%3E+1.09%2F1.025%2C+G+-%3E+1.02%2C+T+-%3E+40%2C+D+-%3E+45000%2C+W+-%3E+.035%2C+A+-%3E+0%7D%5D) to use a formula I set up in WolframAlpha. There are six variables. Five were already discussed: R for annual real return, T for years until retirement, D for desired retirement income in today's dollars, W for withdrawal rate, and G for inflation-adjusted annual growth of savings. G is introduced in the second approach to saving; to use the flat approach, set G equal to 1. The sixth variable is A, savings which already exist. The examples above assume no savings are set aside for retirement yet, but we can easily add this to the equation. R is the nominal return rate divided by inflation rate, 1.09/1.025 in the example above. To see how the equation is derived, [click here](https://github.com/investindex/Retirement/blob/main/Retirement.pdf). [↩](#fn2)

&nbsp;

<sup id="f3"> 3 </sup> The WolframAlpha calculator for calculating retirement income based on savings is [here](https://www.wolframalpha.com/input/?i=ReplaceAll%5BW*R%5ET*%28A%2BS*Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%29%2C+%7BS+-%3E+5531.23%2C+G+-%3E+1.02%2C+R+-%3E+1.09%2F1.025%2C+T+-%3E+40%2C+W+-%3E+.035%2C+A+-%3E+0%7D%5D). If a flat approach is desired, set G equal to 1 to effectively remove it. The variable S is the savings target in the first year. [↩](#fn3)

&nbsp;

<sup id="f4"> 4 </sup> An attentive reader might wonder if the same applies to building the nest egg during working years. One of the assumptions used in my calculations was not only that the average annual nominal return was 9%, but that the nominal return _every year_ was 9%. Yet there are unlimited combinations of annual returns whose average is 9%. Couldn't some of those combinations result in a nest egg that is significantly smaller or larger than the one I calculated? The short answer is, as long as the average ends up close to 9%, it's not a concern.

A longer answer: the best way to observe the range of possibilities would be to simulate many 40-year series of stock market returns. The issue is that we would have to decide on a distribution from which to draw random values, and there is no consensus on which distribution best fits stock market returns — the normal distribution certainly does not. But any plausible sequence of returns that has the same average annual return will produce a similar outcome. The crucial difference is that during retirement, you withdraw from the portfolio. If a retired person's portfolio experiences a large, protracted drawdown, then they need to withdraw a much larger fraction of their portfolio to maintain the same spending. Although the stock market recovers, the parts of the portfolio which were withdrawn never get a chance to recover. The accumulation phase faces no such challenge.

So while the idea that stock market returns will be the same every year is utterly unrealistic, it works as a mathematical assumption in the retirement calculator. Spending during retirement poses different problems. [↩](#fn4)

&nbsp;

The WolframAlpha formula to calculate savings from desired retirement income is:

ReplaceAll[(D/(W\*R^T)-A) / Sum[(G/R)^Y, {Y, 0, T-1}], {R -> 1.09/1.025, G -> 1, T -> 40, D -> 45000, W -> .035, A -> 0}]

And to calculate retirement income from savings:

ReplaceAll[W\*R^T\*(A+S\*Sum[(G/R)^Y, {Y, 0, T-1}]), {S -> 5531.23, G -> 1.02, R -> 1.09/1.025, T -> 40, W -> .035, A -> 0}]

&nbsp;
