# 11.Control del flux dins dels bucles


---

<small class="small">UD02 · DAM · 2025</small>


### `break`

Interromp el bucle immediatament, eixint d’ell.

``` java
for (int i = 1; i <= 10; i++) {
    if (i == 5) break;
    System.out.println(i);
}
```

>  El bucle s’atura quan `i` vale 5.


### `continue`

Salta la iteració actual i **passa directament a la següent**.

``` java
for (int i = 1; i <= 5; i++) {
    if (i == 3) continue;
    System.out.println(i);
}
```

>  S’omet la iteració on `i == 3`.



# Recomanacions

---

1.  Evita els **bucles infinits** (`while(true)`) excepte que controles
    la seua eixida amb `break`.\
2.  Utilitza **noms clars** para las variables de control (`i`,
    `contador`, `indice`).\
3.  Assegura’t d’**actualitzar la variable de control** dins del bucle per a evitar bloquejos.\
4.  Practica amb diferents tipus de condicions per a entendre com
    canvia el flux.
