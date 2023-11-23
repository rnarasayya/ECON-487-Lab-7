# ECON-487-Lab-7
1)	Coding up Double ML.
a.	Use the Double ML algorithm to estimate the own price elasticity for Tropicana, Minute Maid and Dominick’s using all available lagged features in the ML models including feat as a predictor. You’ll estimate three separate regressions one for each brand for the final stage OLS residuals regression.  
i.	I suggest using a random forest or XGBoost for P and Q.
ii.	I also suggest using store and week fixed effects in your model.
iii.	I also suggest using the interaction of important lagged price and quantity variables interacted with sociodemographic characteristics.
b.	Now do the same thing but estimate the full 3x3 elasticity matrix.  Remember that for the OLS regression you’ll have residual log sales on the left and residual log price dom, residual log price MM and residual log price trop on the RHS and you’ll estimate three separate regressions one for each brand.  
