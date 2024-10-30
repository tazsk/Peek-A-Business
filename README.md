# Smart Business Insights System

**Team:**  
**Team #9**

**Team Members:**  
- Amey Makarand Dhongade - [ameymakarand.dhongade@sjsu.edu](mailto:ameymakarand.dhongade@sjsu.edu)  
- Titas Sarkar - [titas.sarkar@sjsu.edu](mailto:titas.sarkar@sjsu.edu)

---

## Project Description:
This project is a location-based decision support system designed using machine learning algorithms and techniques to provide entrepreneurs with insights on starting a business based on existing competition.

The system addresses the need of entrepreneurs who want to establish a business in a city or town but are unaware of the competition in that particular business category. The system aims to solve this problem by identifying major business categories indicating direct competition.

The tool will assist entrepreneurs in searching for ideal locations that offer a strategic advantage to their business.

---

## Motivation:
Traditional methods of finding an ideal location for business setups are time-consuming. By using machine learning techniques to analyze key factors such as demographics and local competition, entrepreneurs can gain a strategic advantage over others.

Moreover, AI streamlines the process of location selection, saving time and cost while reducing uncertainty when deciding on the preferred location.

---

## Goal:
To develop a tool that helps entrepreneurs find optimal business locations, increasing the likelihood of success.

---

## Objective:
Design and implement an AI-driven solution that predicts market competition by analyzing key factors such as demographics and market trends, with the objective of improving business success rates.

---

## Development and Implementation:

### Data Cleaning:
The API call request returns a JSON file that is normalized and converted into a dataframe. We plan to create a new dataframe by retrieving only relevant data, such as name, categories, and location, using Pandas.

### Clustering:
We aim to find major business categories in the dataset to group similar businesses, enhancing data analysis. We will compare results from the K-Means [1] and DBSCAN (Density-Based Spatial Clustering of Applications with Noise) [2] clustering algorithms.

### Predicting:
The goal is to predict the business category based on the input data using a classification algorithm. We plan to compare results between the Support Vector Machine [3] and k-NN [4] classification algorithms.

---

## Dataset:
We will integrate FourSquare API [5] calls with our models to retrieve data.

---

## Deliverables:
- A map with multi-colored cluster points representing major business categories in a city or town.
- Summarized business categories in percentages, giving the user insight into business clusters and classifications.

---

## Technology Stack:
- **Python** [6]
- **Google Colab** [7]
- **Scikit-learn Library** [8]

---

## Project Labor Division:

| **Project Phase**          | **Duration** | **Team Member** | **Role**                                      | **Tasks**                                                                                     |
|----------------------------|--------------|-----------------|-----------------------------------------------|-----------------------------------------------------------------------------------------------|
| Planning and Research       | Weeks 1-2    | All             | Coordinate and Plan                           | Create initial tasks regarding codebase setup and research algorithms                          |
| Design and Prototyping      | Weeks 3-5    | All             | ML Model Design                               | Design initial ML algorithms                                                                   |
|                            |              | Amey            | Clustering & Classification Algorithm Design  | Research how to classify input based on clusters and create the classification algorithm       |
|                            |              | Titas           | Clustering & Classification Algorithm Design  | Research how to classify input based on clusters and create the classification algorithm       |
| Development and Implementation | Weeks 5-7 | All             | ML Model Implementation                       | Work on implementing algorithms using Scikit-learn                                              |
| Testing and Optimization    | Weeks 7-9    | All             | Testing                                       | Test accuracy, and compare approaches used                                                     |
| Presentation Preparation    | Week 10      | All             | Documentation & Deliverables                  | Compile results and prepare final deliverables                                                  |
| Presentation                | Week 10      | All             | Presentation                                  | Present findings and results from the project approach                                         |

---

## References:
1. K-Means Algorithm: [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/clustering.html#k-means)
2. DBSCAN Algorithm: [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/clustering.html#dbscan)
3. Support Vector Machine Algorithm: [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/svm.html)
4. k-NN Algorithm: [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/neighbors.html#classification)
5. Foursquare API: [Foursquare Developer Documentation](https://developer.foursquare.com/docs/)
6. Python Programming Language: [Official Python Website](https://www.python.org/)
7. Google Colab: [Google Colab Platform](https://colab.research.google.com/)
8. Scikit-learn Library: [Scikit-learn Official Website](https://scikit-learn.org/)
