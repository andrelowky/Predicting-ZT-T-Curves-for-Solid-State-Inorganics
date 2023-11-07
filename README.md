# Predicting-ZT-T-Curves

Using a curated starrydata csv, I attempt to create a model to predict the entire ZT-T curve of an inorganic compound. Since the dataset is sparse and incomplete, I crafted a curve fitting function that is adapted to different shapes (parabolic, linear, sigmoid). I try different means of fitting the data to a model, either by considering ZTs at specific temperatures, or by directly predicting for coefficients of the fitted function.
