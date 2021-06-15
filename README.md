# unification-documentation 


##  CDP ( customer Data Platform)

A CDP connects to a wide range of systems and data sources across an organization using built-in connectors, SDKs, webhooks, and APIs. It collects all types of data, including profile data and real-time interaction data (behavioral, demographics, transactional), campaign data, product data, customer support data, mobile and device data, IoT data, and more.

![image](https://user-images.githubusercontent.com/63542990/121841897-eb832f00-ccfc-11eb-8f99-df1f7b5c3652.png) 

##  CDP Data Unification

 customer data must be unified into a single customer profile using a process known as customer identity resolution or data unification. Customer identity resolution includes sophisticated algorithms to stitch identifiers from multiple systems. Identity stitching automates identity graph creation and continuously unifies data into profiles as your customers continue to engage.
 
 
![image](https://user-images.githubusercontent.com/63542990/121843135-5a618780-ccff-11eb-8092-96b3acce381a.png)

![image](https://user-images.githubusercontent.com/63542990/121870392-a244d680-cd20-11eb-88e9-52dd8449854e.png)



## Types of Unification 

# Deterministically:
Unique IDs for customer records in each system are matched using common information, such as an email address or name. This high confidence approach works best when first-party data is readily available.

# Probabilistically:
This approach analyzes a variety of customer data points to estimate the statistical likelihood that two identities are the same customer. While statistical connections aren’t as definitive as authenticated IDs, they can be extremely helpful when first-party data is limited.

## About  Data

# Investor Data
![image](https://user-images.githubusercontent.com/63542990/121997818-96145400-cdc8-11eb-88d0-f3ec00c3ebe5.png)


# Distributer Data
![image](https://user-images.githubusercontent.com/63542990/121998266-3d918680-cdc9-11eb-945d-6d3471c60658.png)

# Channel Data 
![image](https://user-images.githubusercontent.com/63542990/121998700-e93ad680-cdc9-11eb-9776-2e694d25f3fe.png)


1.orm data
2.web data
3.android data
4.ios data

we have to merge invseter data or distributer data to create a master data and then map to channel data like orm,web ,android, ios

# Unification Work Flow
![image](https://user-images.githubusercontent.com/63542990/121998969-50588b00-cdca-11eb-992b-c5bd0eed2747.png)

1).Read all the data of all six file.
2). Data cleaning.
3). preprocessing and validation.
4). clustering using( k means cluster).
5). then assign a probality value based on heigh medium or low feature.
6). final output will be consider as four unification file for four diffrent channel.






