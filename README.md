# lat-long-check
A Python Script to check whether the given latitude and longitude belongs to a given city or country. Uses `Google Maps API`.

# Usage 

Inside the `check_json.py` file, put your Google Maps API key at `YOUR_API_KEY`. Now run the file by creating an object with `self`, your required `location name`, `latitude` and `longitude` as inputs. 

# Additional info

Checks have been put for code testing using PyUnit library for the following cities/country with both positive and negative cases:
 1. Bangalore
 2. New Delhi
 3. Pune
 4. Hyderabad
 5. India
 
The pylint test results were:

`check_json.py` : 8.18/10


`basic_test.py` : 9.62/10

Any corrections/pull requests are welcome.

 
