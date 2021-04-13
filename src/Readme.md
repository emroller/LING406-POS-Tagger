# POS Tagger using SciKitLearn Classifiers
# This program is a part-of-speech tagger that uses four classifiers to determine the part of speech of a target word.
The baseline Jupyter notebook file (emilyroller_baseline.ipynb) provides a baseline tagger that is essentially what was implemented in lab. It calculates the accuracy, precision, recall, and f-measure for three different classifiers (Dummy, Naive Bayes, and Decision Tree) using 5-cross fold validation. The average of these values are printed to standard output. 
The improved POS tagger Jupyter notebook (emilyroller_postagger.ipynb) provides an *improved* baseline tagger, as well leave-one-out tagging where one feature column is dropped. The accuracy, precision, recall, and f-measure are calculated for the same three classifiers as the baseline plus a Random Forest classifier. The results of this program are saved in the file src/table.txt.
# Instructions to run:
Ensure that the input file is titled "pos-eng-5000.data.csv" and is stored in the src/DATA directory. To run either of the ipynb files in the src/Code folder, just run all cells starting from the top of the file. Answers will be saved in the table.txt file in the src directory.

