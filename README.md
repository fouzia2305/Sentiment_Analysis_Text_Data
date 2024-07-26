# Sentiment Analysis of Amazon Fine Food Reviews

## Objective
To analyze customer sentiment in Amazon fine food reviews by transforming raw text data into a structured format and building predictive models.

## Data Description
The dataset includes:
- **Id:** Unique row number
- **ProductId:** Unique identifier for the product
- **UserId:** Unique identifier for the user
- **ProfileName**
- **HelpfulnessNumerator:** Number of users who found the review helpful
- **HelpfulnessDenominator:** Number of users who indicated whether they found the review helpful
- **Score:** Rating between 1 and 5
- **Time:** Timestamp for the review
- **ReviewSummary:** Brief summary of the review
- **ReviewText:** Text of the review

## Sprints

### Sprint 1 - Create DataFrame from Raw Text Files
1. **Task:** Transform the given text files into a tabular format (CSV).
2. **Process:**
    - Read and parse text files into a DataFrame.
    - Save the combined DataFrame as a CSV file.

### Sprint 2 - Build a Model
1. **Task A:** Data Preprocessing
    - Remove duplicates and handle missing values.
    - Create a sentiment column based on review scores.
    - Visualize data with a word cloud.
    - Sample data for training.
    - Split data into train and test sets.
    - Perform text preprocessing (tokenization, stop-word removal, lemmatization).

2. **Task B:** Build and Evaluate Models
    - Define vectorizers (TF-IDF) and classifiers (Decision Trees, Logistic Regression, Random Forests, K-Nearest Neighbors, Support Vector Machines).
    - Train and evaluate each model.
    - Models were evaluated based on F1 scores to ensure balanced precision and recall.

## Results
- **Logistic Regression:** Accuracy ~88%, F1 Score ~0.93
- **Support Vector Machines:** Accuracy ~89%, F1 Score ~0.94
- The models provided valuable insights for enhancing customer satisfaction and product recommendations.

## Challenges
Efficiently processing and transforming the vast raw text data into a structured format while managing memory and computational resources.

## Conclusion
The project successfully demonstrated the application of data engineering and machine learning techniques to derive meaningful insights from unstructured text data. The high-performing models provided valuable insights for enhancing customer satisfaction and improving product recommendations.
