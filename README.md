## Random Forest Implementation - Tensorflow
### Project #2

This project continues the work from the first project, exploring different models beyond AutoGluon. Today, the focus is on implementing a Random Forest using TensorFlow.

TensorFlow is a widely-used Python library for running artificial intelligence models, providing tools for both training and inference.

**Project Goals** 

* Continue the exploration of the dataset from the previous project.
* Implement a Random Forest model using TensorFlow.
* Compare the performance of the Random Forest model against the AutoGluon model.
* Evaluate the model's effectiveness and analyze the results.

**Dataset**

The dataset used in this project is the same as in the previous challenge. For details, refer to the earlier project documentation.

**Tools and Technologies**

* Python
* TensorFlow
* Pandas
* NumPy
* Scikit-learn

**Random Forest Overview**

Random Forest is a technique used for classification or regression tasks. It works by creating multiple decision trees and using either majority voting (for classification) or averaging the predictions (for regression) from those trees. Random Forest is known for its high accuracy and robustness against overfitting, making it a popular choice in various practical applications.

### Conclusion

The correlation increased from 0.29 to 0.305 as observed on the figure below, which is not a significant improvement. The issue might be more related to data preprocessing rather than the model itself. After all, data science relies heavily on the quality of the data rather than the model used. Therefore, proper data engineering should be applied beforehand to achieve significant improvements. Once data preprocessing is thoroughly done, the model should be adjusted or replaced to compare results effectively.

![output](output/output.png)

### Next Steps

The next steps involve focusing on data preprocessing to address any issues within the dataset. After refining the data, the model should be reevaluated, and potentially new models should be tested to achieve better performance.

