# cardio_disease
This project applies Machine Learning techniques to predict whether a person is susceptible to developing cardiovascular disease.

We use a dataset with 10,000 records, containing medical and lifestyle information that may influence cardiovascular health.

#OBJECTIVE
The main goal is to analyze patient data and train a predictive model capable of identifying patterns that indicate potential cardiovascular risks.

#DATASET
The dataset contains 10 features plus the target variable (cardio_disease):
| Feature             | Description                                                             |
| ------------------- | ----------------------------------------------------------------------- |
| **age**             | Age of the person (in years)                                            |
| **gender**          | 1 = Female, 2 = Male                                                    |
| **height**          | Height (cm)                                                             |
| **weight**          | Weight (kg)                                                             |
| **cholesterol**     | Cholesterol level (1 = normal, 2 = above normal, 3 = well above normal) |
| **gluc**            | Glucose level (1 = normal, 2 = above normal, 3 = well above normal)     |
| **smoke**           | Smoking status (1 = smokes, 0 = does not smoke)                         |
| **alco**            | Alcohol intake (1 = consumes, 0 = does not consume)                     |
| **active**          | Physical activity (1 = active, 0 = not active)                          |
| **cardio\_disease** | Target variable: 1 = at risk / has disease, 0 = healthy                 |
