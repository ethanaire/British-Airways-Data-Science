# British Airways Data Science

## Project Briefing:

**Lounge access** is a key part of the premium travel experience, and understanding lounge demand is crucial for British Airways (BA) to maintain high standards while optimizing space and resources. As the airline plans for future operations at Heathrow Terminal 3, it’s important to anticipate demand across different types of lounge access, each associated with varying levels of customer loyalty and travel class.

As BA plans for the future, especially with changes in flying schedules and fleet strategy, it's important to _forecast how many passengers will be eligible to use each lounge on a typical day_. However, future schedules can be unpredictable, which means we need a modeling approach that is both flexible and scalable.

Your job is to create **a lookup table** that BA can use to estimate lounge eligibility percentages across different flight groupings. This will allow the business to anticipate lounge demand without needing exact flight or aircraft details.

## Project Tasks:

### Task 1: Modeling lounge eligibility at Heathrow Terminal 3

To begin modeling lounge demand, it’s important to understand who is typically eligible for lounge access. Lounge eligibility is generally based on customer loyalty status and travel class, with different access tiers offering varying levels of amenities.

<p align="center">
  <img title="BA Lounge Tiers" alt="Alt text" src="/Assets/BA-Lounge eligibility.png" width="600" height="275">

The goal is to create **a lookup table** that estimates lounge eligibility using clear, scalable categories. To do this, you’ll need to decide how to group flights and make logical assumptions.

Common groups include: 
- **Time of day**: Early morning, mid-day, evening departures.
- **Type of route**: Short-haul vs. long-haul
- **Region or destination group**: Europe, North America, Asia, etc.

### Task 2: Predicting customer buying behaviour

The most important factor with a predictive model is the quality of the data you use to train the machine learning algorithms. For this task, you must manipulate and prepare the provided customer booking data so that you can build a high-quality predictive model.

With your predictive model, it is important to interpret the results in order to understand how “predictive” the data really was and whether we can feasibly use it to predict the target outcome (customers buying holidays).

Specifically, here is how we processed this task: 
1. Explore and prepare the dataset.
2. Train a machine learning model.
3. Evaluate model and present findings. 
