
# 🎬 PySpark Movie Recommendation System

This project implements a movie recommendation system using PySpark, leveraging collaborative filtering with ALS (Alternating Least Squares) algorithm. The system processes a dataset of movie ratings, trains a recommendation model, and provides personalized movie recommendations to users.

## 🚀 Features

- **Data Loading:** Loads movie ratings dataset into a Spark DataFrame.
- **Data Preprocessing:** Preprocesses the dataset by indexing movie titles and splitting into training and test sets.
- **Model Training:** Trains a recommendation model using the ALS algorithm.
- **Prediction:** Makes predictions on the test dataset to evaluate model performance.
- **Evaluation:** Evaluates model performance using Root Mean Square Error (RMSE).
- **Recommendation:** Provides top movie recommendations to users based on their preferences.

## 💻 Installation

To run the PySpark Movie Recommendation System locally, follow these steps:

1. Clone the repository to your local machine:
```git clone https://github.com/your_username/your_repo_name.git```


2. Install the required dependencies:
`pip install pyspark`



## 🛠️ Getting Started

To get started with the PySpark Movie Recommendation System, follow these steps:

1. Load the movie ratings dataset.
2. Preprocess the dataset by indexing movie titles.
3. Split the dataset into training and test sets.
4. Train the recommendation model using the ALS algorithm.
5. Evaluate the model performance using RMSE.
6. Provide personalized movie recommendations to users.

## 🚀 Usage

To use the PySpark Movie Recommendation System, follow these steps:

1. Prepare your movie ratings dataset in CSV format.
2. Replace the path to your dataset in the `main.py` file:

```python
df = spark.read.csv('path/to/your/dataset.csv', inferSchema=True, header=True)
```

3. Ensure that your dataset contains columns for userId, title, and rating.

4. Run the main script to execute the recommendation system:


`python main.py`

5. The system will process the dataset, train the recommendation model, evaluate its performance, and provide personalized movie recommendations.

6. Access the recommendations through the console output or any other preferred method of displaying the results.



## 📚 Lessons Learned

Throughout the development of the PySpark Movie Recommendation System, several key lessons were learned and challenges were encountered:

### Data Processing with PySpark

- **Data Loading and Preprocessing**: Handling large-scale datasets efficiently using PySpark required understanding data loading techniques and preprocessing steps such as indexing and splitting into training and test sets.

### Collaborative Filtering with ALS Algorithm

- **Model Training and Evaluation**: Training a recommendation model using the ALS algorithm involved tuning hyperparameters and evaluating model performance using metrics like Root Mean Square Error (RMSE).

### Integration with External Libraries

- **Integration with StringIndexer**: Incorporating external libraries like StringIndexer for indexing movie titles required understanding how to apply transformations to the DataFrame and handle the transformation model.

### User Interaction and Feedback

- **Providing Personalized Recommendations**: Designing a user-friendly interface to provide personalized movie recommendations involved considering user preferences, handling user queries effectively, and presenting recommendations in an understandable format.

### Testing and Debugging

- **Testing Recommendation System**: Thorough testing of the recommendation system with different datasets and user scenarios was crucial for identifying and debugging issues related to model predictions and user recommendations.

### Documentation and Collaboration

- **Documentation and Best Practices**: Documenting the project's architecture, implementation details, and usage instructions facilitated collaboration among team members and ensured the reproducibility of results. Adhering to best practices in software engineering promoted code maintainability and scalability of the recommendation system.

## 🤝 Contributing

We welcome contributions from the community to enhance ExploraAi. If you're interested in contributing, please follow these guidelines:

- Fork the repository and create a new branch for your feature or bug fix.
- Ensure your code follows the project's coding standards.
- Submit a pull request detailing your changes and their purpose.

## 🧑‍💼 About Me
### Kushan Manahara

I'm a final year undergraduate student pursuing Computer Engineering at the University of Peradeniya. My passion lies in research, AI development, and automation. I thrive on exploring new technologies and pushing the boundaries of what's possible in the realm of artificial intelligence.

Whether it's diving into the intricacies of machine learning algorithms or crafting seamless user experiences through full stack development, I'm driven by a relentless curiosity and a desire to make meaningful contributions to the field of technology.

Feel free to reach out if you'd like to collaborate on exciting projects or discuss ideas at the intersection of technology and innovation.

Connect with me on [LinkedIn]([Your_LinkedIn_Profile_URL](https://www.linkedin.com/in/kushan-manahara/))

## 💡 Skills

During the development of the PySpark Movie Recommendation System, various skills were honed and applied to ensure the success of the project:

- **PySpark Development**: Proficiency in PySpark was essential for data processing, model training, and recommendation generation, enabling efficient handling of large-scale datasets.
  
- **Machine Learning**: Solid understanding of machine learning concepts, particularly collaborative filtering algorithms like ALS, was crucial for training accurate recommendation models and evaluating their performance.

- **Data Preprocessing**: Skills in data preprocessing techniques, such as indexing and splitting datasets, were utilized to prepare the movie ratings data for training the recommendation model.

- **Python Programming**: Proficiency in Python programming language was vital for implementing the recommendation system, integrating external libraries, and handling user interactions.

- **Algorithm Tuning and Evaluation**: Knowledge of hyperparameter tuning and model evaluation techniques helped optimize the recommendation model's performance and assess its effectiveness using metrics like RMSE.

- **User Interaction Design**: Designing an intuitive user interface for presenting movie recommendations required understanding user preferences and effectively communicating recommendations in a user-friendly format.

- **Documentation and Best Practices**: Adherence to best practices in software engineering and documentation ensured clarity, maintainability, and reproducibility of the recommendation system's codebase and implementation.

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://kushan-portfollio.vercel.app/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kushan-manahara/)

## ✍️ Authors
- [@KushanManahara](https://github.com/KushanManahara/)
## 🎖️ Badges
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)