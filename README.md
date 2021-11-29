# ML Models Predicting Cooking Durations of Different Recipes
Seth Ng & Wong Li Sean

## Summary
This project aims to dive into the different types of supervised Machine Learning models, how the differ from one another, how they work, and how one may be more beneficial in certain sitautions than others. The case used was for the models to predict the cooking duration labels (quick, medium, slow) of different recipes. The datasets provided included i) the name of the dish, ii) the number of steps in the recipe, iii) the number of ingredients, iv) the list of ingredients, and v) the steps taken. Each model took in a feature list which includes the number of steps & ingredients and the Doc2Vec features (more information in the 'data' folder's README) provided as well. The training set also included the actual duration label for its dishes.

For a more in-depth look at our methods, analyses, and findings please take a look at 'Report.pdf' as well as 'Notebook.ipynb'.

All functions should be run right from the notebook file in order from top to bottom. To avoid the long computation time you may just view the results already shown.

## Models used and analysed include:
- Gaussian Naive Bayes (GNB)
- Decision Trees
- Standardised Linear Support Vector Classification (SVC)
- Logistic Regression
- A stacked model using all four of the above

## Notes
- The files 3.1, 3.2, and 3.2 in the 'data' folder were omitted due to their large capacity.
