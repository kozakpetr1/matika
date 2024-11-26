# Aritmetická posloupnost

**Aritmetická posloupnost** je posloupnost, ve které je rozdíl mezi dvěma po sobě jdoucími členy konstantní. Tento rozdíl se nazývá **diference** a značí se $d$.

Každý člen posloupnosti lze vyjádřit jako:  
$$
a_n = a_1 + (n-1)d
$$  
kde:  
- $a_n$ je $n$-tý člen posloupnosti,  
- $a_1$ je první člen posloupnosti,  
- $d$ je diference,  
- $n$ je pořadové číslo členu.

---

## Rekurentní vyjádření

Aritmetická posloupnost lze definovat rekurentně:  
$$
a_{n+1} = a_n + d
$$  
kde $a_n$ je aktuální člen a $a_{n+1}$ je následující člen posloupnosti.

---

## Příkladová definice

Pro $a_1 = 3$ a $d = 5$:  
$$
a_n = 3 + (n-1) \cdot 5
$$  
Posloupnost: $3, 8, 13, 18, 23, \dots$

---

## Vlastnosti aritmetické posloupnosti

- **Růst nebo pokles**:  
  Posloupnost roste, pokud $d > 0$, a klesá, pokud $d < 0$.
  
- **Konstantní posloupnost**:  
  Pokud $d = 0$, všechny členy posloupnosti jsou stejné.

- **Součet prvních $n$ členů**:  
  Součet prvních $n$ členů aritmetické posloupnosti lze vypočítat pomocí vzorce:  
  $$
  S_n = \frac{n}{2} \cdot (a_1 + a_n)
  $$  
  nebo  
  $$
  S_n = \frac{n}{2} \cdot \big(2a_1 + (n-1)d\big).
  $$

---

## Příklady aritmetických posloupností

1. $1, 3, 5, 7, 9, \dots$  
   $a_1 = 1, \, d = 2$

2. $10, 7, 4, 1, -2, \dots$  
   $a_1 = 10, \, d = -3$

3. $5, 5, 5, 5, 5, \dots$  
   $a_1 = 5, \, d = 0$

4. $100, 110, 120, 130, 140, \dots$  
   $a_1 = 100, \, d = 10$

5. $-5, -3, -1, 1, 3, \dots$  
   $a_1 = -5, \, d = 2$

---
