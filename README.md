We Will use the Boston housing regression problem that 13 inputs and one numerical target and requires learning th erelationship between suburb characterestics and house prices.at the first step we were preper
an using the TransformedTargetRegressor, A naive regression model that predicts the mean value of the target on this problem can achive a mean absolute error(MAR) of about 6.569, we will aim do better, we will fit
HuberRegressor class and normolize  the input variables using a Pipeline and in the second step we were also explore using other data transforms on th etarget variable such as the PowerTransformer that can make
each variable more-Gussian-Like(using the Yeo-Johbson transform) and improve the perfomance of linear models.
