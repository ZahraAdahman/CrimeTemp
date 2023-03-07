# CrimeTemp
How does the changes in daily temperature influence the amount of violent crimes in Massachusetts state?

### Materials and techniques
#### The daily temperature dataset 
Temperature data was gotten from AWS Marketplace
by https://theclimatedatafactory.com/
https://aws.amazon.com/marketplace/pp/prodview-imlqd3epbsufk?sr=0-2&ref_=beagle&applicationId=AWSMPContessa#overview

The dataset contains daily temperature data from January 1st, 2018-October 11th, 2020 across major cities, Boston, MA, Chicago, IL, New Orleans, LA, Seattle, WA, Atlanta, GA, and New York, NY,
The dataset was processed on the data from Boston MA, to represent the temperature data for Massachusetts State.
#### The crime dataset 
 The crime data for Massachusetts from 2018 to 2020 was gotten from the Federal Bureau of Investigation Crime Data Explorer, and Uniform Crime Reporting Program. The compressed file folder was downloaded for each of the year 2018, 2019 and 2020 and the incident.csv files were extracted for each year. It is important to note that only the number or frequency of crime reported will be analysised. Additional data is located in the compressed zip files such as location, type of offense etc.
### Data visualization and analysis
![image](https://user-images.githubusercontent.com/59964869/223541090-45d5c943-ca5a-40a6-a4a4-2592681e6e9e.png)
![image](https://user-images.githubusercontent.com/59964869/223541220-24ecf57b-604b-48eb-9c06-f6b825a0412e.png)
### Times series decomposition
![image](https://user-images.githubusercontent.com/59964869/223541599-b001b20c-8392-43a2-a94f-8ea30e4997b0.png)
### Correlation analysis
![image](https://user-images.githubusercontent.com/59964869/223541761-301590d6-0f65-42bf-9828-4190b545294d.png)
### Time-series Modeling
#### SARIMA
![image](https://user-images.githubusercontent.com/59964869/223542238-6948b8d8-8c31-4c27-8f29-876589b0a326.png)
![image](https://user-images.githubusercontent.com/59964869/223542644-be22b705-8d17-438b-a04f-6c30b216c342.png)
#### LSTM recurrent neural network
![image](https://user-images.githubusercontent.com/59964869/223542927-bbb23109-e3d2-44bd-a867-04826dcab0cc.png)
