# 9. Bucles


---

<small class="small">UD02 · DAM · 2025</small>

---

![Diagrama bucles](./imatges/bucles_java.png)

---

### while
```java
int x = 5;
while (x > 0) {
    x--;
}
```

### do…while
```java
int op;
do {
    // mostra menú
    op = llegirOpcio();
} while (op != 0);
```

### for
```java
for (int i = 0; i < 10; i++) {
    System.out.println(i);
}
```

### break / continue
```java
for (int i = 1; i <= 10; i++) {
    if (i == 8) break;      // ix del bucle
    if (i % 2 == 0) continue; // passa a la següent iteració
    System.out.println(i);
}
```

Els **bucles** permeten **repetir un bloc de codi** mentre es
complisca una condició lògica.\
Són una eina essencial del **control de flux** en programació.


------------------------------------------------------------------------
