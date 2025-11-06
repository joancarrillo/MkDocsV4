# 13. Dades introduïdes per l’usuari


<small class="small">UD02 · DAM · 2025</small>

---

### 13.1 Classe `Scanner`
```java
import java.util.Scanner;

Scanner entrada = new Scanner(System.in);
System.out.print("Nom: ");
String nom = entrada.nextLine();
System.out.println("Hola, " + nom);
```

### 13.2 Netejar el buffer
Quan llegim un enter i després un `String`, cal consumir el `\n` pendent:
```java
int n = entrada.nextInt();
entrada.nextLine(); // neteja el \n
String nom = entrada.nextLine();
```
