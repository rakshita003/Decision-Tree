## Decision-Tree

This is a Java-based Decision Tree project that includes various components for building and working with decision trees. It provides tools to create, train, and evaluate decision trees using different datasets. The project includes the following files:

- **ActualDataSet.java**: A class for representing the actual dataset used for training and testing decision trees.
- **Attribute.java**: A class for defining attributes and their properties.
- **AttributeType.java**: An enumeration for different attribute types.
- **CSVReader.java**: A utility class for reading datasets in CSV format.
- **DataReader.java**: A utility class for reading datasets and creating ActualDataSet instances.
- **DataSet.java**: A class for representing a dataset.
- **DecisionTree.java**: The main decision tree class, responsible for building and using decision trees.
- **EntropyEvaluator.java**: A class for calculating entropy in the dataset.
- **GainInfoItem.java**: A class for storing information gain values for attributes.
- **InformationGainCalculator.java**: A class for calculating information gain.
- **Util.java**: A utility class with various helper methods.
- **VirtualDataSet.java**: A class for representing a virtual dataset.

## Usage

You can use this project to create and work with decision trees in Java. Here are the basic steps to get started:

- Import the project into your Java development environment.
- Use the provided classes to load your dataset, define attributes, and create a decision tree.
- Train your decision tree using the dataset.
- Use the decision tree to make predictions or perform classification tasks.

## Algorithm Used

### Sharon's Algorithm for Decision Trees

Sharon's Algorithm is a method used for constructing decision trees in classification tasks. It aims to find the best attribute to split the dataset at each node to maximize information gain. The algorithm follows these steps:

1. **Calculate Entropy**: Measure the impurity of the current dataset by calculating its entropy.

2. **For Each Attribute**:
   - Calculate the information gain by splitting the dataset based on that attribute.
   - Information gain quantifies how much the attribute reduces uncertainty in classifying data.

3. **Choose Best Attribute**: Select the attribute with the highest information gain as the splitting attribute. This becomes the decision node of the tree.

4. **Recursion**: Recursively apply steps 1-3 to the subsets of data created by the chosen attribute, creating child nodes in the decision tree.

5. **Termination**: Continue this process until all data points are classified or a predefined stopping criterion is met.

This algorithm is commonly used in decision tree construction to make informed decisions about splitting data based on attributes.

## Contact

If you have any questions or need further information, please contact [EMAIL](mailto:rmath049@uottawa.ca).

Happy decision tree building! 🌳🤖







