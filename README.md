# Investing for retirement

Hopefully this section can illustrate the impressive power of compounding growth which makes comfortable retirement possible. Let's start with a broad overview of how to think about long-run investing and financial independence.

Factors over which you exercise some control include:
* Income during your working years and changes in income over time;
* Allocation and timing of investments;
* Use of [tax-advantaged accounts](https://github.com/investindex/TaxAdv);
* Where you live;
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
* Federal tax rates;  
* Government benefits like Social Security and Medicare, which may change by the time you retire.

The daunting scope of retirement planning may provoke some people who haven't thought much about the arc of their life plan to start to consider some important questions. What do you value about money and what do you want to do with it? How much is enough? How much time and how many years do you want to spend working for pay? After approaching financial independence, is there something you would enjoy doing that pays less or nothing at all? 

Although there are variables you cannot control, like federal tax rates, you can adjust variables which are under your control, like savings rates, to make it more likely that you’ll be prepared for an uncertain future. There are also factors which are under your control to a great degree, except in rare situations. Health is a perfect example: most people have the opportunity to reduce expected health care costs by keeping themselves healthy, but it is always possible to be dealt an unavoidable illness or injury. As discussed in the [previous section](https://github.com/investindex/Guidelines/tree/main#minimize-risk-of-catastrophic-loss), this falls in the category of potentially catastrophic risks you can insure yourself against.

Many of these variables can be entered into an online retirement calculator like [this one](https://www.bankrate.com/retirement/calculators/retirement-plan-calculator/). Basic calculators give you an idea of how your saving and investing will add up in the long run, and whether they can sustain you during retirement. There are many factors that can't be explicitly included in these calculators, like unexpected support you may need to provide to children or aging parents in middle age, and potentially [very high](http://fidelityinvestments2020news.q4web.com/press-releases/news-details/2022/Fidelity-Releases-2022-Retiree-Health-Care-Cost-Estimate-65-Year-Old-Couple-Retiring-Today-Will-Need-an-Average-of-315000-for-Medical-Expenses/default.aspx) medical costs in old age. These calculations are inevitably based on rough assumptions. But working out imprecise numbers is far better than the vague assumptions that would take their place. Planning your future will also demonstrate how useful it is to keep track of your spending. Exactly how much do you spend on food? How much does car maintenance cost? You will be able to project future spending far more accurately if you record and categorize your current spending. You may also be able to target areas in which you’re spending more than you thought.

I don't recommend relying on calculators like the one above. Nor would I propose using misleading rules of thumb like [this one](https://www.fidelity.com/viewpoints/retirement/how-much-do-i-need-to-retire). It suggests that I should have the equivalent of my salary saved by 30, and three times my salary saved by 40. Perhaps this could be sensible for someone who started working at 22. For a boarded physician with a negative net worth at 30 but very high earning potential, it is nonsense that has the potential to promote confusion and financial anxiety. Some of the math needed for retirement planning is more advanced than many people are used to, but it's important to understand the assumptions behind the numbers that guide your saving and investing. So we'll review the calculations needed for retirement planning in detail.

&nbsp;

### Les mathématiques

It's essential to understand compounding growth, so watch [this video](https://www.youtube.com/watch?v=ACbu4XER_bQ&list=PLENfNwrAryOiK4QF3Ot8PZdZ-Vcx07HAP) if you aren't sure you completely understand it. Let's walk through a few math problems based on compounding growth that everyone should know how to do.

If a $500 investment earns an average annual return of 7.5% for 30 years, how much is that investment worth at the end of the period? To indicate 7.5% growth in one year, we would multiply the initial amount by 1.075. To indicate an average 7.5% annual return over 30 years, we multiply by 1.075 30 times: 1.075^30 = 8.75496. Now we know that 7.5% average annual growth over 30 years is equivalent to multiplying by 8.75496, so we calculate the final balance as $500 × 8.75496 = [$4,377.48](https://www.wolframalpha.com/input?i=500*1.075%5E30).

If a $300 investment grew to $9,083.15 over 40 years, what was the average annual return? We reverse the process above. First we must find the factor by which the investment grew: 9,083.15/300 = [30.2772](https://www.wolframalpha.com/input?i=9083.15%2F300). Now we can ask, what average return is needed to multiply an investment by 30.2772 over 40 years? We want the number which solves the equation x^40 = 30.2772. So we calculate x = 30.2772^(1/40) = [1.089](https://www.wolframalpha.com/input?i=%289083.15%2F300%29%5E%281%2F40%29). This indicates an average annual return of 8.9%.

If over three years our investments provide annual returns of 7%, 15.5%, and -2%, what is the average annual return? We must convert these percentage changes to multipliers: 1.07, 1.155, and .98. The geometric mean is calculated as (1.07×1.155×.98)^(1/3) = 1.0659, a 6.59% average annual return. The geometric mean of annual returns is often called the compound annual growth rate ([CAGR](https://www.investopedia.com/terms/c/cagr.asp)). If it's unclear, see this footnote<sup id="fn1">[[1]](#f1)</sup> for why the calculation must be done this way.

Next, how does [inflation](https://www.investopedia.com/terms/i/inflation.asp) work when calculating returns? Let's say we project an 8% average annual return over 40 years, so the asset will be multiplied by 1.08^40 = 21.7. This is our nominal return, which is distinguished from the real return — that which remains after accounting for inflation. With average 2.5% inflation, the real return is calculated as 1.08/1.025 = 1.0537, or 5.37%. This gives us a real multiplier over 40 years of 1.0537^40 = 8.1. So instead of imagining that your money will multiply by 21.7, remember that your dollars will be worth less in 40 years, and the multiplier will feel much more like 8.1 (under these assumptions). If this shrinking multiplier is discouraging, imagine how your dollars would decay if you didn't invest at all: (1/1.025)^40 = .37. They would lose 63% of their purchasing power over 40 years! An 8% nominal return converts that multiplier of .37 to 8.1.

Finally, how can we find the savings needed to spend a given amount during retirement, while accounting for inflation and investment earnings? First we need to decide how much we'd like to be able to spend in terms of today's dollars. It's not easy to predict spending desires decades in advance, let alone the funds you'll need to set aside for [health care](http://fidelityinvestments2020news.q4web.com/press-releases/news-details/2022/Fidelity-Releases-2022-Retiree-Health-Care-Cost-Estimate-65-Year-Old-Couple-Retiring-Today-Will-Need-an-Average-of-315000-for-Medical-Expenses/default.aspx) and potentially for beneficiaries. One reminder may be comforting. Because you no longer need to save money once you've retired, the "income" you require from investments and Social Security for a particular standard of living is inherently lower than the income needed during working years. If a 68-year-old retires and was making $75K/year while saving $25K/year, they need only $50K/year to support the same lifestyle (in fact, even less due to reduced taxes). Many retirement experts find that overall retirement spending tends to be around 70-80% of pre-retirement spending.

Let's imagine that we want a comfortable annual "income" of $60,000 in today's dollars by drawing from our investments and receiving Social Security old age benefits. It's difficult to estimate your Social Security benefits if you're young, because benefits depend on your income throughout life as well as whether benefits will be fully funded. Both of these variables are uncertain. We've used the government's [website](https://www.ssa.gov/benefits/retirement/estimator.html) to estimate that someone with our income would receive about $20K per year from Social Security if they retired today and applied for benefits at full retirement age (currently 67). But the latest official [report](https://t.co/hHgTKxE26t) expects that, due to revenue shortfalls, old age benefits will be reduced by roughly 24% around 2034. (Any alarmist predictions about future retirees receiving nothing needs to contend with the fact that new money is added to the trust funds every year. Benefit payouts can never be zero unless Congress changes the rules.) So we'll anticipate only three-quarters of the payments we're supposed to receive (around $15K). We'll rely on our investments for the remaining $45K.

These amounts are expressed in today's dollars, because that's what we can relate to — $161K of inflated dollars 40 years in the future is not intuitive. We decide that we'll commit to withdrawing an average of 4% of the nest egg per year (withdrawal strategies are addressed below). An average 4% withdrawal of $45K translates to a nest egg of 45,000×(100/4) = 1,125,000 at the beginning of retirement. Assuming 2.5% average inflation for 40 years, cumulative inflation would be a factor of 1.025^40 = 2.685. The cumulative inflation factor multiplied by $1.125M is [$3.02M](https://www.wolframalpha.com/input?i=1125000*1.025%5E40). That's the actual dollar amount we're aiming for in 40 years to provide a standard of living similar to $45K/year today. How can we reach it?

There are many ways of doing so. We'll describe the simplest first. We save and invest [$8,080](https://www.wolframalpha.com/input?i=ReplaceAll%5B%28D%2F%28W*R%5ET%29-A%29+%2F+Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%2C+%7BR+-%3E+1.08%2F1.025%2C+G+-%3E+1%2C+T+-%3E+40%2C+D+-%3E+45000%2C+W+-%3E+.04%2C+A+-%3E+0%7D%5D) the first year, and every year we increase that amount by our anticipated average inflation rate, 2.5%. So in the second year we save $8,080×1.025 = $8,241, and so on until we save [$21,165](https://www.wolframalpha.com/input?i=8079.63*1.025%5E39) in the 40th year. We'll have saved [$544,588](https://www.wolframalpha.com/input?i=Sum%5B8079.63*1.025%5EY%2C+%7BY%2C+0%2C+39%7D%5D) and, if our nominal returns are 8%, built a nest egg of $3.02M by the end of the 40th year. See this footnote<sup id="fn2">[[2]](#f2)</sup> for how to calculate the first year's target using this approach as well as the next one. You can do so easily by changing the variables in a [formula](https://www.wolframalpha.com/input?i=ReplaceAll%5B%28D%2F%28W*R%5ET%29-A%29+%2F+Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%2C+%7BR+-%3E+1.08%2F1.025%2C+G+-%3E+1%2C+T+-%3E+40%2C+D+-%3E+45000%2C+W+-%3E+.04%2C+A+-%3E+0%7D%5D) I typed into WolframAlpha.

The figure below illustrates this process. It shows our cumulative contributions to retirement savings (black) as well as the value of our nest egg as it grows over time with various rates of return (colors). Notice how the value of the nest egg explodes near the end, increasing more in the last 10 years than in the first 30 years. This is how any exponential process looks, but it underlines the importance of beginning as early as possible. Every year delayed is one year less of that ever-accelerating explosion at the end. Of course, there will be a great deal of volatility in the colorful lines — stock market returns are not smooth.
&nbsp;

&nbsp;

<p align="center">
<img src="https://github.com/investindex/Retirement/blob/main/Retirement%20Plot.png"/>
</p>

&nbsp;

A variation on the first approach is to increase savings each year by last year's inflation, rather than an assumed long-term average inflation rate like 2.5%. This is a good idea, but of course when planning you will find yourself doing the same calculations because you cannot know what each year's inflation will be. If a given year has unusually low inflation, you may want to adhere to your assumed long-term rate anyway, to be safe.

This first approach could be called time-invariant or flat: you contribute the same inflation-adjusted amount every year. This is advantageous because the more you frontload your retirement savings, the less you need to save overall. In the example above, we contributed only [18%](https://www.wolframalpha.com/input?i=544587.69%2F3020696.82) of the final nest egg and investment took care of the rest. In other words, more than four out of every five dollars were the fruits of investing! If you could put away even more in your early life than this approach would suggest, that would be great. But many people need to do the opposite: they cannot save much until later in life. So we could design an approach in which we increase savings each year in addition to inflation, to acknowledge the growth in ability to save.

Imagine the same conditions as described above, but we increase savings each year by 2% on top of 2.5% for inflation. Our target savings in the first year will be only [$6,109](https://www.wolframalpha.com/input?i=ReplaceAll%5B%28D%2F%28W*R%5ET%29-A%29+%2F+Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%2C+%7BR+-%3E+1.08%2F1.025%2C+G+-%3E+1.02%2C+T+-%3E+40%2C+D+-%3E+45000%2C+W+-%3E+.04%2C++A-%3E+0%7D%5D), a 24% reduction from the flat approach above. In the second year we save $6,109×1.02×1.025 = $6,387. In the 40th year we need to save [$34,642](https://www.wolframalpha.com/input?i=6108.87%281.02*1.025%29%5E39), a 64% increase compared to the first example. Investment still does most of the work for us: we save about [22%](https://www.wolframalpha.com/input?i=661735.28%2F3020696.82) of the $3.02M. But it turns out to be a lot more in absolute terms: we had to put away [$661,735](https://www.wolframalpha.com/input?i=Sum%5B6108.87%281.02*1.025%29%5EY%2C+%7BY%2C+0%2C+39%7D%5D) using this approach, an increase of about $117,000 or 21.5%. We saved more to build the same wealth in this example, but it is a more realistic model for many people. An interesting twist for people who can frontload their savings would be to _decrease_ inflation-adjusted savings each year. For example, someone who frontloads so that they make the same contribution every year would need to save only [$10,797](https://www.wolframalpha.com/input?i=ReplaceAll%5B%28D%2F%28W*R%5ET%29-A%29+%2F+Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%2C+%7BR+-%3E+1.08%2F1.025%2C+G+-%3E+1%2F1.025%2C+T+-%3E+40%2C+D+-%3E+45000%2C+W+-%3E+.04%2C+A+-%3E+0%7D%5D) each year, for all 40 years! Although they would be saving the same dollar amount each year, they're frontloading because they're saving less each year in real terms. The total savings needed to reach the $3.02M goal would be only [$431,864](https://www.wolframalpha.com/input?i=Sum%5B10796.6%281%2F1.025*1.025%29%5EY%2C+%7BY%2C+0%2C+39%7D%5D) ([14%](https://www.wolframalpha.com/input?i=431864%2F3020696.82) of the total).

You may find it useful to reverse this process and convert certain savings patterns into retirement income. This footnote<sup id="fn3">[[3]](#f3)</sup> explains how to use the WolframAlpha calculator linked [here](https://www.wolframalpha.com/input?i=ReplaceAll%5BW*R%5ET*%28A%2BS*Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%29%2C+%7BS+-%3E+6108.87%2C+G+-%3E+1.02%2C+R+-%3E+1.08%2F1.025%2C+T+-%3E+40%2C+W+-%3E+.04%2C+A+-%3E+0%7D%5D). Anyone interested in how the equation is derived can click [here](https://github.com/investindex/Retirement/blob/main/Retirement.pdf).

&nbsp;

### What can we learn from the math?

First: the earlier in life a financial sacrifice is made to save money for retirement, the more potent that act will be. $1,000 invested at an average 8% return until age 75 becomes:
* $4,700 if saved at age 55
* $10,100 if saved at age 45
* $21,700 if saved at age 35
* $46,900 if saved at age 25

We can also use the flat method of saving to illustrate how important it is to start early. In our example, the first year savings target is $8,080 with a 40-year horizon. But with 30 years the figure is $15,088; with 20 years it is $31,062; and with 10 years it is $83,449. When you start late, you give your capital less time to appreciate. In addition, allowing yourself more time implies that your average return will tend to revert to long-term expected returns. The average return of someone with a timeline of only 10 or 15 years will be strongly influenced by idiosyncratic trends and events; their results may be fantastic or underwhelming. For example, someone investing in the cap-weighted US market only from 2000-2009 would have been disappointed, whereas someone investing only from 2010-2019 would have experienced a dazzling run-up. The average return of someone with a timeline of 30 or 40 years is more predictable, in the neighborhood of [8% for the stock market](https://github.com/investindex/Risk#f1). We will discuss in the [next section](https://github.com/investindex/Portfolio) how to increase expected returns above 8% through diversification beyond the cap-weighted total market.

Of course, it is many people's financial reality that they cannot save large amounts of money at a young age. The point here is not to wag a finger at them, but to emphasize the importance of saving and investing as early as possible within the constraints of your situation.

A high savings rate in your early career has [another benefit](https://www.whitecoatinvestor.com/6-reasons-to-have-a-high-early-savings-rate/): it helps tame hedonic adaptation. The initial years of your career will likely see the most drastic improvements in the living standards you can afford. You'll (hopefully) be able to buy more of everything you want, and some people respond by spending every raise. Living well below your income forces you to consider what you value spending money on, and lets you load up on savings (or quickly pay off debt) while you're young.

Second: the plot shows that a difference of even one percentage point in average returns makes an enormous difference to lifetime wealth. Even half a percentage point can easily amount to hundreds of thousands of dollars! And, of course, investing doesn't end at retirement age.

Third: if your spending closely matches your income, you will appear to be living within your means. But failing to save for an eventual goal of financial independence means that the appearance of spending responsibly is superficial. An ever-deepening well of savings is not only necessary for retirement: it also gives you the freedom to not rely on the next paycheck to sustain your lifestyle. __The ability to make decisions without the pressure of imminent financial need is one of the great rewards of building wealth.__ There is a lot more to saving than maximizing your wealth at age 70.

&nbsp;

The assumptions of the examples above are open to question: someone might object to a 4% average withdrawal rate or 2.5% anticipated inflation. See [these](https://www.youtube.com/watch?v=z7rH7h7ljHg) [videos](https://www.youtube.com/watch?v=3BScK-QyWIo) on safe withdrawal rates. [This post](https://earlyretirementnow.com/2017/03/15/the-ultimate-guide-to-safe-withdrawal-rates-part-11-criteria/) is part of a detailed discussion of different withdrawal strategies. When learning about withdrawal approaches, keep in mind that many calculations depend on an assumed portfolio of 50% cap-weighted stocks and 50% intermediate bonds. A retirement portfolio with a higher stock allocation is expected to tolerate higher withdrawal rates. Later sections discuss how to build a stock and bond portfolio, and the [advanced topics](https://github.com/investindex/Advanced) cover additional asset classes.

Your retirement plan should be robust: it shouldn't collapse if stock returns are only 7% during your working years. (However, as [Wade Pfau](https://www.financialplanningassociation.org/sites/default/files/2020-05/4%20Safe%20Savings%20Rates%20A%20New%20Approach%20to%20Retirement%20Planning%20over%20the%20Life%20Cycle_0.pdf) has pointed out, someone who experienced below-average stock returns during their working years may reasonably expect above-average returns during retirement, and vice versa.) If returns fall short, you may have to be prepared to work longer, increase your withdrawal rate, or decrease your spending. "Plan B" actions can include part-time work; reducing large expense categories like restaurants and certain kinds of travel; leaving less to children or charity; moving into a smaller home or to an area with lower cost of living; and forgoing major luxuries like a boat, a second residence, or expensive vehicles. The best way to avoid making financial compromises like these is to save to a degree that you hope is excessive, and invest with modest expectations. Give yourself the capacity to be flexible: don't fixate on a precise retirement date, or rely on above-average investment returns to meet your basic goals.

&nbsp;

There are some notes to keep in mind.

<b>(1)</b> Annual savings targets like $8,080 don't all come from your paycheck. Employer contributions in your work retirement plan might account for several hundred to some thousands of dollars, depending on your income and their matching policy. Once you add your own contributions, this minimum 401(k) activity can put a large dent in the savings you need. Some employers also contribute to your [HSA](https://github.com/investindex/TaxAdv#health-savings-account-hsa).

<b>(2)</b> The risky, long-term portfolio I [suggest](https://github.com/investindex/Fund/blob/main/README.md#example-portfolios) is made up of stocks and long-duration bonds. Many people cannot psychologically tolerate the volatility associated with that portfolio, even in a retirement account they won't touch for 20 years. So they allocate partly to less risky assets like aggregate bond funds. If you do this, projections for your portfolio's long-term growth must be lowered accordingly. Of course, as you approach within eight or ten years of retirement, you may want to begin adding some lower-risk bonds to your portfolio. The lower expected returns due to this transition were not considered in the simple examples above, but they could be accounted for by doing calculations for multiple periods.

<b>(3)</b> If you're decades from retirement, you can't anticipate the precise age at which you'll stop working full-time. That's okay: <b>retirement is a financial status, not an age</b>. You don't have to know when you'll retire, but you should form an approximate goal for the age at which you'll have the _option_ to retire. This could be 40, 60, or 75. Just keep in mind that the older your target retirement age, the more likely it becomes that unexpected obstacles will make it harder to keep earning. Retiring earlier than 65 carries the challenge of paying for health insurance during the gap between group health insurance with an employer and enrolling in Medicare at 65. You can't collect Social Security until age 62, and every month you wait to enroll until age 70 will augment your monthly payments for the rest of your life.

<b>(4)</b> Taxes are an essential part of retirement planning. The [section on taxes](https://github.com/investindex/Taxes#tax-efficient-investing) discusses various techniques for tax-efficient investing. Your expected return could be 8% before taxes but, if you're investing in a taxable account, gains are undercut whenever they're realized. So the most important factor is how much you contribute to tax-advantaged accounts. Moreover, remember that money in your traditional IRA is pre-tax, so using withdrawals from a traditional IRA to generate a $45K "income" is very different than doing the same with a Roth IRA. The best approach is to use [a combination](https://github.com/investindex/Taxes#roth-or-traditional) of Roth and traditional accounts.

<b>(5)</b> During retirement, investments are highly subject to [sequence risk](https://www.forbes.com/advisor/retirement/sequence-of-returns-risk/), whereby poor returns are more harmful to a portfolio if they occur early rather than after some period of positive returns. If a retired person's portfolio experiences a large, protracted drawdown, then they need to withdraw a much larger fraction of their portfolio to maintain the same spending. Although the stock market recovers, the parts of the portfolio which were withdrawn never get a chance to recover.<sup id="fn4">[[4]](#f4)</sup> If depleting your assets is a concern, then flexible spending during retirement is important. In particular, reducing withdrawals when stocks have fallen enhances the longevity of your assets. A large allocation to low-risk bonds early in retirement is one way to defend against sequence risk. Another is to continue earning income for some time. Even 10% or 15% of your pre-retirement income made doing something you enjoy augments the compounding of your investments because it reduces your need to withdraw from them.

I recommend this [interview with Michael Kitces](https://www.youtube.com/watch?v=5dbPdCdFRrs) on a variety of retirement topics, including sequence risk and approaches to spending. Larry Swedroe and Kevin Grogan's [book on retirement](https://libgen.rs/search.php?req=Swedroe+Grogan+Your+Complete+Guide+to+a+Successful+and+Secure+Retirement&open=0&res=25&view=simple&phrase=1&column=def) provides good coverage of all the major retirement considerations.

&nbsp;

[Click here for the next section — Guidelines for personal finance](https://github.com/investindex/Guidelines)

&nbsp;

All sections:

* [Cover page](https://github.com/investindex/Intro)
* [Introduction to index funds](https://github.com/investindex/Index)
* [Thinking about risk](https://github.com/investindex/Risk)
* [Tax-advantaged accounts](https://github.com/investindex/TaxAdv)
* [Your psychology](https://github.com/investindex/Psychology)
* [Investing for retirement](https://github.com/investindex/Retirement)
* [Guidelines for personal finance](https://github.com/investindex/Guidelines)
* [Building a stock portfolio](https://github.com/investindex/Portfolio)
* [Fund proposals](https://github.com/investindex/Fund/blob/main/README.md)
* [Advice](https://github.com/investindex/Advice)
* [Practical information for execution](https://github.com/investindex/Practical)
* [Taxes](https://github.com/investindex/Taxes)
* [Vocabulary and further resources](https://github.com/investindex/Vocab)
* [Advanced topics](https://github.com/investindex/Advanced)

&nbsp;

&nbsp;

Footnotes:

<sup id="f1"> 1 </sup> For some people it may not be obvious why the more common arithmetic mean is unsuitable. Perhaps we could have found the average return like this: (7+15.5-2)/3 = 6.83 or (1.07+1.155+.98)/3 = 1.0683. To consider this, we can imagine an unlikely sequence of returns, in which we double our money the first year and halve it the following year. Multiplying an asset by 2 and then .5 returns it to its original value. We can calculate the geometric mean of these multipliers, which we know intuitively should be 1: (2×.5)^(1/2) = 1. That's right, but the arithmetic mean gives us an incorrect answer, (2+.5)/2 = 1.25. Another way of checking this is finding that the average return matches the actual return. 1.07×1.155×.98 = 1.21, which equals 1.0659^3. The arithmetic mean of 1.0683 does not satisfy this test. Because we are averaging multiplicative factors, the geometric mean must be applied. [↩](#fn1)

&nbsp;

<sup id="f2"> 2 </sup> You can [click here](https://www.wolframalpha.com/input?i=ReplaceAll%5B%28D%2F%28W*R%5ET%29-A%29+%2F+Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%2C+%7BR+-%3E+1.08%2F1.025%2C+G+-%3E+1.02%2C+T+-%3E+40%2C+D+-%3E+45000%2C+W+-%3E+.04%2C+A+-%3E+0%7D%5D) to use a formula I set up in WolframAlpha. There are six variables. Five were already discussed: R for annual real return, T for years until retirement, D for desired retirement income in today's dollars, W for withdrawal rate, and G for inflation-adjusted annual growth of savings. G is introduced in the second approach to saving; to use the flat approach, set G equal to 1. The sixth variable is A, savings which already exist. The examples above assume no savings are set aside for retirement yet, but we can easily add this to the equation. R is the nominal return rate divided by inflation rate, 1.08/1.025 in the example above. To see how the equation is derived, [click here](https://github.com/investindex/Retirement/blob/main/Retirement.pdf). [↩](#fn2)

&nbsp;

<sup id="f3"> 3 </sup> The WolframAlpha calculator for calculating retirement income based on savings is [here](https://www.wolframalpha.com/input?i=ReplaceAll%5BW*R%5ET*%28A%2BS*Sum%5B%28G%2FR%29%5EY%2C+%7BY%2C+0%2C+T-1%7D%5D%29%2C+%7BS+-%3E+6108.87%2C+G+-%3E+1.02%2C+R+-%3E+1.08%2F1.025%2C+T+-%3E+40%2C+W+-%3E+.04%2C+A+-%3E+0%7D%5D). If a flat approach is desired, set G equal to 1 to effectively remove it. The variable S is the savings target in the first year. [↩](#fn3)

&nbsp;

<sup id="f4"> 4 </sup> An attentive reader might wonder if the same applies to building the nest egg during working years. One of the assumptions used in my calculations was not only that the average annual nominal return was 8%, but that the nominal return _every year_ was 8%. Yet there are unlimited combinations of annual returns whose average is 8%. Couldn't some of those combinations result in a nest egg that is significantly smaller or larger than the one I calculated? The short answer is that as long as the average ends up close to 8%, it's not a concern. Any plausible sequence of returns that has the same average annual return will produce a similar outcome during the accumulation phase. Spending during retirement poses different problems. [↩](#fn4)

&nbsp;

The WolframAlpha formula to calculate savings from desired retirement income is:

ReplaceAll[(D/(W\*R^T)-A) / Sum[(G/R)^Y, {Y, 0, T-1}], {R -> 1.08/1.025, G -> 1, T -> 40, D -> 45000, W -> .04, A -> 0}]

And to calculate retirement income from savings:

ReplaceAll[W\*R^T\*(A+S\*Sum[(G/R)^Y, {Y, 0, T-1}]), {S -> 6108.87, G -> 1.02, R -> 1.08/1.025, T -> 40, W -> .04, A -> 0}]

&nbsp;

&nbsp;

&nbsp;

&nbsp;
