# 7. Variables i tipus


---

<small class="small">UD02 · DAM · 2025</small>


### 7.1 Què són i com es declaren
```java
int primerNumero = 56;
int segonNumero = 23;
System.out.println(primerNumero + segonNumero); // 79
```
**Regla:** primer el **tipus**, després el **nom**. Es pot **inicialitzar** en la mateixa línia.

### 7.2 Tipus de dades primitives


|   Tipus	|   Decimals	|   Mida	|   Exemple	|   	|
|:-:	|:-:	|:-:	|:-:	|---	|
|   `byte` | No       | 1B   | `byte edat = 25;`                 |
| `short`| No       | 2B   | `short alt = 160;`                |
| `int`  | No       | 4B   | `int suma = 100;`                 |
| `long` | No       | 8B   | `long diners = 20000L;`           |
| `float`| Sí       | 4B   | `float preu = 2.5f;`              |
| `double`| Sí      | 8B   | `double pi = 3.1416;`            |
| `char` | No       | 2B   | `char lletra = 'A';`              |
| `boolean`| No     | 1B   | `boolean actiu = true;`           |


### 7.3 Operacions bàsiques i abreujades
- Matemàtiques: `+ - * / %`
- Relacionals: `> >= < <= == !=`
- Lògiques: `&& || !`
- Abreujades: `+= -= *= /=`, `++ --`

### 7.4 Exemple lògic
```java
if ((a == 3 && b > 5) || (a == 7 && !(b < 4))) {
    // condició certa
}
```


