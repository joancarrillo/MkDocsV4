# 6. El primer programa: “Hola Món”


---

<small class="small">UD02 · DAM · 2025</small>


Crea `HolaMundo.java`:
```java
// Aplicació HolaMundo de exemple
class HolaMundo {
    public static void main(String[] args) {
        System.out.println("Hola Món!");
    }
}
```
**Compila i executa:**
```bash
javac HolaMundo.java
java HolaMundo
```

### 4.1. Entendre el codi
- `class HolaMundo { … }` → defineix una **classe** (contenidor del codi).
- `public static void main(String[] args)` → punt d’entrada del programa.
- `System.out.println("…")` → escriu per pantalla i fa **salt de línia**.
- Cada **sentència** acaba amb `;`.
