Punctul b)

Efectul lui Y asupra posteriorului pentru n

Cand Y este mic (ex. 0), este compatibil cu valori mici ale lui n, dar si cu valori moderate, deoarece chiar si un n mare poate produce Y=0 cu probabilitate (1-theta)^n.
Posteriorul va fi larg si impins spre valori mai mici.

Cand Y este mediu (ex. 5), posteriorul pentru n se concentreaza in jurul valorilor unde n * theta aproximativ egal cu Y.
Posteriorul devine mai informat (dispersie mai mica).

Cand Y este mare (ex. 10), posteriorul impinge n spre valori mari deoarece doar un n mare poate produce un numar mare de succese Y.
Posteriorul devine concentrat pe valori ridicate ale lui n.



Efectul lui theta asupra posteriorului pentru n

Theta mic (ex. 0.2):
Succesul este rar. Deci, pentru a obtine un Y dat, modelul tinde sa favorizeze valori mai mari ale lui n.
Exemplu: pentru Y=5, daca p=0.2, avem nevoie de aproximativ n = 25.

Theta mare (ex. 0.5):
Succesul este mai probabil. Pentru acelasi Y, sunt necesare valori mai mici ale lui n.
Exemplu: pentru Y=5, daca p=0.5, n aprox 10.


Punctul d)

Posterior pentru n | Y

Reprezinta distributia credintei asupra valorii necunoscute n dupa observarea datelor Y.
Este o distributie asupra parametrului n.
Reflecta incertitudinea asupra n data de observatiile deja vazute.


Predictive posterior pentru Y | Y*

Reprezinta distributia pentru un viitor rezultat Y* folosind:
incertitudinea asupra lui n (din posterior),
modelul binomial Y* ~ Binomial(n, theta)

Este o distributie asupra datelor viitoare, nu asupra parametrilor.
