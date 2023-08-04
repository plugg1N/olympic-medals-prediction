
# 🥇🏅 Predict Olympic Medals of Each Country's Team

My own take on solving problem to predict amount of medals, that they would receive on a new year of olympic games solution is pretty straightforward. I've checked the correlation of each factor to "y" (wanted "medals") factor as it was true for other cases, **amount of medals received earlier had the biggest correlation to amount received next time**

Furthermore, as logical as it seems, *amount of players* played the biggest role too!

> More players = more medals

## 🎯 Results

I've tried LinearRegression model from **Scikit-leanr** library, and it was pretty accurate on test. But it turned out, that **RandomForest** Was best with R^2 over 92%! 
