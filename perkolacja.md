# Przykład 1
Grid size: N = 6  
![image](https://github.com/user-attachments/assets/dad0a9dc-d2db-44c6-a3ab-832d62e277a9)

1. (1,1)  
2. (3,1), (2,2), (3,2), (2,3), (2,4)  
3. (5,1), (5,2), (6,2)  
4. (4,4)  
5. (6,4), (5,5), (6,5)  
6. (1,6)  
7. (3,6)


### Tabelka 1
|Nr|M(i)|Perkolujacy|Środek geometryczny r(i)|Średni promień R(i)|Rozciągłość l(i)|
|---|---|---|---|---|---|
|1|1|Nie|(1,1)|$\sqrt{\frac{(1-1)^2+(1-1)^2}{1}} = 0$|0|
|2|5|Nie|$(\frac{3+2+3+2+2}{5},\frac{1+2+2+3+4}{5}) = (2.4,2.4)$|$\sqrt{\frac{(2.4-3)^2+(2.4-1)^2+(2.4-2)^2+(2.4-2)^2+(2.4-3)^2+(2.4-2)^2+(2.4-2)^2+(2.4-3)^2+(2.4-2)^2+(2.4-4)^2}{5}} = 1.131$|$\sqrt{(3-2)^2+(1-4)^2} = \sqrt{10}$|
|3|3|Nie|$(\frac{5+5+6}{3},\frac{1+2+2}{3}) = (5.333,1.666)$|$\sqrt{\frac{(5.333-5)^2+(1.666-1)^2+(5.333-5)^2+(1.666-2)^2+(5.333-6)^2+(1.666-2)^2}{3}} = 0.516$|$\sqrt{(5-6)^2+(1-2)^2} = \sqrt{2}$|
|4|1|Nie|(4,4)|$\sqrt{\frac{(4-4)^2+(4-4)^2}{1}} = 0$|0|
|5|3|Nie|$(\frac{6+5+6}{3},\frac{4+5+5}{3}) = (5.666,4.666)$|$\sqrt{\frac{(5.666-6)^2+(4.666-4)^2+(5.666-5)^2+(4.666-5)^2+(5.666-6)^2+(4.666-5)^2}{3}} = 0.516$|$\sqrt{(6-5)^2+(4-5)^2} = \sqrt{2}$|
|6|1|Nie|(1,6)|$\sqrt{\frac{(1-1)^2+(6-6)^2}{1}} = 0$|0|
|7|1|Nie|(3,6)|$\sqrt{\frac{(3-3)^2+(6-6)^2}{1}} = 0$|0|

### Tabelka 2
|Masa|Agregaty|Liczba|Masa sumaryczna|$n_s(p)$|
|-|-|-|-|-|
|1|{1,4,6,7}|4|$4*1 = 4$|$\frac{4}{N^2} = 0.111$|
|3|{3,5}|2|$2*3 = 6$|$\frac{2}{N^2} = 0.0555$|
|5|{2}|1|$1*5 = 5$|$\frac{1}{N^2} = 0.02777$|

### Przeciętna wielkość nieperkolujących agregatów $l_{av}$
$l_{av} = \frac{\sqrt{10}+\sqrt{2}+\sqrt{2}}{10} = 0.599$

### Średnia masa nieperkolującego agregatu $S_{av}$ (podatność perkolacji)
$S_av$ = masa wszystkich nieperkolujących agregatów / liczba nieperkolujących agregatów

Agregaty o masie 1: 4 sztuki -> 4 * 1 = 4
Agregaty o masie 3: 2 sztuki -> 2 * 3 = 6
Agregaty o masie 5: 1 sztuka -> 1 * 5 = 5

Suma mas: 4 + 6 + 5 = 15
Liczba agregatów: 4 + 2 + 1 = 7

Średnia masa nieperkolującego agregatu: $S_av$ = 15 / 7 ≈ 2
