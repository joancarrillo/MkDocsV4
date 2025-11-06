# 10.Tipus de bucles en Java


---

<small class="small">UD02 · DAM · 2025</small>


### 1. `while` --- Bucle condicional

Executa el bloc **mentre la condició siga vertadera**.\
Primer avalua la condició i després executa el codi.

``` java
int i = 1;
while (i <= 5) {
    System.out.println("Iteración: " + i);
    i++;
}
```

**Característiques:** - La condició s’avalua **abans** de cada
iteració.\
- Si la condició és falsa a l’inici, **no s’executa**.\
- S’utilitza quan **no sabem quantes vegades** es repetirà el procés.

------------------------------------------------------------------------

### 2. `do...while` --- Bucle postcondicional


Executa el bloc **almenys una vegada**, i **després avalua la condició**.

``` java
int i = 1;
do {
    System.out.println("Iteración: " + i);
    i++;
} while (i <= 5);
```

**Característiques:** - La condición se evalúa **después** de cada
ejecución.\
- Garantiza **al menos una iteración**.\
- Útil quan el bloc ha d’executar-se sempre una vegada (per exemple, demanar dades a l’usuari).

------------------------------------------------------------------------

### 3. `for` --- Bucle controlat

Permet definir **inicialització**, **condició** i **actualització** en una mateixa línia.

``` java
for (int i = 1; i <= 5; i++) {
    System.out.println("Iteración: " + i);
}
```


**Característiques:** - Se usa quan **coneguem el nombre exacte** de
repeticions.\
- És compacte i molt llegible.\
- Molt comú per a recórrer **arrays o col·leccions**.

------------------------------------------------------------------------

### 4. `for-each` --- Bucle millorat

Dissenyat per a recórrer **arrays o col·leccions** sense necessitat d’usar índexs.

``` java
String[] nombres = {"Ana", "Luis", "María"};
for (String nombre : nombres) {
    System.out.println("Hola " + nombre);
}
```

**Característiques:** - No permet modificar l’índex.\
- És més llegible i evita errors de límits.\


- Ideal per a recórrer llistes, arrays i col·leccions en general.

------------------------------------------------------------------------
