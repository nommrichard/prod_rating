# NLP project- Predicting product rating based on review text 
### Team members:  Karl Jaagup Kask, Ludvig Leis, Richard Nõmm
## Description of the project
The plan is to use user-written reviews to predict the product's rating. We want to capture sentiment and emotions from user input to classify the reviews and try different approaches (CNN, RNN, Naive-Bayes and more models, if time is sufficient) to see which method is the best for predicting product rating based on review text. The overall goal is to become familiar in a more practical way, how NLP works with real-life problems, apply the studied technologies and learn from the positives and negatives of the outcome. It would also be interesting to research similar projects and find interesting approaches from there. The final model can be applied on product feedback on sites, which don’t have the opportunity for users to give ratings on a scale of 1 to 5. Another option is to capture the honest average feedback on sites, which already have these ratings. This is because some users might put the maximum (5) or minimal (1) value by overexaggerating their thoughts. 

## Data (Datafiniti_Amazon_Consumer_Reviews_of_Amazon_Products_May19.csv)
https://www.kaggle.com/datafiniti/consumer-reviews-of-amazon-products 

## Results

BERT MODEL: TRAIN, VAL AND TEST 80-10-10 - 16 batch size, original data,  no stopwords data - Accuracy: 73.81% 
