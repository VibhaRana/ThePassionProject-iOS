

#  Passion Project
<hr>
This is a Passion Project of my own intrest i made using swift. 
Its a weather app, which shows weater of any place on earth. I used an API to fetch data from Open Weather. 
The sfu icons are also from Open weather source, which i choose using conditional id's.








### Condition Codes
```
switch conditionID {
        case 200...232:
            return "cloud.bolt"
        case 300...321:
            return "cloud.drizzle"
        case 500...531:
            return "cloud.rain"
        case 600...622:
            return "cloud.snow"
        case 701...781:
            return "cloud.fog"
        case 800:
            return "sun.max"
        case 801...804:
            return "cloud.bolt"
        default:
            return "cloud"
        }
```


