# Statistical-Inference-A-B-Testing

## Task
Analyze the A/B test and provide recommendations. Follow this structure:

1. **Goal**. Based on the dataset description in [Kaggle](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test), describe the goal of the A/B test. Give any necessary context.
2. **Target metric**. Choose a target metric and describe how it measures progress towards the stated goal of the A/B test.
3. **Calculations**.

## Some notes:

- The dataset is aggregated by **LocationID**, **PromotionID**, and **week**. You should aggregate by **LocationID** and **PromotionID** before conducting the statistical tests.
- Since there are three marketing campaigns and you have to select the best-performing one, you will have to conduct several tests, comparing campaigns against one another. This kind of testing is known as pairwise comparisons, and it suffers from the multiple testing problem - if we run a lot of tests, there’s an increased chance of getting a type I error (false positive). It is, therefore, suggested to use the confidence level of 99% instead of the traditional 95% in your graded task.

### The full analysis is available in the attached PDF document.
