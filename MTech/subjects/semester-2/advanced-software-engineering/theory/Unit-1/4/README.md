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

E = [(LOC X B^0.333)/P^3] X [t^4]
E => Effort
B => Special skills factor
P => Productivity parameter
t => Project duration
```
```
4. Estimation for Object Oriented Projects

Approaches:
(a) Develop estimation using effort decomposition and FP analysis.
(b) Develop use cases using requirement model for determining the count.
(c) Determine number of key classes (known as analysis classes) using requirement model.
(d) Develop a multiplier for categorizing the type of interface in applications.
(e) Multiply the number of classes by the average number of work units per class.
(f) Cross check by multiplying the average number of work units per use case.
```
```
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
