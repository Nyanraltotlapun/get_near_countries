# get_near_countries
Simple CLI utility to query countries with direct bounders to given one.

It accepts coutry code for search and otput list of bordering countries codes.
Country codes is two-character country codes based on ISO 3166.

Program allows for recursive search.


# Pre requirements
 Python

# Usage
```
get_near_countries.py [-h] -c COUNTRY [-r RECURSION]

options:
  -h, --help            show help message and exit
  -c, --country COUNTRY
                        Country for which you want to do the search.
  -r, --recursion RECURSION
                        Recursion depth, 1 means search to only direct boarder, 2 means to search also for countries found on step 1, etc.

```



Copyright (C) 2025  Kirill Shakirov
