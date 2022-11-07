# So You Want Some MONEY!

![kisspng-loan-credit-risk-finance-clip-art-crazy-person-pictures-5aa95e9233ce04 3591579915210492342122](https://user-images.githubusercontent.com/67832009/199850803-0cfa2aef-d583-4e4b-a270-1618ae0689ba.png)


## Pre-Analysis Predictions

1. High debt-to-income is a telling indicator of credit risk.
1. High interest rates are another sign of credit risk.
1. A lot of loans increases credit risk.

## And the model says . . .

1. Looking at the RandomForestClassifier, the interest rate is the most predictive feature. 
1. Borrower income and debt-to-income are a distant second & third respectively.
1. The LogisticRegression model yielded more sketchy results. It seems to suggest that loan size is the biggest predictor. I am skeptical of that since loan size is really relevant when it reflects the ability to pay.

## How the models performed

1. Both models performed well in respect to the testing and training data.
1. Given that both models performed well, I would have expected similar results, but this may be more indicative of applying the right model to the data!
