# Iowa Liquor Sales
Liquor Sales + Linear models

--- 

### Overview
This was the second project from my DSI program experience at General Assembly. 

Pre-knowledge: Linear regression models in scikit-learn, how goals & business objectives translate to model fit, and how to optimize models using cross-validation. 

---

### Data
Data set from the state of Iowa, [here](https://www.dropbox.com/s/5oiz27mhvsiibo8/iowa_liquor_sales_proj_2.csv?dl=0), which contains transactions for all stores that have a class E liquor license.

NOTE: I used the 10% data set because the full data set was to big for my computer to handle.
[The 10% dataset version of Iowa liquor sales](https://drive.google.com/file/d/0Bx2SHQGVqWaseDB4QU9ZSVFDY2M/view?usp=sharing).

---


### Task: State tax board
The Iowa State legislature is considering changes in the liquor tax rates and wants a report of current liquor sales by county and projections for the rest of the year to inform their decision.

* Identify the problem
* Acquire the data
* Explore the data
* Mine the data
* Refine the data
* Build a data model
* Present the results

**Goal:** 
* Calculate the yearly liquor sales for each store using the provided data. The transactions for each year can be added up, and store sales in 2015 specifically can be used as the target variable.
* Use the data from 2015 to make a linear model to predict the yearly sales of all stores. Sales from January to March must be one of your variables.
* Use model for 2015 to estimate total sales in 2016, extrapolating from the sales so far for January to March of 2016.
* Report your findings, including any projected increase or decrease in total sales (over the entire state) for the tax committee of the Iowa legislature.
* Use cross-validation to check how the model predicts to held out data compared to the model metrics on the full dataset.
* Fit the model using one or both of the regularization tactics covered. Explain whether the regularized or the non-regularized model performed better and what the selected regression are doing.

---

###  Presentation
Stakeholder presentation that covers methodologies, process, findings, conclusion and recommendations. Please se pdf of presentation in repo.