NOTE:
-----
I could not upload penna and votes table to Github because the files were greater than 25 MB. 
However, I am willing to email the files if you are interested. Just contact me through my email 
and I will send the files by email. Sorry for the inconvenience!


Background Information:
-----------------------

Penna is a table consisting of information about 2020 election votes in Philadelphia.

The table consists of 217 timestamps (from 2020-11-03 19:39:48 to 2020-11-11 21:50:46) from 
3,110 precincts. For each timestamp, the tuple shows the amount of votes (totalvotes) until 
that timestamp. Each tuple also shows how many votes went to Trump and how many votes went to
Biden. 


2 Adjustments made to penna:
----------------------------

1. I deleted tuples with an empty value for geo.

2. For precinct LOWER PAXTON TWP--23RD PRECINCT 
at Timestamp 2020-11-06 22:01:06 to 2020-11-11 21:50:46, 
I changed the Trump value from 636 to 637 because it originally violated constraint c in part 3
and votes should not decrease.


FILES:
------

BidenGraph file and TrumpGraph file are for PlotCandidate.

Penna file is the adjusted penna table.

votes file and precincts file are the tables for decomposed Penna.
