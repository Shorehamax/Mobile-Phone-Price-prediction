# Mobile-Phone-Price-prediction
The phone price varies from a few hundred dollars to thousands of dollars which is a very wide range. I 
would like to investigate what factors influence the phone price via the dataset that contains the specs of 
phones and the corresponding prices, so people can expect what the proper price a phone should have 
when they want to purchase a new phone and avoid buying an overpriced phone with extra money. It is 
particularly important because people can save some money from accidentally buying those overpriced 
phones.
I made the model that consisted of The price of phone, which is the response variable, and resolution of 
the phone, Phone Pixel Density, the number of CPU cores, CPU frequency(GHz), internal memory of the 
phone, RAM of the phone, battery size and thickness of the phone.
I used boxplots, histograms, scatter plots to demonstrate the distribution of the raw data from the 
original dataset, then use the summary p-value and BIC backward method to remove the predictors that 
don’t significantly relate to the price of the phone. I also used the VIF to check the multicollinearity, and 
marginal model plots to see if the data fit the model.
We can summarise that the CPU performance, RAM are strongly positive related to the price of the 
phone, resolution, thickness are negative related to the price of the phone. Internal memory, Phone Pixel 
Density, battery size are slightly positively correlated to the price of the phone
