# My Application

slc run .

/t/lt_loopback ❯❯❯ loadtest -n 10000 -c 10 http://localhost:3000

[Mon Mar 30 2015 09:21:27 GMT+0100 (WEST)] INFO Requests: 0 (0%), requests per second: 0, mean latency: 0 ms
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Target URL:          http://localhost:3000
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Max requests:        10000
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Concurrency level:   10
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Agent:               none
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Completed requests:  10000
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Total errors:        0
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Total time:          2.3508537449999998 s
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Requests per second: 4254
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Total time:          2.3508537449999998 s
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO Percentage of the requests served within a certain time
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO   50%      1 ms
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO   90%      2 ms
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO   95%      5 ms
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO   99%      9 ms
[Mon Mar 30 2015 09:21:30 GMT+0100 (WEST)] INFO  100%      28 ms (longest request)