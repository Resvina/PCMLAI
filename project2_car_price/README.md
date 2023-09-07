**OVERVIEW**

In this application, you will explore a dataset from kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing.  Your goal is to understand what factors make a car more or less expensive.  As a result of your analysis, you should provide clear recommendations to your client -- a used car dealership -- as to what consumers value in a used car.

### Business Understanding

From a business perspective, we are tasked with identifying key drivers for used car prices.  In the CRISP-DM overview, we are asked to convert this business framing to a data problem definition.  Using a few sentences, reframe the task as a data task with the appropriate technical vocabulary. 

Pre-owned vehicles constitute a substantial industry, influenced by various elements determining the relative worth of one used car compared to another. To optimize earnings, a pre-owned car dealership must maintain a stock of vehicles equipped with sought-after attributes and priced competitively.Therefore analyze the data and provide clear reccommendation to clients

### Data Understanding

After considering the business understanding, we want to get familiar with our data.  Write down some steps that you would take to get to know the dataset and identify any quality issues within.  Take time to get to know the dataset and explore what information it contains and how this could be used to inform your business understanding.

### Evaluation

With some modeling accomplished, we aim to reflect on what we identify as a high quality model and what we are able to learn from this.  We should review our business objective and explore how well we can provide meaningful insight on drivers of used car prices.  Your goal now is to distill your findings and determine whether the earlier phases need revisitation and adjustment or if you have information of value to bring back to your client.

Post-modeling analysis is essential to discern the efficacy of our model and extract valuable insights.
We must align our objectives with the goal of unraveling the factors influencing used car prices.
Our task now involves condensing our findings and evaluating whether prior phases necessitate reevaluation and adjustment or if we've gleaned information of significance to present to the client.
The modeling phase presented unforeseen challenges. Due to certain columns lending themselves to one-hot encoding, our dataframe expanded beyond the processing capacity of a standard home laptop, limited to 20 columns with less-than-ideal labels.
Modeling outcomes exhibited inconsistencies, characterized by substantial errors. 
Notably, factors such as lower odometer readings, newer vehicle models, and increased cylinder count exhibited a positive correlation with price. 
Some additional features played a role, notably the preference for automatic transmissions.
However, our confidence in providing further valuable insights from the current dataset is limited. 
We recommend collecting additional data that may exhibit stronger correlations with price, such as horsepower or fuel efficiency. 
Another ambiguity lies in distinguishing vehicles that generate the most profit from those with the highest selling prices, a crucial distinction for used car dealers.

### Deployment

Now that we've settled on our models and findings, it is time to deliver the information to the client.  You should organize your work as a basic report that details your primary findings.  Keep in mind that your audience is a group of used car dealers interested in fine tuning their inventory.

In my effort to optimize profits from used car sales through data collection and analysis, 
I have gained some insights. However, I acknowledge the need for more comprehensive data, particularly
regarding past car sales profitability, which could be obtained by tracking dealers' 
purchase prices. From the available data, certain trends are evident: buyers are willing to pay higher
prices for newer cars with lower odometer readings, automatic transmissions, and electric or hybrid vehicles. 
While other factors play a role in pricing and customer interest, their influence remains uncertain. 
Therefore, I recommend ongoing data collection to identify additional features that drive customer interest and,
consequently, higher profits, enhancing my predictive models.

