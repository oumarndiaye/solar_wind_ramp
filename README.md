# RAMP starting kit on solar wind classification

[![Build Status](https://travis-ci.org/ramp-kits/solar_wind.svg?branch=master)](https://travis-ci.org/ramp-kits/solar_wind)


### M2 MOSEF Project

This RAMP setup is used for the Machine learning project at M2 MOSEF.

 - Project presentation date: February 15, 2018 9:00 - 12:00

Work can be performed in groups of two. Final code solution should be uploaded the RAMP platform,

 - Submission URL: will be available on January 25 on this page.

Project reports with detailed explanation of the approach taken should be sent to roman.yurchak@symerio.com.
Please mention the names of students in your group and the username used on the RAMP platform for your
submission.

### Introduction

_Authors: Gautier Nguyen, Joris van den Bossche, Nicolas Aunai & Balazs Kegl_

Interplanetary Coronal Mass Ejections (ICMEs) result from magnetic instabilities occurring in the Sun atmosphere, and interact with the planetary environment and may result in intense internal activity such as strong particle acceleration, so-called geomagnetic storms and geomagnetic induced currents. These effects have serious consequences regarding space and ground technologies and understanding them is part of the so-called space weather discipline.

ICMEs signatures as measured by in-situ spacecraft come as patterns in time series of the magnetic field, the particle density, bulk velocity, temperature etc. Although well visible by expert eyes, these patterns have quite variable characteristics which make naive automatization of their detection difficult.

The goal of this RAMP is to detect Interplanetary Coronal Mass Ejections (ICMEs) in the data measured by in-situ spacecraft.


#### Set up

Open a terminal and

1. install the `ramp-workflow` library (if not already done)
  ```
  $ pip install git+https://github.com/paris-saclay-cds/ramp-workflow.git
  ```
  
2. Follow the ramp-kits instructions from the [wiki](https://github.com/paris-saclay-cds/ramp-workflow/wiki/Getting-started-with-a-ramp-kit)

3. Download the data,
   
   ```
   python download_data.py
   ```
#### Local notebook

Get started on this RAMP with the [dedicated notebook](solar_wind_starting_kit.ipynb).

To test the starting-kit, run


```
ramp_test_submission --quick-test
```


#### Help
Go to the `ramp-workflow` [wiki](https://github.com/paris-saclay-cds/ramp-workflow/wiki) for more help on the [RAMP](http:www.ramp.studio) ecosystem.



