# Fastread-DMM-Py
Read DMMs the fastest way possible over GPIB with python

Results with an Agilent 82357B GPIB adapter on a RasPi 3B: <br>
<br>
Throughput: <br>
mean: 2.577ms <br>
median: 2.584ms <br>
stdev: 0.109ms <br>
min: 2.210ms <br>
max: 7.976ms <br>
<br>
1NPLC (50Hz and more than 6 million datapoints): <br>
mean: 21.808ms <br>
stdev: 0.058ms <br>
min: 10.848ms <br>
max: 33.124ms <br>
<br>
Not sure why, but 1NPLC has a significantly lower delay than throughput test (1.8ms vs 2.6ms).
