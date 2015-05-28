```
Empirical Estimation Models
```
```
1. The structure of estimation models

1.1 Estimation models

E = A + B X (e to the lower power of v)^C
A,B,C => Empirical derived constants
E => Effort
(e to the lower power of v) => Estimation variable

1.1.1 LOC-oriented estimation model
LOC => Lines Of Code
-- Four models
(a) Walston model
E = 5.2 X (KLOC)^0.91
(b) Baiyson Baisili model
E = 5.5 + 0.73 X (KLOC)^1.16
(c) Boehm simple model
E = 3.2 X (KLOC)^1.05
(d) Doty model
E = 5.288 X (KLOC)^1.047

1.1.2 FP-oriented estimation model
FP => Function Point
(a) Albrecht and Gaffney model
E = -91.4 + 0.355 FP
(b) Kermerer model
E = -37 + 0.96 FP
(c) Small project regression model
E = -12.88 + 0.405 FP
```
```
2. The COCOMO II model

Hierachy of Estimation models
(i) Application composition model
(ii) Early design stage model
(iii) Post-architecture stage model

Estimation of re-use:
NOP = object points X [(100 - re-use%)/100]
NOP => New Object points

Estimation of productivity rate:
PROD = NOP / (person - month)

Estimation of efforts:
Estimated effort = NOP / PROD
```
```
3. The software equation
4. Estimation for Object Oriented Projects
5. Specialized Estimation Techniques
5.1 Estimation for Agile Development
5.2 Estimation for WebApp Projects
6. Make/Buy Decision
6.1 Creating a decision tree
6.2 Outsourcing
7. Summary

References:
[3] Roger S.Pressman - Software Engineering : A Practitioner's approach, 7th edition.
```
