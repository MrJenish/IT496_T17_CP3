# IT496_T17_CP3

# Cricket World Cup 2023 Predictions

This project predicts the winners of Cricket World Cup 2023 matches using an Artificial Neural Network (ANN) model. The predictions are based on historical One Day International (ODI) cricket match data.

## Dataset

- **Dataset Link:** [here is the dataset link](https://www.kaggle.com/datasets/jaykay12/odi-cricket-matches-19712017)

- **Columns:**
  1. Scorecard
  2. Team 1
  3. Team 2
  4. Winner
  5. Margin
  6. Ground
  7. Match Date

## Analysis of the Dataset

- The dataset includes information about ODI cricket matches, including participating teams, match outcomes, venues, and match dates.


- ## Exploratory Data Analysis (EDA)

In the Exploratory Data Analysis phase, we delved into the ODI cricket match dataset to uncover key insights and patterns. Three essential visualizations were created to better understand the historical data:

1. **Number of Times Each Team Wins:**
   We analyzed the dataset to determine the frequency of victories for each cricket team. The bar chart displays the count of matches won by each team, providing a comprehensive overview of the teams' historical performance in ODI matches.

2. **Number of Matches Held Each Year:**
   Another crucial aspect examined was the distribution of matches over the years. The line chart illustrates the number of ODI matches held each year, offering insights into the trends and variations in match frequency over time.

3. **Percentage of Wins for Each Team:**
   To gauge the success rate of each team, we computed the percentage of matches won by each team relative to the total number of matches they played. The pie chart visualizes the distribution of victories, highlighting the proportional contribution of each team to the overall match outcomes.

These visualizations collectively provide a comprehensive overview of the dataset, offering insights into team performances, yearly trends, and the relative success rates of each participating team in ODI cricket matches.


## Preprocessing

- **Label Encoding:**
  Categorical variables such as 'Team 1', 'Team 2', and 'Ground' were label-encoded to transform them into numerical values. This step is essential for the ANN model, as it requires numerical inputs. The label encoding process involved assigning a unique numerical identifier to each distinct team and ground present in the dataset.

These preprocessing steps contribute to the overall cleanliness and suitability of the dataset for training the ANN model, ensuring that it can effectively learn from the historical ODI cricket match data.

## ANN Model for Predictions

- Built an ANN model to predict match winners based on 'Team 1', 'Team 2', and 'Ground'.

## Model Accuracy

- Achieved an accuracy of **41.81%** on the test set.

## Hyperparameter Tuning

Fine-tuning the hyperparameters of the ANN model played a crucial role in enhancing its performance. Several parameters were adjusted and optimized to achieve the best possible results. The hyperparameters subjected to tuning included:

- **Number of Neurons in Each Layer:**
  The architecture of the neural network was optimized by varying the number of neurons in each layer. This process involved experimenting with different configurations to identify the combination that yielded the highest predictive accuracy.

- **Number of Layers:**
  The depth of the neural network was explored by adjusting the number of layers. This helped in finding the optimal balance between model complexity and generalization.

- **Dropout Rate:**
  Dropout layers were introduced to prevent overfitting. The dropout rate, which determines the fraction of neurons to randomly drop out during training, was fine-tuned to achieve better model performance on unseen data.

- **Optimizer Selection:**
  Different optimizers were evaluated to determine the one that facilitated faster convergence and improved the overall efficiency of the training process.

The hyperparameter tuning process involved a systematic exploration of various configurations, and the best combination was selected based on its impact on the model's accuracy and generalization capability.


## Best Model Accuracy

- The best-performing model achieved an accuracy of **43.63%**.

## Tournament Predictions

- **Semifinal 1 Winner:** India
- **Semifinal 2 Winner:** South Africa
- **Final Winner:** India

## Contributors

- [Arnish Satasiya](https://github.com/arnishsatasiya) - 202001031 : Data Preprocessing, API development in fastAPI & deployment in render
- [Jay Kuvadiya](https://github.com/JaYkuvadiya17) - 202001042 : Data Preprocessing, Winner prediction
- [Jenish Mangukiya](https://github.com/MrJenish) - 202001176 : Model Tranning, Hyperparameter Tunning and Winner prediction 
- [Aastha Shetty](https://github.com/aasthashetty) - 202001260 : EDA Part, Data Preprocessing
- [Deep Kanani](https://github.com/202001454) - 202001454 : EDA Part, API development in fastAPI & deployment in render
