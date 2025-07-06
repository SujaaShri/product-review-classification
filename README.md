# 🛍️ E-Commerce Review Category Classifier (watsonx.ai)

This project uses IBM watsonx.ai's **FLAN-UL2** foundation model to classify product reviews into one of three categories:  
**Electronics**, **Clothing**, or **Home Appliances**, using few-shot prompt-based learning.

## Files Included

- `ecommerce_reviews_train.csv`
- `ecommerce_reviews_test.csv`

## What It Does

- Loads e-commerce review data from IBM Cloud Object Storage  
- Uses prompt engineering to guide the foundation model  
- Predicts the product category for each review text

## Model Used

- **FLAN-UL2** from IBM watsonx.ai

## How to Use

1. Upload your CSV files (`train` and `test`) to an IBM Cloud Object Storage bucket.
2. Provide your IBM Cloud:
   - **API key**
   - **project ID**
   - **bucket name**
3. Run the notebook in [watsonx.ai](https://dataplatform.cloud.ibm.com/) to classify the reviews using the few-shot prompt and display predictions.

