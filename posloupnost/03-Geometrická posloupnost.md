# Geometrická posloupnost

**Geometrická posloupnost** je posloupnost, ve které je poměr mezi dvěma po sobě jdoucími členy konstantní. Tento poměr se nazývá **kvocient** a značí se $q$.

Každý člen posloupnosti lze vyjádřit jako:  
$$
a_n = a_1 \cdot q^{n-1}
$$  
kde:  
- $a_n$ je $n$-tý člen posloupnosti,  
- $a_1$ je první člen posloupnosti,  
- $q$ je kvocient,  
- $n$ je pořadové číslo členu.

---

## Rekurentní vyjádření

Geometrickou posloupnost lze definovat rekurentně:  
$$
a_{n+1} = a_n \cdot q
$$  
kde $a_n$ je aktuální člen a $a_{n+1}$ je následující člen posloupnosti.

---

## Příkladová definice

Pro $a_1 = 2$ a $q = 3$:  
$$
a_n = 2 \cdot 3^{n-1}
$$  
Posloupnost: $2, 6, 18, 54, 162, \dots$

---

## Vlastnosti geometrické posloupnosti

- **Růst nebo pokles**:  
  Posloupnost roste, pokud $q > 1$, a klesá, pokud $0 < q < 1$.
  
- **Konstantní posloupnost**:  
  Pokud $q = 1$, všechny členy posloupnosti jsou stejné.

- **Součet prvních $n$ členů**:  
  Součet prvních $n$ členů geometrické posloupnosti lze vypočítat pomocí vzorce:  
  Pokud $q \neq 1$:
  $$
  S_n = \frac{a_1(1 - q^n)}{1 - q}
  $$  
  Pokud $q = 1$:
  $$
  S_n = n \cdot a_1
  $$

---

## Příklady geometrických posloupností

1. $1, 2, 4, 8, 16, \dots$  
   $a_1 = 1, \, q = 2$

2. $27, 9, 3, 1, \frac{1}{3}, \dots$  
   $a_1 = 27, \, q = \frac{1}{3}$

3. $5, 10, 20, 40, 80, \dots$  
   $a_1 = 5, \, q = 2$

4. $1000, 500, 250, 125, 62.5, \dots$  
   $a_1 = 1000, \, q = \frac{1}{2}$

5. $1, \frac{1}{2}, \frac{1}{4}, \frac{1}{8}, \dots$  
   $a_1 = 1, \, q = \frac{1}{2}$

---
