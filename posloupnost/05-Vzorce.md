# Cheat Sheet

| **Typ vzorce**                     | **Aritmetická posloupnost**                               | **Geometrická posloupnost**                             | **Harmonická posloupnost**                              |
|------------------------------------|-----------------------------------------------------------|---------------------------------------------------------|---------------------------------------------------------|
| **Obecný vzorec pro $n$-tý člen**  | $a_n = a_1 + (n-1) \cdot d$                              | $a_n = a_1 \cdot q^{n-1}$                              | $a_n = \frac{1}{n}$                                      |
| **Výpočet $n$-tého členu (na základě předchozího)** | $a_n = a_{n-1} + d$                                     | $a_n = a_{n-1} \cdot q$                                | $a_n = \frac{1}{n}$                                      |
| **Rekurentní vztah**               | $a_{n+1} = a_n + d$                                      | $a_{n+1} = a_n \cdot q$                                | Není potřeba – členy jsou přímo závislé na pořadovém čísle |
| **Součet prvních $n$ členů**       | $S_n = \frac{n}{2} \cdot (a_1 + a_n)$                    | $S_n = \frac{a_1(1 - q^n)}{1 - q}$  (pro $q \neq 1$)    | $S_n = \sum_{k=1}^{n} \frac{1}{k}$                     |
|                                    | nebo $S_n = \frac{n}{2} \cdot (2a_1 + (n-1) d)$         | $S_n = n \cdot a_1$  (pro $q = 1$)                      | Diverguje (neexistuje konečný součet pro všechny členy)  |
| **Výpočet $s$-tého členu (pokud je znám $r$-tý člen)** | $a_s = a_r + (s-r) \cdot d$                              | $a_s = a_r \cdot q^{s-r}$                              | $a_s = \frac{1}{s}$                                      |
