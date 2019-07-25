# PREDICTING PROFITABILITY

The fictional sales team of Blackwell Electronics asked for another analysis regarding sales performance of certain products in one of their stores. This time, the analysis aims at the prediction of sales performance but taking the product type into account to see whether and how specific product types outperform others. Therefore, the historical sales data on sales volume has to be analysed to assess whether the inclusion of ‘product type’ has a positive impact on predictability and finally to predict sales volume of four products types: PC, Laptops, Netbooks and Smartphones.
Additionally, Blackwell expresses their interest in assessing the impact of service reviews and customer reviews on sales performance.

# PROCEDURE

The analysis followed the common data mining approach including the following steps:
Exploration, pre-processing, modelling and optimization, prediction, and evaluation.
For the analysis, the statistical programming language R was used with different packages (highlighting ‘caret’ to apply several prediction techniques). Other tests include Correlation Matrix, Random Forest and ANOVA. These were applied to assess the importance of ‘product type’ among other attributes.

# RESULTS

Product Type | Brand    | Volume  | Profit (in k$)
------------ | -------  | ------  | ------  
Netbook	     |Acer	    | 734     | 22 
PC	         |Dell1	    | 267     | 47 
Smartphone	 |Samsung2  | 267     | 2 
Laptop	     |Apple	    | 225     | 27
Smartphone	 |Motorola1	| 181     | 4
Smartphone	 |Motorola2	| 167     | 6
PC	         |Dell2	    | 152     | 26
Netbook	     |Asus	    | 137     | 7
Smartphone	 |HTC	      | 134     | 3
Netbook	     |hp	      | 101     | 3
Netbook	     |Samsung1	| 95      | 3
Laptop	     |Toshiba	  | 77      | 14
Laptop	     |Razer	    | 0       | 0
