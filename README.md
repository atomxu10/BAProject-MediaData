# Subscription Service 'Recipe Box' Task
**Task Introduction:**

Your client has a subscription service that supplies recipes and associated ingredients, direct to consumers via their website. Please take at ***maximum 3 hours*** to interrogate the dataset and paint a picture of their business. It has ***3 questions below*** to provide guidance on how to tackle the task. Please have any workings in ***Excel*** ready to show (***PowerPoint*** may be used).

The dataset(Excel) can be found in the [Subscription_Task(3hours).xlsx](https://github.com/atomxu10/MediaDataAnalysis/blob/main/Subscription_Task(3hours).xlsx)

**Questions:**

1. Chart the clients' New and Existing Customer data.
  Please make it clear what the changes over time are, what are the patterns in the data, is the client in growth or decline?
  Are there key factors that may influence new & existing customer growth? Explore further charting to explain what the relationship between the   factor and client data is.

2. We have included both spend and TV ratings for 3 major campaigns. Describe the relationship between the TV Campaign and the customer data.
Can you make an educated guess about which campaign (A, B, C) was the most effective at driving customer growth?
Explain what other benefits the client could get from their TV advertising.

3. The client wants you to answer the question "How is media contributing to my business growth?
Using the existing data, how would you help the client answer this?
What other data sources would you request and why?

I completed the data processing task (data cleaning, analysis, visualization, and modeling) in Excel within two hours. Additionally, I spent one-hour creating presentation slides using PowerPoint.

**Content (Powerpoint):**
<div align="center">
    <img src="plot/sss1.png" width="800px" alt="s1">
</div>

Let's first examine the time series data for new and existing customers. The blue line represents the total revenue for each week over three years. To clarify the trend, I applied the Moving Average method, which is illustrated by the red line. Despite some fluctuations, we can observe a consistent upward trend over time. Significant fluctuations are marked with green circles for low points and red circles for high points. Comparing the different charts, it is evident that these fluctuations occurred at similar times for both new and existing customers. This pattern suggests that the fluctuations might have been influenced by certain campaigns, which will be discussed in more detail later.

<div align="center">
    <img src="plot/ss2.png" width="900px" alt="s1">
</div>

To determine whether the client was in growth or decline, I divided the nearly three years of data into three segments, each covering 55 weeks. The bar charts on the right illustrate the total revenue from different customer segments, both showing significant increases. Based on this analysis, we can conclude that the client is in a period of growth.

<div align="center">
    <img src="plot/ss3.png" width="900px" alt="s1">
</div>
