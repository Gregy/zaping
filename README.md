 Options:

   zaping.sh server [mode=avg] [count=5] [interval=0.2]

       server      Server to ping, either ip or dns
       option      operational mode (default avg)
                     "loss" to get the percentage of lost pings in a range of pings
                     "min" to get the minimum time in a range of pings
                     "avg" to get the average time
                     "max" to get the max time
       count       How many times to ping when doing a range of pings
       interval    Interval between pings during a range.  Must be
               greater than 0.2 (only root can go less than 0.2)

   Returns positive floating point number on success and -1 on failure
