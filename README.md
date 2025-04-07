# An intelligent system for predicting health risks and recommending preventive interventions

## Motivation
With chronic diseases on the rise, our healthcare systems are struggling to keep up, often reacting to health crises rather than preventing them. Current diagnostic methods are too slow, leading to delayed interventions and worsening patient outcomes. 
What if we could predict health risks such as heart disease,  chronic kidney disease, breast cancer, and other diseases before they occur, simply by analyzing patient data? This project aims to use Machine Learning to identify potential health risks early, allowing healthcare providers to act before it’s too late. By enabling customized prevention strategies, personalized care, and more efficient resource allocation, this predictive system has the potential to transform our approach to healthcare—shifting from reaction to prevention and ultimately enhancing lives. 

## Research Background
<b>Comparative Analysis of Logistic Regression, Gradient Boosted Trees, SVM, and Random Forest Algorithms for Prediction of Acute Kidney Injury Requiring Dialysis After Cardiac Surgery</b>
In this research, the authors explore the use of Support Vector Machines (SVM), Random Forest, and Logistic Regression for classifying medical data, particularly in disease diagnosis. They conclude that while Logistic Regression is straightforward and easy to interpret, SVM and Random Forest demonstrate better performance due to their capacity to manage complex, high-dimensional data. The study highlights the benefits and challenges associated with each model and suggests that ensemble methods, such as Random Forest, may offer the best balance between accuracy and interpretability in medical applications.


## Data Science Pipeline
<img width="955" alt="Screenshot 2025-04-07 at 5 36 55 AM" src="https://media.github.sfu.ca/user/2178/files/c52e8231-3a57-43ee-90c2-c27cad0a538f"/>

## Data Product
### Here is a snapshot of the Power BI dashboard: <img width="1710" src="https://media.github.sfu.ca/user/2178/files/c6fbcc2d-b9f9-41dc-ad69-465177d91f37">

## Report
The project report is availaibe at Capstone/Report/. 

## Project Structure
<img width="418" alt="Screenshot 2025-04-07 at 1 28 10 PM" src="https://media.github.sfu.ca/user/2178/files/202da918-e5ba-4f87-8f40-af45eae887f3">

## Environment Setup
## 🔐 Testing With GitHub Actions (Secure)

This project is designed to access Azure Blob Storage **securely** via GitHub Actions.

If you'd like to test the notebook using built-in credentials (no setup required):

1. **Fork this repo**
2. Go to the **Actions** tab
3. Select the workflow: `Access Azure Blob from Colab`
4. Click **"Run workflow"** (you’ll see this if `workflow_dispatch` is enabled)

The GitHub workflow will:
- Install dependencies
- Inject secure Azure secrets
- Execute the notebook
- Upload the results as an artifact (you can download it)

✅ No local setup needed. You don’t need Azure credentials on your machine.
