# TOP-NIA-BS

Adapted instances for the TOP with nonidentical agents and balanced score. 

The format of the instances is the following:
```
n 21 -> number of customers + depots (2)
m 2 -> number of vehicles
tmax 16.0 -> travel length limit
  4.6  7.1    0    1    1 -> departure 
  5.7 11.4   20    1    1 -> customer with index 1 in format (x, y, score, compatibility with the first vehicle, compatibility with the second vehicle)
  4.4 12.3   20    0    1
  2.8 14.3   30    1    1
  3.2 10.3   15    1    0
  3.5  9.8   15    1    0
  4.4  8.4   10    1    1
  7.8   11   20    1    0
  8.8  9.8   20    1    1
  7.7  8.2   20    1    1
  6.3  7.9   15    1    1
  5.4  8.2   10    0    1
  5.8  6.8   10    1    1
  6.7  5.8   25    0    1
 13.8 13.1   40    1    0
 14.1 14.2   40    1    0
 11.2 13.6   30    1    0
  9.7 16.4   30    1    1
  9.5 18.8   50    1    0
  4.7 16.8   30    0    1
    5  5.6    0    1    1 -> arrival

** Note: compabilities of the departure and arrival node are unused because every route MUST start in the departure node and finish at the arrival node
```
