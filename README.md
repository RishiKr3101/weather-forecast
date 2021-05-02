#  weatherfrcst 



The pip package provides weather forecasting information based on location or address. Using address, the weather_forecast provides location specific forecast. Currently only one function is included i.e forecast which returns a dictionary.



### Install :computer:
```
pip install weatherfrcst==0.0.1
```

### Code Usage :video_game:
```
import weatherfrcst as wf
d = wf.forecast(place = "<place>" , time= None , date=None , forecast)
print(d) // d is a dictionary
```





```
