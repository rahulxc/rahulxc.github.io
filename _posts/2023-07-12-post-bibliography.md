---
layout: post
title: Customer Funnel Journey Analytics For DS Interviews
description: "Exploring the nuances of diagnosing changes in key metrics through customer funnel journey analysis."
tags: [Data Science Interview]
date: 2023-08-08
author: Rahul Chaudhary
---


**One of the most common data science-product interview questions involves understanding a sudden change or drop in output, examined through the lens of intermediary steps. Here are some examples:**

- **Tech**: How’d you diagnose a sudden drop in Traffic on Facebook Threads App?
- **E-commerce**: There's a drop in sales for eBooks on the Kindle App. How would you diagnose this issue?
- **Marketing**: There's a drop in the open rate for marketing emails. How would you diagnose this problem?

---

The aforementioned questions can be approached through the lens of a **Customer Funnel Journey Framework**, where we encapsulate each facet of the customer journey — from the first interaction to the final purchase. Let's explore this framework using an e-commerce website as an example.

### The Customer Funnel Journey Framework

The journey might start with site visitors and end with a product purchase. The diagram below outlines the various intermediate steps — with various inputs which will influence the flow to the next step. It is crucial to understand each step and its inputs carefully.


<img src="/assets/img/customer_funnel.png" alt="Customer Funnel Journey" title="Customer Funnel Journey" style="width: 50%;"/>


Each stage of the funnel has inputs or variables that can impact the output. By manipulating these inputs, it is possible to increase the proportion of users progressing to the next stage.

**Controllable vs. Uncontrollable Inputs**: It's important to distinguish between controllable inputs like marketing and SEO, and uncontrollable ones like seasonality.

**Seasonality**: For an e-commerce website, recognizing increased traffic during holiday seasons is crucial in product sense analysis.

**Ethical Considerations**: It is unethical, for instance, to manipulate product reviews to improve outcomes.

**Other Limitations**: Some inputs like price and relevancy may be challenging to change, while others offer more flexibility.

**Product Prioritization**: In identifying features to implement at different funnel stages, prioritize based on the potential impact on top-line goals like growth or profitability.

<img src="/assets/img/customer_funnel2.png" alt="Prioritize For Impact" title="Prioritize For Impact" style="width: 50%;"/>


---

### Root-cause Analysis Using the Customer Funnel

The framework can be leveraged for troubleshooting. For instance, if revenue has decreased, identify at which funnel step the dip occurred. Segment this step by platform, marketplace, or screen size to narrow down and pinpoint the root cause.

### Technical Deep-Dive: Example Scenarios

1. **E-commerce Drop in eBook Sales on Kindle App**: 
   - **First Step**: Analyze the visitor-to-viewer transition. Check if there's been a decrease in website traffic or app usage. 
   - **Next Steps**: Examine the viewer-to-purchaser transition. Are users viewing product pages but not proceeding to purchase? Investigate issues like load times, user interface, or payment gateway problems.
   - **Further Analysis**: Dive into customer reviews, pricing strategies, and eBook promotions for potential insights.

2. **Decrease in Marketing Email Open Rates**:
   - **Initial Analysis**: Review changes in email content, subject lines, and send times.
   - **Segmentation**: Break down the open rates by demographics, past user behavior, and email types.
   - **Technical Aspects**: Examine if emails are being marked as spam or if there are deliverability issues.

---

**In conclusion**, the Customer Funnel Journey Framework provides a structured approach to diagnosing and addressing drops in key metrics. By segmenting the analysis at each funnel stage and considering both controllable and uncontrollable factors, one can effectively identify and tackle the underlying issues.

*Source: "How to Think Product Analytics in PM Interviews" by Amazon Sr PM, Vivek Pandey.*
