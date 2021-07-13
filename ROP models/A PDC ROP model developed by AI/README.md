# Developing PDC ROP model using Artificial Inteligence

A PDC ROP model was developed using symbolic regression algorithm. 

#### Symbolic Regression Algorithm




#### Python library

The PySR library is used in this study. check out the the PySR website [here](https://pysr.readthedocs.io/en/latest/docs/getting-started/).


#### Repository structure

```
└───A PDC ROP model developed by AI
    ├───Archive
    └───Data
```

#### Bits 


PDC bits manufactured by National Oil Varco - NOV (left) and Ulterra (right) are seen at the following image.
<p align="left">
  <img  width="450" src="Images/NOV_bits.PNG" >
  <img  width="450" src="Images/Ulterra_bits.PNG" >
</p>

#### Data

The four row of data used in this syduy are seen at the following table.

|   year | name       |     WOB |   ROP data |   Db |   RPM |   UCS |   NOC |   BR |   SR |   Dc |   NOB |
|--------|------------|---------|------------|------|-------|-------|-------|------|------|------|-------|
|   2019 | SWG        | 2543.8  |    6.2     | 3.75 |    80 | 28000 |    11 |   25 |    1 | 0.51 |     4 |
|   2019 | SWG        | 3048.9  |   11.9     | 3.75 |    80 | 28000 |    11 |   25 |    1 | 0.51 |     4 |
|   2019 | SWG        | 3538.7  |   19.5     | 3.75 |    80 | 28000 |    11 |   25 |    1 | 0.51 |     4 |
|   2019 | SWG        | 4066.2  |   28.6     | 3.75 |    80 | 28000 |    11 |   25 |    1 | 0.51 |     4 |

#### Data Dimensions

WOB is in lbf
ROP data is in ft/hr
Db is in inch
RPM is in rpm
UCS is in psi
NOC is dimensionless
BR is dimensionless
Dc is in inch
NOB is dimensionless


