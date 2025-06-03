# Julie Piot - Weekly Logs

### Week 1 ###

- [x] New student orientations
- [x] Download and familiarize myself with data
  - Plotted the basic timeseries for all variables
  - Looked into variables (eg. temperature in celsius!)
- [x] Background reading on eddy covariance
  - Notes in sticky on laptop; refer back to that

### Week 2 ###

- [x] First analysis of 10 hz wind data stationarity
  - Created 30-min, 15-min, 5-min, and 1-min intervals to compare trends
  - ADF test on the 30-min intervals: came back as stationary over all intervals
  - Created a dataframe of means and stds of each interval within 30-min (same for 15, 5, and 1)
    - Plotted the means/stds of the intervals across time (one for each var: t, uwind, wwind, vwind)
  - Created a dataframe of differences in means and stds for consecutive interval chunks
    (seperately for 30, 15, 5, 1)
    - Plotted the differences in means/stds of the intervals across time (one for each var: t, uwind, wwind, vwind)
- [ ] Play around with definitions of stationarity; what is my definition?
  - The ADF test originally reported that all 30-minute intervals were stationary, why?
    Some segments must be non-stationary, find a test that is more critical.
- [ ] Remove outliers; the data was unaccurate because another instrument influenced it
  - 
- [ ] Attend LICOR Eddy Covariance Workshop; even more in-depth learning
- [ ] Look into the noise distribution of 'correct' data
- [ ] Compare the 'correct' data noise distribution to the 'incorrect' data
- [ ] Calculate flux using the different measures of stationarity
- [ ] Understand better; is there an efficient way to not assume 30-minute session
      but instead make a software to see how long a time series is stationary and then
      calculate flux for a flexible time period rather than a 30-minute standard?






