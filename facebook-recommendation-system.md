# Facebook's machine learning/AI recommendation engine in 2024

**Can you explain this article in simple terms without too much maths, how does their recommender system differ and does it keep recommendations less bias? 
https://engineering.fb.com/2015/06/02/core-infra/recommending-items-to-more-than-a-billion-people/**

> The article describes how Facebook developed a large-scale recommender system using a method called "rotational hybrid approach."
> Unlike traditional methods that generate massive amounts of network traffic and struggle with skewed data, this approach efficiently
> scales for over a billion users and billions of data points. It reduces biases by addressing issues like popular items overwhelming
> the system, and by combining two optimization methods (SGD and ALS), it makes better recommendations without excessive computing power or data overload.

**But how does the system keep recommendations neutral?**

> Facebook's system aims to keep recommendations neutral by using a hybrid model that combines two algorithms, stochastic gradient descent (SGD) and
> alternating least squares (ALS). This balances the recommendations by preventing popular content from dominating the suggestions and addressing
> biases like overrepresentation of items with more data. Additionally, they ensure that personalized recommendations are more relevant to each
> user by diversifying the input signals, such as user preferences and interaction patterns, which helps avoid recommendation bias towards
> only the most popular or frequently interacted-with items.

**If you were Democrat would they ever show something criticizing the Democrats, or visa versa?**

> Facebook’s recommendation system does not explicitly aim to filter out political viewpoints based on a user’s affiliation.
> However, the recommendations are personalized based on user behavior—likes, shares, interactions, and past content preferences.
> This can create a “filter bubble,” where users see content that aligns with their views, potentially reducing exposure to opposing viewpoints.
> The system doesn't deliberately suppress or promote specific political content, but the personalization might naturally limit how often users
> see criticism of their political affiliations unless they actively engage with diverse sources.
