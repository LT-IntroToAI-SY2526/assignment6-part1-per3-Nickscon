# Assignment 6 Part 1 - Writeup

**Name:** _______________  
**Date:** _______________

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

The R² score tells how linear the line is on the graph, and the closer it is to 1 the straighter the line is meaning more accurate data. And if the line is closer to 0 means that the line is not as straight meaning there are odd points on the graph.




---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

MSE means how much the margin of error  is from the predicted value compared to the actual value. We square the values because any number squared turns it to positive so there cannot be any negative values in our error value. 




---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

No because the max amount of hours in our training data is 9.6 hours meaning that when we make a prediction outside our range of data it may be incorrect.



---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

The relationship is very weak and non-linear as there are alot of outlier points but the relationship tends to be positive as the association between more hours studied equates to a higher score.




---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. Amount of sleep
2. Mental state of the student
3. Learning disabilities


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

We split it so we can see how our calculator would react to new data after being trained with a previous set and if we trained and tested on the same data we would get a result of overfitting which is when the AI just memorizes the patterns it is given instead of trends.




---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

Learning all the new plot commands and how the embedded functions inside of anaconda work. I overcame it by referencing the ice cream sales functions which gave me a template for the student scores one.




---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

Helping farmers stop overfarming by associating sales with crop yield, and this relationship would be linear because the amount of profit the farmers make equates to how much crops they would need to yield.




---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
