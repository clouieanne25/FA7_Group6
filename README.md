# Part 1: Exponential Distribution
## Time Intervals Between Students Entering a Campus Restroom

## 1. Summary

This study examines the time intervals between students entering a campus restroom. The purpose is to determine whether the waiting times between student entries can be modeled using an exponential distribution. This type of analysis can help the school understand restroom usage and improve cleaning and maintenance schedules.

A total of 31 student arrival times were recorded, producing 30 time intervals between consecutive entries.

## 2. Methodology

The data were collected by recording the arrival time of each student entering the campus restroom. No names, photographs, or identifying information were recorded.

The time intervals between consecutive student entries were calculated in minutes. The mean interval was used to estimate the exponential rate parameter:

λ = 1 / mean interval

The data were analyzed using R and R Markdown. The exponential probability density function (PDF), cumulative distribution function (CDF), and probabilities for different waiting times were also calculated.

## 3. Results

The analysis produced the following results:

- Number of observations: 30 time intervals
- Mean time interval: 1.47 minutes
- Estimated exponential rate (λ): 0.6810 students per minute
- Expected waiting time: 1.47 minutes
- Probability of another student entering within 1 minute: 49.39%
- Probability of another student entering within 2 minutes: 74.39%
- Probability of another student entering within 3 minutes: 87.00%
- Probability of another student entering within 5 minutes: 96.66%

The estimated exponential probability density function is:

f(x) = 0.6810e^(-0.6810x)

The cumulative distribution function is:

F(x) = 1 - e^(-0.6810x)

## 4. Interpretation

The results show that students generally enter the restroom at relatively short intervals during the observation period. The mean waiting time between student entries was approximately 1.47 minutes.

There was a 74.39% probability that another student would enter the restroom within 2 minutes. This suggests that the restroom may experience frequent use during the observed period.

The exponential distribution provides a reasonable model for the waiting times because the study focuses on the time between consecutive events. However, factors such as class dismissal or unusually busy periods may affect the arrival pattern and should be considered when collecting future data.

## 5. Conclusion

The study demonstrates how the exponential distribution can be used to analyze the time between student arrivals on campus. The estimated mean waiting time was 1.47 minutes, with an estimated rate of 0.6810 students per minute.

These results may help the school understand restroom usage and plan cleaning and maintenance schedules based on periods of frequent student activity.
