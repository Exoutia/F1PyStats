# F1PyStats
F1PyStats is an open-source Python3 package that provides Formula 1 data/statistics to developers.
This package obtains Formula 1 data via the [Ergast Developer API](http://ergast.com/mrd/), and returns results in a pandas DataFrame format.


# Installation
## Prerequisite
The package uses `Poetry` as the primary dependency management tool. To install `Poetry` follow their 
official documentation at [link](https://python-poetry.org/docs/)
```
// Clone the repo
$ git clone https://github.com/alec-kr/F1PyStats.git

// Install dependecies using poetry
$ cd /<path where the repository was cloned>/F1PyStats
$ poetry install --only main

// Install dependencies
$ pip install pandas requests

// Install the package
$ pip install path/to/F1PyStats/
```

# Usage
```
# Import the package
import F1PyStats as fp
```

The package currently contains four functions
| Function                    	| Description                                                         	| Returned Datatype 	|
|-----------------------------	|---------------------------------------------------------------------	|-------------------	|
| fp.driver_standings(year)      	| Returns the driver standings for a particular year                  	| Pandas DataFrame  	|
| fp.constructor_standings(year) 	| Returns the constructor standings for a specified year              	| Pandas DataFrame  	|
| fp.race_winners(year)          	| Returns the race winners for a specified year                       	| Pandas DataFrame  	|
| fp.race_table(year)           	| Returns the race schedule for a specific year 	                      | Pandas DataFrame  	|

# Contributions
- Have a feature you would like to add? Feel free to create a PR :smile:.
- Spot an issue or bug? Please let us know by creating an issue. :bug:
