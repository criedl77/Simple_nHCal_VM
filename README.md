First run ePIC_Analysis.C, then ePIC_Plotting.C

## ePIC_Analysis.C

CR 2024-08-14/20

Run this macro, from the Linux / Terminal command line, as

root -l -q ePIC_Analysis.C

The only condition is that there is a subdirectory called "data" that contains the input MC file (from SDCC), which can be downloaded here:
https://uofi.box.com/s/mjyewaidimk5ka7oaxgi37ltgbkz3nf4

The name of this input MC file (variable "strang") is hardcoded in this macro and must match with the file name

CR 2024-11-08

It is also possible to stream a runlist directly on SDCC. I can provide instructions

## ePIC_Plotting.C

Run this macro, from the Linux / Terminal command line, as

root -l -q ePIC_Plotting.C

The only condition is that previously ran ePIC_Analysis.C  with the identical "strang" as hardcoded in this macro

Strang must match the string in a file starting with out*, in this directory
