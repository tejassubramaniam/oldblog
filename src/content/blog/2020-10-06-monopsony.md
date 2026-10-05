---
title: "Minimum wages in a monopsony"
pubDate: 2020-10-06
slug: economics/monopsony
---
A well-known result in microeconomics is that a monopsony in a labor market produces a deadweight loss (assuming it does not wage-discriminate), leading to the counterintuitive result that some binding minimum wage levels might *increase* both employment and wages. 

![A graph illustrating the welfare costs of a monopsony.](https://upload.wikimedia.org/wikipedia/commons/thumb/8/81/Monopsony-welfare-effects.svg/800px-Monopsony-welfare-effects.svg.png) 

*The deadweight loss of a monopsony. [CC BY 2.5](https://creativecommons.org/licenses/by/2.5/), SilverStar at English Wikipedia.*

(I promise we won’t be talking about this graph at all. It’s just for the aesthetic.)

When initially learning economics, I found it hard to grasp this concept intuitively. I recently consulted [Perloff (2020)](https://www.pearson.com/us/higher-education/program/Perloff-My-Lab-Economics-with-Pearson-e-Text-Access-Card-for-Microeconomics-Theory-and-Applications-with-Calculus-5th-Edition/PGM2569046.html), [Varian (2014)](https://www.wwnorton.co.uk/books/9780393690019-intermediate-microeconomics-with-calculus-a-modern-approach), [Landsburg (2013)](https://www.amazon.com/Price-Theory-Applications-Economics-Titles/dp/1285423526), and other textbooks searching for an answer that explained this without mathematics or graphs and didn’t find anything – so I thought I would try to articulate my understanding of this. I’m not sure this explanation is correct: it’s just my attempt at roughly translating the math to English, and I would appreciate if anyone could correct me on inaccuracies. 

A monopsonist is a single consumer of a good or service, often in a market with many suppliers. In a labor market, that is a single employer, with many workers willing to supply their labor. 

In a competitive market (i.e., many employers and prospective employees), standard economic theory suggests that imposing a binding minimum wage would decrease employment, because firms would lay off workers to compensate for the increased cost of labor. The empirical research is mixed on this question (and indeed, on the question of whether labor markets are competitive or monopsonistic/oligopsonistic). Here’s a good post on this subject by [Trevor Chow](https://tmychow.com/blog/2020/08/05/\$15-minimum-wage).

A monopsonistic market – as you may have guessed – is more complicated. So let’s (re)build a model. I’ll outline some assumptions first. This is a single labor market – for example, a labor market in a particular type of worker (someone who does the same job). The employer pays every employee of this type the same wage. This seems reasonable – since workers do not have an incentive to accurately report their reservation wage (the lowest wage at which they are willing to work), a monopsonist does not have a metric by which to wage-discriminate. Furthermore, there are tangible barriers on many blue-collar employers from wage discriminating – including unions, legislation, fear of backlash, common labor contracts, and so on.

Back to a competitive labor market for a moment. In a competitive labor market, with many employers competing for workers and many employees competing for jobs, the wage in the market will end up (1) being the same and (2) equalling the marginal revenue product of labor (MRPL, which is the marginal increase in revenue from hiring an additional worker). (1) is true because if one employer pays a higher wage, every other employer will lose out on workers and be forced to raise their wages. If one employer pays a lower wage, they will either lose access to their workers (forcing it to raise its wage) or operate at a higher profit than others (forcing others to lower their wage). In the end, wages will normalize to be about the same. This is the [Law of One Price](https://en.wikipedia.org/wiki/Law_of_one_price). (2) is true because an employer is making a loss if the wage is significantly above the MRPL, while if the wage is significantly below the MRPL, the worker will find an alternative job (since there are many employers competing). 

This isn’t true in a monopsonistic labor market. If workers have no (or few) alternatives, then an employer will pay a wage less than the MRPL – because they can. This is a simple syllogism: the profit-maximizing wage for a firm with no competition is less than the profit-maximizing wage for a firm that does compete for workers, and we’ve established that the profit-maximizing wage is the MRPL for a firm that does compete. Now, remember: the MRPL is how much the firm *values* the worker (approximately) – it is how much a marginal worker would bring in. But a firm has chosen a profit-maximizing wage less than how much it values a marginal worker. That suggests that there are workers willing to work for a wage just incrementally below their additional revenue product, but who are not willing to work at the monopsonistic employer’s current wage. The monopsonist has a choice. Either they raise wages for *everybody* (since wages have to be the same, per our assumptions) to get these people to work, or they don’t hire some workers (hiring whom would give them a surplus) because it would mean raising the costs of keeping *everyone else*. Hence, many monopsonists would choose not to hire these workers.

This is a deadweight loss. There is a trade to be made that, on its own, would benefit both parties – the workers would get a job a bit above their reservation wage and employers would hire people a bit below how much they value their work. However, the implication it has for the wages of *other employees* (whom a monopsonistic employer can *afford* to pay below the MRPL) means the employer doesn’t maximize a profit when it hires everyone willing to work at below the employer’s value for a worker. 

You can now see how a minimum wage set at the MRPL would likely increase employment for such a monopsonist. If the government sets a binding minimum wage at the MRPL for each worker, then a monopsonist would have to pay all its existing workers the MRPL. That means hiring these new workers *does not* mean raising everyone else’s wage – so the monopsonist makes the decision on whether to hire a new worker solely on whether the wage they’re willing to accept is less than the value they offer the monopsonist. Since there are some workers who meet this condition who were not hired earlier, they are hired now.

This also means a minimum wage set a bit above the MRPL has an ambiguous effect on employment. It has two counteracting effects – one increasing employment and one decreasing it, and which one of these effects dominates depends on how high the minimum wage is set.

## Comments (from the original WordPress site)

**shivesh** · 2020-10-08

> hey i think whether the monopsonist will hire new employees or not depends on how many workers the monopsonist has too. my reasons to believe the same is marginal productivity of labour reduces as more workers are hired so the first few employees to be hired will have a higher chance to get more than their reservation wages.  
> apart from this setting the minimum wages at MRPL implies that wages for every additional labour hired fall as MRPL falls as every additional labour is hired , isn't this contradictory form your primary assumption that you will not price discriminate because clearly different employees doing the same job get different prices ultimately

**Tejas** · 2020-10-14

> Thanks for the comment/for reading!
>
> I agree that employers have an *incentive* to wage discriminate (i.e., that would be profitable for them), since the MRPL of each worker points. But when employers *can’t* wage discriminate due to the constraints I mention in the post (such as a lack of knowledge of a worker’s actual reservation wage, unions, labor contracts, government regulations, etc.), they set a common wage for every worker. So yeah, wage-discrimination would eliminate the deadweight loss and be more profitable to the employer because labor has diminishing marginal returns – the point is that a monopsonist has a deadweight loss when there are constraints that prevent wage discrimination. (Admittedly, these constraints often don’t exist, in which case this post – and indeed, textbook 101 monopsony models – are not very relevant.)
