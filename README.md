# da-car-need-es

Does half of the population of Spain need a car or not? 

## Conclusion

According to just population we can assume that 76.12% live in less populated areas. However we have not included characteristics (ages, number of working people etc) and the city characteristics (sparsity, public transport level, number of working people, ...). The only proxy for service level is the number of habitants. 

## Problem statemet

H0: Less than half of the population of Spain don't need a car

H1: Half or more of the population of Spain need a car

## Considerations

The only use the total amount of habitants as a proxy to service level

### Possible improvements 

* City Characteristics (sparsity, number of public transport, how does it arrive to different areas...)

* Population characteristics (Age, working or not, where are they employed, ...)

## Data 

Population from [INE](https://www.ine.es/dynt3/inebase/es/index.htm?padre=517&capsel=525)

## Set-up 

* Python version `3.10.5`, `pyenv install 3.10.5`

* Create virtualenv `pyenv virtualenv 3.10.5 venv`

* Install all the requirements `pyenv activate venv` & `pip install requirements.txt`

* Start jupyter `jupyter-lab`