from sklearn.preprocessing import StandardScaler
sc_X = StandardScaler()
sc_y = StandardScaler()


X_train = sc_X.fit_transform(X_train)
y_train = sc_y.fit_transform(y_train)

y_pred = sc_y.inverse_transform(regressor.predict(sc_X.transform(X_test)).reshape(-1,1))

in standard scarlar what willhappen if we do fit_transform , transofrm and inverse_transform 

---

STANDARD SCALER

When the features of the given dataset fluctuate significantly within their ranges or are recorded in various units of measurement, StandardScaler enters the picture.

The data are scaled to a variance of 1 after the mean is reduced to 0 via StandardScaler.outliers present in data have a significant impact that reduces the spectrum of characteristic values.

#### we must normalize the data (µ = 0, σ = 1). 


![](../../../IMG20240809150759.jpg)





