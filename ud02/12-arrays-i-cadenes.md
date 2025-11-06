# 12. Arrays i cadenes


---

<small class="small">UD02 · DAM · 2025</small>


### 12.1 Arrays

```java


int[] a = {10, 20, 30};
System.out.println(a[1]); // 20

double[] dades = new double[1000];
dades[0] = 5.5;
```

Un **array** es una **estructura de datos** que almacena **varios
valores del mismo tipo** bajo un solo nombre.\
Cada valor ocupa una **posición (índice)** que empieza en **0**.

------------------------------------------------------------------------
# Declaració i creació





``` java
int[] numeros = new int[3]; 
String[] nombres = {"Ana", "Luis", "María"}; // Inicializació directa
```

-   Els valors s´accedeixen per índex: `nombres[0]`, `nombres[1]`, etc.\
-   Els arrays tenen **tamany fixe**.\
-   Propietat útil: `array.length` torna el tamany.



# 12.2 Accés i modificació




``` java
numeros[0] = 10;
System.out.println(numeros[0]); 

```

---

![Arrays i Strings](./imatges/arrays_strings.png)

---
# 12.3 Recorregut

> ** Nota d'imatges:** copia els arxius a `docs/assets/imatges/`. Els enllaços dels capítols apunten a `assets/imatges/...`.

---



### Amb `for`

``` java
for (int i = 0; i < numeros.length; i++) {
    System.out.println(numeros[i]);
}
```

### Amb `for-each`

``` java
for (int n : numeros) {
    System.out.println(n);
}
```


