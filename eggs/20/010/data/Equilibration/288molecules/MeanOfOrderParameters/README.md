# Mean value of the order parameters

We wish to calculate the mean values of the order parameters in the liquid and in ice Ih.
The order parameters are the following:

* The average of the kernels with ice Ih reference environments
* The number of molecules with environments compatible with those of ice Ih
* The average of the kernels with ice Ic reference environments
* The number of molecules with environments compatible with those of ice Ic
* Q6

The COLVAR files can be created by running PLUMED with the commands:

```
plumed driver --mf_dcd ../IceIh/dump.dcd
plumed driver --mf_dcd ../Liquid/dump.dcd
```

Afterwards the script ```script.py``` generates the output in the table below.

|               | Avg Kernel Ih | # molec Ih    | Avg Kernel Ic | # molec Ic    | Q6            |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Liquid        | 0.291         | 2.28          | 0.265         | 1.38          | 0.039         |
| Ice Ih        | 0.813         | 285.98        | 0.592         | 219.01        | 0.413         |

