# LuhnCalulator_LabView
This repo contains of a simple Luhn Calculator for Swedish "Person nummer" (Personal ID number in Sweden).
Format is YYMMDD-NNGL
- Y = Year
- M = Month
- D = Day
- N = Randomized number
- G = Gender code (Even / Odd)
- L = Luhn number

## LuhnCalculator.lvproj
Project file for the application

## MainWindow.vi
Simple Labview application that will let you calculate the Luhn number of a swedish "Personnummer".
It will also indicate if the calculation is wrong.

### To be done.
- Limitation of months to only allow 01 - 12.
- Limitation of days to only allow 01 - 31.
- Limitation of days to follow months.
- Add Gender to calculation
