# A Demand-Driven Pattern-Based Timetabling Strategy for a Short-Turning Metro Line - Instances

This repository contains the data of the instances used for the computational experiments of the paper *A Demand-Driven Pattern-Based Timetabling Strategy for a Short-Turning Metro Line*.

All instances report the following parameters:

`n` number of trains operating on the line
`stations` number of stations
`disc` discretization coefficient (number of time-steps per unit time)
`root` root station
`max_h` maximum train headway
`min_h` minimum train headway
`max_w` maximum train waiting time

`travel` vector of the travel distances of each station from station 1
`permitted` binary vector indicating legal short-turning stations 

`D` demand matrix
