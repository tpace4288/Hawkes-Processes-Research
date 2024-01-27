# Hawkes-Processes-Research
This repository contains various Jupyter notebooks used to simulate Hawkes processes. These simulations were coded in Julia and used in research pertaining to my PhD thesis.

HawkesHT details how one might simulate a 'heavy-tailed' Hawkes process and HawkesNU details how one might simulate nearly unstable Hawkes processes. In general, the idea is to simulate a number of first generation parents according to a Poisson distribution and then create offspring according to a recursive structure with tails that are either 'heavy' or not. This sort of process was initially used to describe the aftershocks of earthquakes and more modernly, how a tweet becomes viral after retweets.
