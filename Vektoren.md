# Vektoren
``` 
vektor <- c(1,2,3)
```
Alle Elemente eines Vektors müssen den gleichen Datentyp haben, falls nicht, werden sie entsprechend gecastet.
## Operationen
+ / - / * / /    
- Die Operationen laufen nicht inplace ab
- ```*``` ist die Multiplikation der Elemente, nicht das Kreuzprodukt
## Funktionen
- sum(v1, v2, v3) gibt Summe zurück
- max(v), min(v)
- sd(v) ist die Standardabweichung der Elemente eines Vektors
- var(v) ist die Varianz der Elemente eines Vektors
- prod(v) gibt Produkt der Elemente
## Indizierung
``` v[1] ``` gibt das erste Element eines Vektor zurück
## Slicing
```v[c(1,2)]``` liefert das erste und das zweite Element(inklusive) zurück
```v[3:6]``` liefert das dritte bis zum sechsten Element(inklusive) zurück
## Namenzuweisung
In R ist es möglich, den Elementen eines Vektors Namen zuzuweisen:
```
v <- c(1,2,3)
names(v) <- c("a","b","c")
```
Jetzt ist ein Zugriff auf die Vektorelemente über den Namen möglich:
```
v["a"]
v[c("a","b")]
```
## Bedingungen
```v[v>2]``` gibt nur die Werte größer 2 des Vektors zurück
