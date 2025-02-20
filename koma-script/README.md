### Theorems (dutch) using TColorBox
```tex
\begin{THEOREM}{TITLE}{REFNAME}
    TEXT
\end{THEOREM}
```
Note: `TITLE` and `REFNAME` are optional.

#### Theorem name and refname-prefix
- definitie: `def`
- axioma: `ax`
- eigenschap: `prop`
- lemma: `lem`
- stelling: `stel`
- bewering: `bwr`
- propositie: `prop`
- gevolg: `gev`
- bewijs: `bew`
- voorbeeld: `vb`
- toepassing: `tp`
- oefening: `oef`

Example:
```tex
\begin{stelling}{Pythagoras}{pyt}
    In een rechthoekige driehoek is de som van de kwadraten van de rechthoekszijden gelijk aan het kwadraat van de schuine zijde.
\end{stelling}
Zoals gezien in \cref{stel:pyt} ...
```

### Boxes
```tex
\begin{THEOREM}{TITLE}
    TEXT
\end{THEOREM}
```
Note: `TITLE` is optional.

#### Box name
- oplossing
- antwoord
- uitwerking
- opmerking
- hint
- herinner
- intermezzo
- notatie
- conventie
- vraag
- interpretatie

Example:
```tex
\begin{notatie}{}
    We noteren \Re als het reële deel van een complex getal.
\end{notatie}
```
