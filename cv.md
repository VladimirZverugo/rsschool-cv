## **Vladimir Zverugo** 

- Zverugo.vladimir@gmail.com
- +375447809446
- telegram: @rafdaddy


My main goal is to get a job in frontend that is why i'm attending RSSchool. Four years in the university gave me enough patiency to selfeducate and some soft skills to find any informtion I need:)


|   Skills      |    Level       |
|:-------------:|:---------------|
| C#            | Able to create a simple app, unit tests|
| C++           | Novice, basic OOP           |
| JS (vanilla)  | In pocess of education:) |
| Git           | In process of education              |
| Python        | Novice in ML and math, able to develop a simple parser (shown below)|
| Matlab        | Able to modulate complex physical processes |
| Adobe PS,AI   | Skilled, able to draw logos,patterns, etc.|
| SAP/ABAP dev  | Passed "LeverX LevelUP" course with a certificate|
| CMS           | Common admin skills in wordpress, magento, EVO |
 

Code samples:

Python parser: shows COvid19 statistics on random country
```Python
{

import requests
import json
import random


def handler(event, context):
    response = requests.get("https://data.covid19info.live/processeddata.js")
    file = json.loads(response.text)

    if response.status_code==200:
        regions = file['regions']
        country = regions[random.randint(0,len(regions)-1)]
        print(f"Country: {country[0]['en_name']} \nConfirmed COvid: {country[7][-1]['c']} \nRecovered: {country[7][-1]['r']}")
    else:
        print("Error")
}
```

#

Job experience  might be here

#

### Education
Bachelory degree - BSU, faculty of radiophysics and computer technolories, radiophysics (2016-2020)

Masters degree - BSU, faculty of radiophysics and computer technolories, computer security (2020-2022)

SAP/ABAP - LeverX International course certificate

English -  FCE Certificate of Cambridge English Assessement 


| Language      | Level           | certificates  |
|:------------- |:---------------:| -------------:|
| English       |        B2       |FCE (Cambridge)|
| Russian       |      Native     |               |
