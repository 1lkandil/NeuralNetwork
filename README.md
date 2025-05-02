# A Beginner-Friendly Overview of Neural Networks

## Project overview
In this project, we aimed to predict user ratings for video games based on a dataset of over 47,000 games. The features included data like price, genre, publisher, platform, and game length. We leveraged deep learning techniques, specifically neural networks, to assess how different features influenced game ratings. By using PyTorch, we trained the model and gained insights into the potential of neural networks to work with structured datasets.

## Key findings

**Embeddings**
- Embeddings were used for categorical features, reducing data complexity and allowing the model to capture deeper relationships. For example, the model learned that games from similar platforms or publishers shared certain rating trends.

**RMSE**
- Root Mean Squared Error (RMSE) was used as the loss function to penalize large errors, helping the model improve over time. The RMSE dropped significantly, indicating that the model was learning meaningful patterns and generalizing its predictions well.

**Models and Techniques**
- **Neural Network with Embeddings:** Neural networks, traditionally used for unstructured data, were adapted for structured datasets with embeddings to handle categorical features like genre and publisher.
- **Gradient Descent:** The model used gradient descent to iteratively adjust its weights, learning from errors to minimize loss and improve accuracy.

## Data sources
- **Video Game Dataset:** A collection of over 47,000 games, including numerical features such as price, release year, and game length, and categorical features like genre, publisher, and platform.
- **Feature Engineering:** Non-essential columns were removed, and we focused on relevant gameplay features such as price, game length, and story.

## Project files and organization
- **data/** – CSV files containing raw and processed game data.
- **notebooks/** – Jupyter notebooks used for data preprocessing, model training, and evaluation.
- **presentations/** – PDF of the presentation summarizing the project findings.
- **articles/** – LinkedIn article detailing the project process and results.
