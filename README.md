# MyAIImageReader

## This is an academic project that was created for [CS5644: Machine Learning with Big Data](https://cs.vt.edu/Graduate/Courses/GradCourseDescriptions.html) at Virginia Tech.

The source code for this project can not be made public owning to [VT academic Honor Code](https://honorsystem.vt.edu/). However, please feel free to reach out if you have any questions. :wink:

### Backgroud

This project focuses on solving the challenge of digitizing and classifying textual data within office action documents from the [USPTO](https://www.uspto.gov/). The goal is to address the limited accessibility and searchability of historical office action data, crucial for legal professionals and intellectual property stakeholders. Existing methods like OCR and manual data entry are deemed inefficient, prompting the exploration of AI models for accurate classification of characters and fonts. The proof-of-concept initiative aims to achieve a minimum accuracy of **85%** in categorizing one-hundred and fifty-three possible classifications. 

### Approach

Our problem required a **supervised machine learning** solution. We tested the Categorical Variable Decision Tree, Naïve Bayes, Random Forest, and Logistic Regression models to identify which models perform better. In each model implemented, the data was adjusted as per the model’s required input. Each model was reviewed and the performance scores were calculated and compared to identify the best model for creating a better OCR engine.

### Highlights

AI, Classification, Optical Character Recognition (OCR), Google Cloud Platform (GCP), Python 3, Categorical Variable Decision Tree, Naïve Bayes, Random Forest, Logistic Regression, Sklearn, TensorFlow, PyTorch, Cross Entropy Loss, Convolutional Neural Network (CNN), principal component analysis (PCA), variance threshold/feature selection, Central Processing Unit (CPU), Random Access Memory (RAM), Graphical Processing Unit (GPU), Accuracy, Precision, Recall, and F1 score.

### Data

The data consists of 750,000 instances, 410 features, and target variables. We reviewed and tested the integrity of the data. These tests include 
- checking for missing data, consistent data types, outliers
- verifying that the target variable is nominal and not real-valued

This data was loaded in a list(s) data types for the manipulation for each model. For non-real-valued data, i,e. feature ‘font’ and ‘fontVariant’, we have used the **one-hot encoding** to process categorical features.

Lyman,Richard. (2016). Character Font Images. UCI Machine Learning Repository. https://doi.org/10.24432/C5X61Q

### Acknowledgments
- [Dillard Murphy](https://www.linkedin.com/in/dillard-murphy/) aided in verifying dataset integrity, implementing classification models, models tuning, debugging the code, creating visuals, document formatting, and a final review of the project.

- [Georgio McGarrah](https://www.linkedin.com/in/georgio-mcgarrah/) aided in cleaning the data, data preprocessing, normalizing data, debugging code, refactoring code, and reviewed the final project.

- [Mengyi Guo](https://www.linkedin.com/in/mengyi-guo/) created a test plan and set target goals for each AI classification model, implemented ML models, coded visuals, debugged code, documented the experiments, and reviewed the final project.

---

  ![Mengyi Cartoon Pic](/Live,%20Love,%20Learn.png)

Know more about **me** by

- 🙋🏻‍♀️ going to my [Website](https://mengyig.github.io/#)
- 😁 visiting my [LinkedIn](https://www.linkedin.com/in/mengyi-guo/)
- 🎥 checking my [Youtube](https://www.youtube.com/channel/UCu7Q8pfeEvjgTxVyj7YVxHw)
