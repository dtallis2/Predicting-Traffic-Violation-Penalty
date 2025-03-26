# Predicting-Traffic-Violation-Penalty
Download the Stratified Sample Dataset
Open Weka and load updated_stratified_sample.arff
Click on the “Select Attributes” tab and choose “OneRAttributeEval”
  When prompted to select “Ranker” search, select yes
Select “Search Outcome” as class in drop down menu
Click Start
Use the cutoff value of 60 (inclusive) to select attributes
In the “Preprocess” tab select All in the Attributes window, unselect the chosen attributes and the class attribute, and press Remove
  Alternatively, download the OneR Evaluation Dataset
  Open Weka and load oner_eval.arff
Navigate to the “Classify” tab
Choose weka → classifiers → bayes → NaiveBayes
Ensure “Cross-validation” with 10 folds in chosen in Test options pane
Ensure class in correct
Click Start
