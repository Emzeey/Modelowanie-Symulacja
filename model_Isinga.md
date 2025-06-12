# Przykład 1
H = -2

### Stan początkowy:
|D|D|U|U|
|-|-|-|-|
|U|U|D|U|
|D|U|U|D|
|U|D|D|D|

U: 8  
D: 8  
$\sum{S_j} = 8-8=0$  
$E_0 = -H * \sum{S_j} = -2 * 0 = 0$  

### Iteracja 1
|D|U|D|U|
|-|-|-|-|
|D|D|U|D|
|U|U|D|U|
|D|U|D|D|

U: 7  
D: 9  
$\sum{S_j} = 7-9=-2$  
$E_1 = -2 * -2 = 4$  

### Iteracja 2
|U|D|U|D|
|-|-|-|-|
|D|U|D|U|
|D|U|U|D|
|U|D|D|U|

U: 8  
D: 8  
$\sum{S_j} = 8-8=0$  
$E_1 = -2 * 0 = 0$  
