# Global-Terrorism-Analysis
The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START), headquartered at the University of Maryland.

![650413-terror-011817](https://user-images.githubusercontent.com/32620288/137513463-8ffa196e-d019-4921-a69a-6636d44d2279.jpg)

-----------------------------------------------------------------------------------------------
### Data Description
* ‘Year’: For Terror attack year
* 'Month’: For the attack month
* 'Day': For the attack Day
* 'Country’:Country(name) face the attack by terrorist.
* 'state': state(name) faced the attack by the terrorist.
* 'Region': Region(name) where the terror attack happened.
* 'city': city faced the terror attack.
* 'Success’: Terror attack status.
* 'latitude': Terror attack location latitude.
* 'longitude': Terror attack location longitude.
* 'AttackType': Types of terror attack.
* 'Killed': No of people killed by terrorist.
* 'Wounded': No of people wounded by terrorist.
* 'Target': Terrorist target.
* 'Group': Terror group name
* 'Target_type': Tarket type either Government or privet etc.
* 'Nationality': People nationality who killed and wounded by terrorist attack.
* 'Weapon_type': Types of weapons used during attack 
* 'Hostages/Kidnapping': No people hostages or kidnapped.
--------------------------------------------------------------------------------------------

### Overview:
We have done EDA (Exploratory data Analysis)

Technology and tools wise this project covers,

1.Python

2.Numpy and Pandas for data cleaning

3.Matplotlib

5.Data visualization

6.Google Colab Notebook

---------------------------------------------------------------------------------------
### Technologies Used:
https://www.google.com/imgres?imgurl=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F3%2F31%2FNumPy_logo_2020.svg&imgrefurl=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FNumPy&tbnid=ghAGPef9vrDcYM&vet=12ahUKEwiIn-yS4MzzAhWHnEsFHQWTCasQMygAegUIARDJAQ..i&docid=mbaIme1UnDJhSM&w=800&h=360&q=numpy&ved=2ahUKEwiIn-yS4MzzAhWHnEsFHQWTCasQMygAegUIARDJAQ

data:image/png;base64,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
