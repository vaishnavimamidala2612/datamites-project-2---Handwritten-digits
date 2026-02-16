Objective: To analyze and classify grayscale images of handwritten digits from the standard MNIST benchmark dataset.

Dataset: Utilizes 70,000 images, each consisting of 784 features (28x28 pixels) representing digits 0 through 9.

Data Preprocessing: * Fetched data using the fetch_openml method.

Applied feature scaling via StandardScaler to handle high-dimensional data and improve model convergence.

Model Implementation: Built and compared various classification algorithms, including:

Logistic Regression: Established as a baseline model.

Support Vector Machine (SVM): Identified as the best-performing model for this classification task.

Evaluation: Models were assessed based on accuracy scores and detailed classification reports to determine the most effective digit recognizer.
