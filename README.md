# Platform Choice

## Overview
I have been hired to help the company decide whether to focus their efforts on their **Mobile App** experience or their **Website**.

## System Requirements
To run this project, ensure you have the following libraries installed
```bash
pip install pandas numpy seaborn matplotlib 
```
for any other library find them on the internet

## Dataset

### Data
**Source**: Artificially generated by PIERAN DATA

### Features
- **Email**
- **Address**
- **Avatar**
- **Avg. session length**
- **Time on App**
- **Time on Website**
- **Length of Membership**
- **Yearly Amount Spent**

### EDA
The main findings from the EDA include:
- Visualizations: Used jointplot, pairplot, lmplot to understand the relationship between the **features** and the **Yearly Amount Spent**
- Insights:
    - The **Time on App** is correlated with the **Yearly Amount Spent**.
    - The **Length of Membership** is correlated with the **Yearly Amount Spent**.
    - The most Correlated feature with **Yearly Amount Spent** is **Length of Membership**.

### Modelling
Used only one machine learning model at the moment
- **Model**: 
    -Linear Regression: used as a baseline model
- **Evaluation Metrics**: Mean Absolute Error, Mean Squared Error, Root Mean Squared Error, Explained Variance score(R^2).

## Results
- **Final Results**: The Linear Regression model achieved a Explained_Variance_Score of **98%**.
- **Conclusion**: 
    - The comapny can focus their efforts on their mobile App experience since it is   already performing or the company improve theier website experience to the level of the mobile App.
    - The Length of Membership generates a Greater increase in the Yearly Amount Spent.

## Contributing
```markdown
1. Fork the repository
2. Create a new branch(`feature-branch`)
3. Add extra Data stages
4. Submit a pull request
```

## Acknowledgemtns
- **Inspiration**: This project was inspired by PIERAN DATA [Python for data science and machine learning](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/?couponCode=ST6MT103124)