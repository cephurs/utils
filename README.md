# utils
Different DFIR and CTI utilities

## ACH_template-v0.4.xlsx
It's an excel sheet that implements the scoring and weighting methodology of the Analysis of Competing Hypotheses. You can read more about it and a practical use case (WannaCry attribution) below:
- https://isc.sans.edu/forums/diary/Analysis+of+Competing+Hypotheses+ACH+part+1/22460/
- https://isc.sans.edu/forums/diary/Analysis+of+Competing+Hypotheses+WCry+and+Lazarus+ACH+part+2/22470/

## Epochalypse
There is the standard, official Epoch time (the Unix/POSIX one, seconds elapsed since 1 Jan 1970), and there are "other epoch" type of time (because, why not?). Epochalypse is a python script that receives a generic timestamp as input and converts it in several known common formats. Sample output and currently supported formats below:
```
$ python3 epochalypse.py -e 547120509.243697

##########################################################
#                                                        #
#    Epochalypse - Epoch timestamp converter utility     #
#            by Pasquale Stirparo, @pstirparo            #
#                                                        #
##########################################################

Epoch Time input to be converted: 547120509.243697
Unix:   1987-05-04 09:55:09.243697 UTC
COCOA:  2018-05-04 09:55:09.243697 UTC
FAT:    1997-05-03 09:55:09.243697 UTC
HFS+:   1921-05-03 09:55:09.243697 UTC
WebKit: 1601-01-01 00:09:07.120510 UTC
NTFS:   1601-01-01 00:00:54.712051 UTC
APFS:   1970-01-01 00:00:00.547121 UTC
```
