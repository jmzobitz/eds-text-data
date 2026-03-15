# Environmental Data Science Book Datasets published by Routledge Chapman & Hall/CRC books

This is the updated, but still work-in-progress, version of the book we are writing.

- `unde_nee.csv`: half-hourly net ecosystem exchange data from the University of Notre Dame Research Center
  - Downloadable as CSV
  - Variables:
      - `time`: POSIXct date (half hourly increments)
      - `year`: 4 digit year
      - `month`: calendar month (1-12)
      - `day_of_year`: day (out of 365 or 366)
      - `nee`: Net Ecosystem Carbon Exchange (umol m^-2^ s^-1^)
  - Found in [Iteration without Tears](https://jmzobitz.github.io/eds-text/14_iteration.html) and [Approaches to Visualizing Data](https://jmzobitz.github.io/eds-text/15_viz.html)

- `lwc_2023.csv`: Daily reported weatherstation data from Lawrence, Kansas. Processed from the [Iowa Environmental Mesonet](https://mesonet.agron.iastate.edu/request/daily.phtml?network=KS_ASOS), station "LWC" 
  - Variables:
      - `station`: Weather station
      - `day`: POSIXct date (daily)
      - `max_temp_f`: Maximum temperature (F)
      - `min_temp_f`:  Minimum temperature (F)
      - `max_dewpoint_f`: Maximum dewpoint (F)
      - `min_dewpoint_f`: Minimum dewpoint (F)
      - `avg_rh`: Average relative humidity (%)
  - Found in [Wrangling and joining Data](https://jmzobitz.github.io/eds-text/13_wrangling_joining.html)
  
 - `msp_2023.csv`: Daily reported weatherstation data from Minneapolis/St. Paul, Minnesota. Processed from the [Iowa Environmental Mesonet](https://mesonet.agron.iastate.edu/request/daily.phtml?network=MN_ASOS), station "MSP" 
    - Variables:
      - `station`: Weather station
      - `day`: POSIXct date (daily)
      - `max_temp_f`: Maximum temperature (F)
      - `min_temp_f`:  Minimum temperature (F)
      - `max_dewpoint_f`: Maximum dewpoint (F)
      - `min_dewpoint_f`: Minimum dewpoint (F)
      - `avg_rh`: Average relative humidity (%)
    - Found in:
      - [Core languages for environmental data science](https://jmzobitz.github.io/eds-text/03_env_for_data_science.html)
      - [Wrangling and joining Data](https://jmzobitz.github.io/eds-text/13_wrangling_joining.html)