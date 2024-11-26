# Matematická posloupnost

**Matematická posloupnost** je uspořádaná množina čísel (nebo jiných objektů), kde každému prvku odpovídá jeho **pořadí**. Jednotlivé prvky posloupnosti se nazývají **členy** posloupnosti a jejich pořadí je dáno přirozenými čísly.

Posloupnost můžeme zapsat jako:

$a1,a2,a3,…,an,…a_1, a_2, a_3, \dots, a_n, \dots$

kde $a_i$ označuje $i$-tý člen posloupnosti.

---

## Typy posloupností

1. **Konečná posloupnost**  
    Posloupnost má konečný počet členů, např. $1, 2, 3, 4, 5$.
    
2. **Nekonečná posloupnost**  
    Posloupnost má nekonečný počet členů, např. $1, 2, 3, 4, \dots$
    

---

## Vlastnosti posloupností

- **Explicitní definice**  
    Každý člen je vyjádřen jako funkce svého pořadí:
    $$
    a_n = f(n)
    $$
    například $a_n = 2n$.
	    
- **Rekurentní definice**  
    Každý člen je určen na základě předchozích členů:
    $$
    a_{n+1} = g(a_n)
    $$
    například $a_{n+1} = a_n + 2$.
    

---

## Speciální druhy posloupností

1. **Aritmetická posloupnost**  
    Rozdíl mezi každými dvěma po sobě jdoucími členy je konstantní.  
    Například: $2, 5, 8, 11, \dots$  
    Vzorec pro n-tý člen:
    $$
    a_n = a_1 + (n-1)d
    $$
    
    kde $d$ je diference.
    
2. **Geometrická posloupnost**  
    Poměr mezi každými dvěma po sobě jdoucími členy je konstantní.  
    Například: $3, 6, 12, 24, \dots$  
    Vzorec pro n-tý člen:
    $$
    a_n = a_1 \cdot q^{n-1}
    $$
    
    kde $q$ je kvocient.
    
3. **Harmonická posloupnost**  
    Členy jsou převrácené hodnoty členů aritmetické posloupnosti.  
    Například: $1, \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \dots$
    

---

## Praktické použití

Posloupnosti se využívají v různých oblastech matematiky a aplikací, jako jsou:

- analýza a modelování dat,
- řešení diferenciálních rovnic,
- studium řad a jejich konvergence,
- kryptografie a šifrovací algoritmy.

