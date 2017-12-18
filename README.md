# Airbnb-Kaggle
Machine learning project to predict the country where the user will first book the ticket.

This project was part of Kaggle data science hiring challenge by Airbnb
Tasks completed in this project
1) Data Cleaning
2) Graphs plotting
3) Create two varible Test and Train and pass those as a paramter to LogisticRegression

# Logistic Regression

logreg = LogisticRegression()

logreg.fit(X_train, Y_train)

Y_pred = logreg.predict(X_test)

logreg.score(X_train, Y_train)

