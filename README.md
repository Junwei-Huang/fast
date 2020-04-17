# speedtest-fast
**Internet speed test | fast.com**  

Test your download and upload speed using fast.com  

# Usage
```
[root@test ~]# docker run -it --rm mratrend/speedtest-fast:latest fast 


     610 Kbps ↓


```
or
```
[root@test ~]# docker run -it --rm mratrend/speedtest-fast:latest fast 


     610 Kbps ↓


```
# fast CMD params
```
  Usage
    $ fast
    $ fast > file

  Options
    --upload, -u  Measure upload speed in addition to download speed

  Examples
    $ fast --upload > file && cat file
    17 Mbps
    4.4 Mbps
```
