# Patients-Severity-States-Classification-based-on-EHR-Data-using-Multiple-Machine-and-Deep-Learning

## Research Paper Title:

Patients’ Severity States Classification based on Electronic Health Record (EHR) Data using Multiple Machine Learning and Deep Learning Approaches

## Submitted into: 

First attempt was into ICPRAM 2022 (https://icpram.scitevents.org/), Second attempt was into ICACDS 2022 (https://www.icacds.com/), both were rejected.


## Authors:

1. A. N. M. Sajedul Alam
2. Rimi Reza
3. Asir Abrar
4. Tanvir Noor
5. Salsabil Ahmed
6. Shihab Sharar
7. Annajiat Alim Rasel

## First attempt abstract:

This paper presents an analysis that is aimed at predicting the severity of patients according to their electronic
health records in a specific time span by implementing supervised and unsupervised machine learning techniques. The proposed approach analyses the severity score prediction using an EHR dataset obtained from
an open-source platform. The data pre-processing was done using tools such as openRefine. To implement
the approach, different supervised learning algorithms such as Random Forest, XGBoost, LightGBM, KNN,
CatBoost, and unsupervised learning algorithms such as K-means clustering, Spectral Clustering, Gaussian
Mixture Model, Hierarchical Clustering and Principal Component Analysis are being used. The experimental
results demonstrate that supervised learning outperforms unsupervised learning on the dataset for the expected
outcomes.

## First attempt future work:

As this work shows performance analysis based on unsupervised and supervised classification techniques, in the future, we will apply regression techniques on these datasets to see how it performs. Also, we will try to improve the classification techniques by doing feature selection and feature engineering. Through our work, we have come across a point where the Gaussian Mixture model works more limited after dimension reduction, which we want to work on later. This future task will include the improvement of the BIC score and the log-likelihood score of the Gaussian Mixture Model. For dimension reduction, we have relied on feature extraction approaches. Other dimension reduction techniques, such as Matrix Factorization, Manifold Learning, and Autoencoder Methods, can be used for this task. Furthermore, similar studies may be performed on various EHR datasets or any COVID19 pandemic related EHR datasets to see how these algorithms perform on various datasets.


## First attempt conclusion:

In this paper, a performance analysis of predicting the patient severity scores has been proposed and successfully implemented by applying supervised and unsupervised machine learning techniques upon an EHR dataset. This analysis is planned and executed with consideration of blood test report data such as the patient’s amount of Hematocrit, Hemoglobin, Erythrocyte, Thrombocytes and all the other measurements of different cells in blood. Our proposed approach can assess and forecast the severity of patients in cases when there is a shortage of medical beds in pandemics and we can’t provide all of the patients beds in the hospital, so we have to make quick decisions about who needs a medical bed and who doesn’t. In this instance, instead of human brain decisions, this strategy can make things faster as an automated procedure. Patients with less severe conditions can simply be alerted about their health status and taken home; on the other hand, when patients are at high risk, their families can take required steps to improve the paient’s position. As a result of our research, we discovered that supervised classification algorithms outperformed unsupervised algorithms in predicting patient severity score.

## Second attempt abstract:

This research presents an examination of categorizing the severity
states of patients based on their electronic health records during a certain time
range using multiple machine learning and deep learning approaches. The
suggested method uses an EHR dataset collected from an open-source platform
to categorize severity. Some tools were used in this research, such as
openRefine was used to pre-process, RapidMiner was used for implementing
three algorithms (Fast Large Margin, Generalized Linear Model, Multi-layer
Feed-forward Neural Network) and Tableau was used to visualize the data, for
implementation of algorithms we used Google Colab. Here we implemented
several supervised and unsupervised algorithms along with semi-supervised and
deep learning algorithms. The experimental results reveal that
hyperparameter-tuned Random Forest outperformed all the other supervised
machine learning algorithms with 76% accuracy as well as Generalized Linear
algorithm achieved the highest precision score 78%, whereas the
hyperparameter-tuned Hierarchical Clustering with 86% precision score and
Gaussian Mixture Model with 61% accuracy outperformed other unsupervised
approaches. Dimensionality Reduction improved results a lot for most
unsupervised techniques. For implementing Deep Learning we employed a
feed-forward neural network (multi-layer) and the Fast Large Margin approach
for semi-supervised learning. The Fast Large Margin performed really well with
a recall score of 84% and an F1 score of 78%. Finally, the Multi-layer
Feed-forward Neural Network performed admirably with 75% accuracy, 75%
precision, 87% recall, 81% F1 score.

## Second attempt limitations & future Work:

In the future, we will try to collect more real-time datasets from other hospitals so that
the models can be trained better to predict the categorization of illness severity states
of patients. As a limitation of this research, we can include that we just worked on one
dataset from one private medical company from Indonesia, which we can not rely on
in case of providing automated medical services to patients as it can be risky.
Although if we can manage more data from several medicals the data range should be
larger. In this dataset we have 4, 412 patients’ data, in the future we are planning to
work with more than 10, 000 patients’ data to come up with better outputs. Another
limitation of this research work was we only used one method for implementing the
semi-supervised machine learning technique and one method for implementing the
deep learning technique. For future research, we want to use several deep learning and
semi-supervised techniques. Additionally, we only trained our models, but could not
deploy them into our IoMT devices successfully, though we tried to, as we had a
shortage of time, we decided to deploy our custom models of classification illness
severity in the future. Furthermore, the dataset should have more variety, as it was
collected from another research work from Indonesian researchers [6], the dataset was
from a private hospital and from a specific country if data can be collected from
different countries and different types of clinics such as government, private, military
clinics, this research would be more impactful. Because then the dataset will have
more varieties of patients who belong to different classes of society. It would be more
realistic research then.

## Second attempt conclusion:

This research proposes and effectively implements a performance analysis of
categorizing the illness severity from their electronic health record data using
supervised, unsupervised, semi-supervised machine learning as well as deep learning
techniques. This study is planned and carried out with the help of clinical report data
such as the patient's Hematocrit, Hemoglobin, Erythrocyte, Thrombocytes, and all
other measurements of different cells in the blood. Our proposed approach can
analyze and forecast the severity of patients’ illness in situations when there is a
scarcity of medical services because of the large number of patients and medical staff
cannot give all of the patient's services in the hospital because of limited spaces,
therefore we must make quick decisions about who requires emergency care and who
does not. In this case, rather than relying on the human brain decisions of medical
staff, this method can expedite things as an automated procedure. Patients with less
severity of the illness can simply be informed of their condition and taken home; on
the other hand, when patients are at high risk, they will get higher priority to get
medical service first. From this research, we found multiple supervised, unsupervised,
semi-supervised machine learning and deep learning algorithms are useful for
categorizing patients’ illness severity states as a result of our research. In a short
summary from result analysis, from unsupervised clustering techniques,
hyperparameter-tuned Hierarchical with 86% precision score and Gaussian Mixture
Model with 61% accuracy worked really well. Noticeably, dimension reduction
helped a lot to improve results, especially in the case of unsupervised methods.
Furthermore, from supervised learning techniques, hyperparameter-tuned Random
Forest outperformed all other supervised techniques at the accuracy of 0.76, also
according to precision score Generalized Linear algorithm performed the best with
78% score. The Semi-supervised approach Fast Large Margin performed
unexpectedly well with 84% recall score and 78% F1 score. Lastly, the Deep learning
approach Multi-layer Feed-forward Neural Network performed outstandingly with
75% accuracy, 75% precision, 87% recall, 81% F1 score. As our goal of this research
was to improve the previous work [6] and try out different new models, we were able
to do both and from our observations, we found out in previous work
hypermeter-tuned XGBoost was performing best, but in our experiments, Random
Forest performed best among supervised classifiers with 76% accuracy. Also, in
previous work [6], they only used supervised classification, but we tried out,
supervised, unsupervised, semi-supervised machine learning models along with deep
learning techniques, and from these new model experiments we got new insights
which we have explained in detail already


## Organization:

Brac University, School of Data & Sciences, Deparment of Computer Science and Engineering.