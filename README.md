# DP-Project---ThePySquad
**Health Insurance Cross Sell Prediction**
**Predict Health Insurance Owners' who will be interested in Vehicle Insurance**
Our client is an Insurance company that has provided Health Insurance to its customers now they need your help in building a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

An insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium. A premium is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee.

For example, you may pay a premium of Rs. 5000 each year for a health insurance cover of Rs. 200,000/- so that if, God forbid, you fall ill and need to be hospitalised in that year, the insurance provider company will bear the cost of hospitalisation etc. for upto Rs. 200,000. Now if you are wondering how can company bear such high hospitalisation cost when it charges a premium of only Rs. 5000/-, that is where the concept of probabilities comes in picture. For example, like you, there may be 100 customers who would be paying a premium of Rs. 5000 every year, but only a few of them (say 2-3) would get hospitalised that year and not everyone. This way everyone shares the risk of everyone else.

Just like medical insurance, there is vehicle insurance where every year customer needs to pay a premium of certain amount to insurance provider company so that in case of unfortunate accident by the vehicle, the insurance provider company will provide a compensation (called ‘sum assured’) to the customer.

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

Now, in order to predict, whether the customer would be interested in Vehicle insurance, you have information about demographics (gender, age, region code type), Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.

**Variable	Definition**
**_id_** : Unique ID for the customer 
**_Gender_** : 	Gender of the customer
**_Age_** :	Age of the customer
**_Driving_License_	0** : Customer does not have DL, 1 : Customer already has DL
**_Region_Code_**: 	Unique code for the region of the customer
**_Previously_Insured_	1** : Customer already has Vehicle Insurance, 0 : Customer doesn't have Vehicle Insurance
**_Vehicle_Age_** :	Age of the Vehicle
**_Vehicle_Damage_	1** : Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.
**_Annual_Premium_** :	The amount customer needs to pay as premium in the year
**_PolicySalesChannel_** :	Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.
**_Vintage_** :	Number of Days, Customer has been associated with the company
**_Response_**	1 : Customer is interested, 0 : Customer is not interested
