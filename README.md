# Fastread-DMM-Py
Read DMMs the fastest way possible over GPIB with python

Results with an Agilent 82357B GPIB adapter on a RasPi 3B:


Throughput:

mean: 2.577ms

median: 2.584ms

stdev: 0.109ms

min: 2.210ms
max: 7.976ms


1NPLC (50Hz and more than 6 million datapoints):

mean: 21.808ms

stdev: 0.058ms

min: 10.848ms

max: 33.124ms


Not sure why, but 1NPLC has a significantly lower delay than throughput test (1.8ms vs 2.6ms).
