# AI-Learning

## Nim Solver (Reinforcement Learning)

### Overview
This project focuses on implementing an AI that learns the optimal strategy for the game of Nim using reinforcement learning, specifically Q-learning. In Nim, players take turns removing objects from piles, and the one who removes the last object loses. The AI learns from experience by playing against itself, assigning rewards to actions based on their outcomes, and updating its Q-values accordingly.

### Implementation Details
- **State Representation:** A state in Nim is represented by the current size of each pile. For instance, the state [1, 1, 3, 5] signifies 1 object in pile 0, 1 object in pile 1, 3 objects in pile 2, and 5 objects in pile 3.
- **Action Representation:** An action is a pair of integers (i, j), indicating the action of taking j objects from pile i.
- **Q-learning Formula:** The Q-values are updated using the formula: 
```Q(s, a) <- Q(s, a) + alpha * (new value estimate - old value estimate)```

Here, alpha is the learning rate, and the new value estimate considers the reward for the current action and the estimate of future rewards.

## Online Shopping Intent Classifier (k-Nearest Neighbors)

### Overview
This project involves building a nearest-neighbor classifier to predict whether a user browsing an online shopping website intends to make a purchase. Using a dataset of user sessions, the classifier considers various features such as the number of pages visited, browsing day, and web browser used.

### Implementation Details
- **Dataset:** The classifier is trained on a dataset containing information from approximately 12,000 user sessions on a shopping website.
- **Prediction:** The classifier predicts whether a user will make a purchase or not based on the input features.
- **Evaluation Metrics:** Sensitivity (true positive rate) and specificity (true negative rate) are used to measure the classifier's performance.

------------

<sup>This repo is part of Harvard's CS50 AI studies.</sup>
