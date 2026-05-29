# Renal Impairment PBPK Model
**CKD Staging · GFR Scaling · Dose Adjustment · OSP PK-Sim Exercise**

PBPK model for gabapentin across all CKD stages (G1 Normal through G5 ESRD),
implemented in Python and R. Reproduces the OSP PK-Sim v12 Renal Impairment
exercise and validates FDA dose adjustment recommendations.

## Key Finding
Gabapentin AUC increases ~15x in ESRD vs normal kidney function,
requiring dose reduction from 300mg TID to 150mg QD.

## Tools
Python · numpy · scipy · matplotlib · plotly  
R · deSolve · ggplot2 · plotly

## Training Reference
OSP PK-Sim Course v12 — Renal Impairment Exercise
