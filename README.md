# Audiobook_ML
This project involves using Deep Net algorithm on the Audiobooks data to predict whether a customer is likely to buy a subscription. This is capstone project, part of a udemy course on Data Science.

## About the data

The csv file consists of consumer data representing two years worth of engagement. 

The data consists of the following columns:

1) Id: Unique user identifier key
2) Book length overall: sum of the length of the purchases
3) Book length average: book length overall / number of purchases
4) Price overall: sum of price of all the purchases
5) Price average: price overall / number of purchases
6) Review: Shows if customer left a review (1= left a review, 0= didn't leave a review)
7) Review 10/10: Customer review on a scale of 1 to 10 (Represents overall feeling of the customer across all his/ her purchases)
8) Total minutes listened: Total time of engagemenet with the platform
9) Completion: Total minutes listened / book length overall
10) Support Requests: Shows the total number of support requests
11) Last visited minus Purchase date: Difference between last time a person interacted with the platform and their last purchase date

Target variable: Boolean value that represents if a consumer converted or not. This means whether the consumer bought another book in the next six months.

## Task

### To create a machine learning algorithm that can predict if a customer will buy again.

This is a classification problem with two classes- will buy or won't buy.

## Action Plan:

Below-mentioned is the process how the goal is accomplished.

1) Preprocessing the data
  
  1.1) Balancing the dataset
  1.2) Standardizing and shuffling the input dataset
  1.3) Dividing the dataset into training, validation and testing dataset
  1.4) Save the data in .npz format
  
2) Creating the machine learning algorithm (Using Tensorflow)

## Output: 

After testing the data with the tensorflow model, final accuaracy achieved was 81.03%.
