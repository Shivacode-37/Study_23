Machine Learning - is the science (and art) of programming computers so they can learn from data.
- The examples that the system uses to learn are called the *Training set*
- The part of the machine learning system that learns and makes predictions is called a *model*.
* (Neural networks and random forests are examples of models.)
- Digging into large amounts of data to discover hidden patterns is called *Data Mining*.
## Examples of Applications ##
* Analyzing images of production on a production line to automatically classify them.
* Detecting tumors in brain scans.
* Automatically classifying new articles.
* Creating a chatbot or personal assistant.
* Detecting credit card frauds.

# Types of Machine Learning Systems:
1. Supervised
2. Unsupervised
3. Semi-Supervised
4. Self-Supervised

``` Supervised Machine Learning ```
* The training set you feed to the algorithm includes the desired solutions, called *labels*.
- A typical supervised learning task is *classification*. (Ex- Spam filter)
- A typical task to predict a target numeric value, such as price of car. This sort of task is called *Regression*.

*** Note: Some regression models can be used for classification as well as vice versa. (e.g. Logistic Regression is commonly used for classification) ***

``` The words target and label are generally treated as synonyms in supervised machine learning, But
Target is more common in regression and label is more common in classification tasks.
Features are sometimes called predictors or attributes. ```

 ```UnSupervised Learning 
 ```

* The traning data is unlabeled. The system tries to learn without teacher.
- *Clustering algorithm* to try to detect groups of similar visitors.
- *Hierarchical clustering algorithm*, it may also subdivide each group into smaller groups.

* *Visualization algorithms* are also good examples of unsupervised learning: You feed them lot of complex and unlabeled, and tey output a 2d or 3d representationof your data that can easily be plotted. - These algorithms try to preserve as much as structure as they can(e.g trying to keep separate clusters in the input space from overlapping in the visualization and perhaps identify unsuspected patterns.)

- *Dimensionality reduction* the goal is to simplify the data without losing too much information. One way to do this is to merge several correlated features into one. This is called *Feature Extraction*.
* Benefits: It will run much faster, ythe data will take up less disk and memory space, and in some cases it may also perform better.

- Important unsupervised task is *Anomaly detection* - (Ex-Detecting unusual credit card-) - The system is shown ostly normal instances during training, so it learns to recognize them;  then, when it sees a new instance, it can tell whether it looks like normal one or whether it is likely aan anomaly.
- *Novelty Detection* It aims ot detect new instance that loook different from all instances in the training set.

- *Association rule learning* in which the goal is to dig into large amounts of data and discover interesting relation between attributes.

