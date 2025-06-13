📌 Project Journey & Learnings
This project started out as a mini challenge where I wanted to go beyond toy datasets and work with something more real-world and complex. I came across the Telco Customer Churn dataset, and from there, the project began evolving.

🔄 Data Preprocessing Challenges
At first, I faced encoding issues due to the large number of categorical features and formatting bugs. After some trial and error, I discovered a clean and scalable approach using ColumnTransformer from sklearn. This allowed me to combine:

OneHotEncoder for nominal categories

OrdinalEncoder where appropriate

StandardScaler for numerical features

This modular approach really simplified and cleaned up the preprocessing pipeline.

🧠 ANN Model Experiments
I initially used a basic 3-layer ANN, but its performance wasn't satisfying. So I created two more deeper ANN variants to experiment with:

Different numbers of neurons

Models with and without activation functions like Sigmoid

It was fascinating to observe how these architectural tweaks affected learning and performance.

⚙️ Optimizers & Learning Rate Insights
Trying out various optimizers (SGD, Adam, RMSprop, etc.) led me to research how each optimizer works under the hood. This really helped me understand:

When to use which optimizer

The trade-offs between convergence speed and generalization

How crucial learning rate is in model training

This experience helped me build intuition on choosing optimizers and hyperparameters rather than blindly experimenting.
