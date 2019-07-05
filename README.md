# Letter-Recognition-through-Ensemble-Classification
<UL>
<li> Exploratory data analysis is done on the data to do the Data Preprocessing if needed.</li>
<li> Classes/Labels distribution in the data is visualized by using PCA.</li>
<li> Hyper parameter Tuning is done on various Classification algorithms (Decision Tree, KNN, Naive Bayes, Linear and Non-Linear SVM).</li>
<li> Error Plots and Heat maps are generated by using Matplotlib and Seaborn packages respectively to validate the performances of Classifiers with various parameter values to determine the optimal parameter configuration.</li>
<li> KNN and Poly SVM performs better than the other Models with accuracies 94%, 91% respectively. </li>
<li> Since Poly SVM and KNN are lazy learners, Ensemble Learning is implemented on Quick learners inorder to match the performance of KNN and Poly SVM </li>
<li> Homogeneous(Dependent, Independent), Heterogeneous Ensemble methods are applied on the Decision Tree and linear SVM.</li>
<li> Error Plots are visulaized to validate the performance of Ensemble Classifiers to find the optimal no.of estimators.</li>
<li> Two tail Pair T-test is conducted to find the statistical difference between the Classifier Performances/Accuracies. </li>
<li> Time Plots are generated to find the quick learner which is efficient in every manner and can have the best performance among all          classifiers.</li>
<li> By implementing Adaboost on Descision Tree 93% Accuracy is achieved and the training time of the Model is reduced by 46% of the KNN training time.
<li> Performance of each classifier is also validated with respect to every class by checking Specificity and Sensitivity values along with      Time complexity to determine Adaboost of Decision Tree as the best Hypothesis. </li>
