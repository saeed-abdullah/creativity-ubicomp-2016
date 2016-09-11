# Supplementary materials for _Shining (Blue) Light on Creative Ability_

[![DOI] (https://img.shields.io/badge/DOI-10.1145%2F2971648.2971751-blue.svg)](https://dx.doi.org/10.1145/2971648.2971751)

This repository contains supplementary materials for _Shining (Blue) Light on Creative Ability_. UbiComp, 2016. DOI: [10.1145/2971648.2971751](https://dx.doi.org/10.1145/2971648.2971751)

## Convergent Thinking Test ##

This repository contains a machine-friendly version of compound remote
association test (CRA) developed by
[Bowden and Jung-Beeman](https://link.springer.com/article/10.3758/BF03195543).

Remote association tests are widely used for assessing
[convergent thinking](https://en.wikipedia.org/wiki/Convergent_thinking).
The test requires coming up with a word that combines or connects with three
given words. For example, given the words "_cream / skate / water_", the
correct answer is _ice_. Note that finding correct answer requires recalling
and combining semantically distant information — a process associated with
convergent thinking.

To facilitate future research on creativity, Bowden et al. published a list of
remote association tests along with normative data that gives a sense of
complexity of each task (e.g., percentage of people being able to come up with
the correct answer in a given time period). The `cra.csv` contains the data from
the table in page 5 in their paper.

### Column description ###

The columns in `cra.csv` reflects the columns of the table in the paper:

* comparison_0: First term of the test (e.g., _cream_ in the above example).
* comparison_1: Second term of the test.
* comparison_2: Third term of the test.
* solution: The correct answer of the test (e.g., _ice_ in the above example).
* two_sec: Percentage of the population (n = 89) being able to solve the test
within 2 seconds.
* seven_sec_p: Percentage of the population (n = 85) being able to solve the test
within 7 seconds.
    * seven_sec_mean: The mean time for coming up with correct answer for this
    population
    * seven_sec_sd: Associated standard deviation
* fifteen_sec_p: Percentage of the population (n = 76) being able to solve the test
within 15 seconds.
    * fifteen_sec_mean: The mean time for coming up with correct answer for this
    population
    * fifteen_sec_sd: Associated standard deviation
* thirty_sec_p: Percentage of the population (n = 39) being able to solve the test
within 15 seconds.
    * thirty_sec_mean: The mean time for coming up with correct answer for this
    population
    * thirty_sec_sd: Associated standard deviation
