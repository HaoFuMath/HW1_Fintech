# Homework 1: Fintech Intro

## Overview and Origin

* Name of company

* When was the company incorporated?
- > RobinHood 
* Who are the founders of the company?
- >Vladimir Tenev and Baiju Bhatt

* How did the idea for the company (or project) come about?
- > Robinhood was founded in April 2013 by Vladimir Tenev and Baiju Bhatt, who had previously built high-frequency trading platforms for financial institutions in New York City.The company's name comes from its mission to "provide everyone with access to the financial markets, not just the wealthy". Tenev noted that executing a trade cost brokerages "fractions of a penny" but they typically charged fees of $5 to $10 per trade, as well as required account minimums of $500 to $5,000.
* How is the company funded? How much funding have they received?
- >In April 2017, Robinhood raised $110 million at a $1.3 billion valuation led by Yuri Milner of DST Global, Greenoaks Capital, and Thrive Capital. On May 10, 2018, Robinhood closed a $363 million Series D financing round led by DST Global. As of May 2018, Robinhood raised a total of $539 million in venture capital funding, with the last valuation at $5.6 billion, up from their previous valuation of $1.3 billion. In May 2019, reports from Bloomberg and other outlets publicized Robinhood's pursuit of an additional $200 million in funding, which could value the company in the $7 billion to $10 billion range. In November 2019, Robinhood announced its expansion to the United Kingdom.
In May 2020, it was announced that Robinhood had raised $280 million in venture funding at a pre-money valuation of $8.3 billion led by Sequoia Capital, and 3 months later, the company announced a $200 million Series G funding round from a new investor, D1 Capital Partners, on August 17.

## Business Activities:

* What specific financial problem is the company or project trying to solve?
- > They are trying to build products that would provide everyone with access to the financial markets, not just the wealthy. So to speak, free of charges for investors exploring the markets.
* Who is the company's intended customer?  Is there any information about the market size of this set of customers?
What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
- > The firm’s target customer base is young people new to investing, who are drawn to the app by advertising that leans heavily on words such as "free" and "democratization." By and large, this tactic has succeeded, drawing in 10 million accounts held by an unknown number of customers. Compared with Fidelity Investments which continues to evolve as a major force in the online brokerage space, Robinhood allows you to trade cryptocurrencies in the same account that you use for equities and options, which is unique.
* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
One of their curretly-used technologies is dynamic configuration.
At Robinhood, they built the first version of dynamic configuration back in early 2016. They leveraged Zookeeper watches to push changes at a process level across our various services. They stored these variables in memory and relied on Zookeeper’s strong consistency to ensure that writes They're durable. Over time, the usage of the dynamic configuration system expanded and while the original architecture was simple, They started reaching scaling limits both in terms of the size of the configuration desired as well as the number of reads They could perform on the existing architecture. As They set out to re-architect this critical piece of infrastructure, They took the opportunity to look at a lot of the design decisions from scratch to ensure that our design would meet the needs of Robinhood today as well as through the next period of growth.

## Landscape:

* What domain of the financial industry is the company in?
- > Stock and ETF trading, Cryptocurrency trading, Banking.

* What have been the major trends and innovations of this domain over the last 5-10 years?
- > Robinhood showed that even that was essentially gouging, and that year the company pushed the trend in trading costs to its theoretical limit: zero.
* What are the other major companies in this domain?
- > Fidelity Investments.

## Results

* What has been the business impact of this company so far?
- > Not only are some amateur Robinhood traders making money – as a group, they are creating enough traffic to impact entire segments of the market.As a result, large investors are quickly learning that their traditional techniques for riding out volatile markets won’t work.This phenomenon, now referred to as the “Robinhood Effect”, is challenging the status quo and driving significant changes in the strategies available to experienced investors. In short, the Robinhood Effect is a term that describes irrational stock price movements caused by retail traders buying stocks without regard to their fundamentals.

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?
- >The company is so successful in part because of how easy the interface is to use. The app provides its largely novice base access to trading more complicated instruments like options.
Based on those metrics, the company is/was successful.
* How is your company performing relative to competitors in the same domain?
- > 1. Usability: 
- - Fidelity is quite friendly to use overall. The firm has addressed the challenge of having the tools for active traders while still having an easy experience for basic investors by essentially splitting its offering into two platforms. Initial account opening with Fidelity is simple, especially if you're adding an account to an existing household. However, adding on account features such as options trading or margin involves filling out an additional application, and none of that data (such as your occupation) is copied from your profile, so you have to enter it again.
- - Robinhood is very easy to navigate and use, but this is related to its overall simplicity. Robinhood's app and the website are similar in look and feel, which makes it easy to invest through either interface. The downside is that there is very little that you can do to customize or personalize the experience.
- > 2. Range of Offerings
- - Fidelity clients can trade a wide swath of assets on the website and on Active Trader Pro. Equities (including fractional shares), options and mutual funds can be traded on the mobile apps. One notable limitation is that Fidelity does not offer futures, futures options, or cryptocurrency trading. 
- - Robinhood allows you to trade cryptocurrencies in the same account that you use for equities and options, which is unique, but it's missing quite a few asset classes, such as fixed income. Robinhood allows fractional share trading in nearly 7,000 stocks and ETFs.

## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
- > I would personally suggest they could be able to open up foreign stock market, such as European and Asian which are also large and potential target.

* Why do you think that offering this product or service would benefit the company?
- >Because in that way, more investors could be attracted and in return, more revenue would be generated.

* What technologies would this additional product or service utilize?
- > I would suggest using blockchain technique would be beneficial to the company.
* Why are these technologies appropriate for your solution?
- > Because blockchain coule provide greater transparency, increased efficiency, better security and improved traceability, which are crucial and beneficial to international transactions.



https://en.wikipedia.org/wiki/Robinhood_(company)
https://www.investopedia.com/robinhood-review-4587919
https://www.investopedia.com/fidelity-vs-robinhood-4587945
https://robinhood.engineering/a-simple-implementation-of-dynamic-configuration-71383bcc803b
https://money.usnews.com/investing/investing-101/articles/how-robinhood-changed-an-industry
https://financhill.com/blog/investing/robinhood-effect-on-stock-market#:~:text=Not%20only%20are%20some%20amateur,entire%20segments%20of%20the%20market.&text=In%20short%2C%20the%20Robinhood%20Effect,without%20regard%20to%20their%20fundamentals.