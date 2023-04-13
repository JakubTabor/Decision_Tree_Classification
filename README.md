# Decision_Tree_Classification
# When I get my "X" and "y" ready I can import "train_test_split" and get "train" nad "test" set 
# Then I make feature scaling, so import "StandardScaler" and prepare my "X_train" and "X_test" """sc.fit_transform(X_train)""" """sc.transform(X_test)"""
# Now I import "DecisionTreeClassifier" and set "criterion" to "entropy"
# And then train my model """classifier.fit(X_train, y_train)""" and get prediction """classifier.predict(sc.transform([[30, 87000]]))"""
