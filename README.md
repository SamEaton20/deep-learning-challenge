# deep-learning-challenge
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
# Preprocess
- Read in the charity_data.csv to a Pandas DataFrame
- Drop the EIN and NAME columns.
- Determine the number of unique values for each column.
- For columns that have more than 10 unique values, determine the number of data points for each unique value.
- Use the number of data points for each unique value to pick a cutoff point to combine "rare" categorical variables together in a new value, Other, and then check if the replacement was successful.
- Use pd.get_dummies() to encode categorical variables.
- Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.
- Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.
# Compile, Train, Evalute Model

# Resources
I used ChatGPT to clean up my code and clean my report.
