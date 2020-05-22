# Context
When the outbreak reached France, I started a project to try to predict the future evolution. Especially I found this article https://towardsdatascience.com/using-kalman-filter-to-predict-corona-virus-spread-72d91b74cc8 and I wanted to try to at least reproduce the results

# Repository structure
In this repository you will find the following 
* The original repository from the article : COVID19_Kalman
* Another repository which contains a University class about Kalman filters : Kalman-and-Bayesian-Filters-in-Python
* My own Notebook : covid19_prediction.ipynb
* Data extracted from the Johns Hopkins University

# Approach
At the beginning, the idea was to understand the work described in the article above, try to reproduce the results an get new one. However, even though, I studied Kalman Filters at school, the overall theory felt a little bit overwhelming (i.e. in the context of a side project, I could not spend hours or days trying to get the theory back), second it looked like it was involving building algorithms from scratch and that few readily available packages where out there. Finally, the data preprocessing part took longer than expected. Therefore I used this project as a learning opportunity for Data Wrangling and to try the Facebook package <a href="https://facebook.github.io/prophet/docs/quick_start.html">FbProphet</a>

# Conclusion

The FbProhet package was not a good fit for this purpose. It works best for predictions with longer historical data with the ability to dectect daily, weekly and yearly components of complex Time Series. I will reuse this package in the future for a Stock Price prediction project
