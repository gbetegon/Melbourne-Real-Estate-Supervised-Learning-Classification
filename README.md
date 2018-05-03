
## Melbourne Housing Market – Dealing with missing data when building a predictive model
The __goal__ of this notebook is to __simulate a real-life business scenario__ where a company needs to leverage on a predictive model to successfully implement or enhance a business strategy.

With that in mind, we’re trying to work through the challenges of building a working model that can __add value__ to a company rather than just getting the highest accuracy. This perspective, and real-life constrains (particularly around missing data) will inform many of the decisions in this notebook.

On a personal note, I emphasized explaining the reasons behind every key decision throughout the notebook. Some of the ideas or explanations might be inaccurate, but in any case arbitrary.

The notebook is still live and I will continue to add/enhance content.

__Data Source__: [Kaggle Melbourne Housing Market](https://www.kaggle.com/anthonypino/melbourne-housing-market/data)

## Scenario: Build a classifier to find houses with more than three rooms
We are part of __a company that works in interior design__ of residential spaces. After dissecting the company’s sales, we realize that, though only 20% come from __houses or apartments that have more than three rooms__, these __sales make up to a 70% of the total revenue__. The executive decides to __focus on this high-margin segment__ of the market as part of a new business strategy.

Our main sales channel is a call-center. The cost of customer acquisition is directly related to the number of calls that an agent has to place before finding a potential match. The company wants to maintain acquisition costs while targeting this specific segment. For this reason, they asks us to __build a predictive model using publicly available data that will help target potential customers and reduce useless calls as much as possible__.

The company, present throughout Australia, wants to start launching a pilot on Melbourne. Currently there’s one sales agent assigned part-time to this city with capacity to make an average of 20 calls a day. We want to make those 20 calls as effective as possible and avoid calling customers that don’t fit the criteria.

