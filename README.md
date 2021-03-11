# Ecommerce_Customers_Linear_Regression_Project
# Ecommerce Customers Linear Regression   In this project fundamental Data Analysis and Machine Learning is done with the data of customers at an Ecommerce company based in New York City.  (This is not real data from a company but was compiled using other sources.)  The company sells clothing online but they also have an in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, and then order from home using either a mobile app or website for the clothes they want.  The company wants to determine if they should focus their efforts more on the mobile app or the website.  The libraries used in this project are Pandas, Seaborn, Matplotlib and Scikit-learn.   The numerical columns in our dataframe are as follows: * Avg. Session Length: Average session of in-store style advice sessions. * Time on App: Average time spent on App in minutes * Time on Website: Average time spent on Website in minutes * Length of Membership: How many years the customer has been a member.  Analyses that are done in this project:  * Various visualizations are used to detect patterns in the data * An lmplot() shows the strong positive correlation between the yearly amount a customer spends and the length of her / his membership. * The numerical data is then trained, tested and fitted to a linear regression model and the model is evaluated using the test set of the data.  A scatterplot for the y test values against the predicted y values shows that we have a very good model. * The Mean Absolute Error, Root Mean Squared Error and R^2 is determined and interpreted.  From these metrics we can deduce that the model is a very good fit for the data and that R^2 accounts for 99% of the variation in the data.  * The linear coefficients from the numerical columns are interpreted.  A conclusion is made on the company’s question of whether they should spend more efforts on developing the mobile app or the website.  This project was done through Jose Portilla (head of Data Science at Pierian Data Inc.) on Udemy (Python for Data Science and Machine Learning Bootcamp).
