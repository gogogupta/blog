---
layout: post
title: Confidence Level or p value
truncated_preview: true
excerpt_separator: <!--more-->
---
<div class="message">
Writing notes helps me think more clearly. I share them in case someone spots a gap in my thinking.
</div>

Understanding p value can be confusing. People who get it have an edge over those who don’t.

To make it easier, don’t focus too much on the p-value because it is not very intuitive. Instead, focus on the confidence level, which is simply 1 - p.

Confidence Level (CL) tells us the probability that the experiment worked or that your idea is successful. If it is higher than 95%, it means there is enough evidence that the experiment worked.

<!--more-->
For example, if your p-value is 0.04, then CL = 0.96. That means your experiment likely worked.

Think of it like this:

1. High p means the experiment likely failed
2. High CL (or low p) means the experiment likely succeeded

Use CL to make decisions. It is more intuitive and helps your team move faster.

## Basics of p-value / Confidence Interval

Every experiment starts with a hypothesis. For example: “Adding Feature X will improve LTV.”
To test this, we create a null hypothesis, which is the opposite: “Adding Feature X does not improve LTV.”

The p-value tells us how likely the null hypothesis is true.

1. If p is low (less than 5 percent), we reject the null. So, your idea likely worked.
2. If p is high, we keep the null. Your idea probably didn’t work.

## Examples

1. Suppose you think drinking green tea in the morning helps you stay more alert during the day. You ask 100 people to try this for a week and record their focus levels. You compare this with another group that didn't drink green tea.
After running the data, you get a p-value of 0.03.
That means CL = 0.97 (≥ 95%). It means green tea likely helps with alertness.

2. You want to check if changing a button’s color increases clicks in your app.
Your null hypothesis is: “Changing the color will not increase clicks.”
You run an A/B test and get a p-value of 0.06. That means CL = 0.94. Since CL is below 95 percent, your change might not be effective.
But if your p-value was 0.01, then CL = 0.99, which means your idea likely worked.

-----
You can reach out to me via [Linkedin](https://www.linkedin.com/in/rohitgupta61) or [email](mailto:rohit.x.gupta@iiml.org).