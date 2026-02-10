# Kurrikulum

## Aurkibidea:
- [Kurrikulum](#kurrikulum)
  - [Aurkibidea:](#aurkibidea)
      - [Datu Pertsonalak:](#datu-pertsonalak)
      - [Profil Profesionala:](#profil-profesionala)
      - [Trebetasun teknikoak:](#trebetasun-teknikoak)
      - [Formazioa:](#formazioa)
      - [Kode zati bat (Java):](#kode-zati-bat-java)


#### Datu Pertsonalak:
| ![Me](./6105bf79-0248-4ccd-8d59-15e694ae7cf6.png){width=130px} | - Izena: **Alex Moreno Ruiz**<br>- Adina: 27 urte<br>- Email: alex.moreno.dev@gmail.com<br>- Telefonoa: 600 123 456<br>- LinkedIn: linkedin.com/in/alex-moreno-dev<br>- GitHub: github.com/alexmoreno-dev |
|---|---|

#### Profil Profesionala:
Mahaigaineko eta web aplikazioen garapenean ezagutza sendoak dituen programatzaile juniorra. Kode garbiaren, objektuetara bideratutako programazioaren eta etengabeko ikaskuntzaren zale amorratua. Esperientzia proiektu akademiko eta pertsonaletan, Java, Python eta web teknologiak erabiliz.

#### Trebetasun teknikoak:
| Arloa | Trebetasuna |
|-------|-------------|
| Lengoaiak | Java, Python, JavaScript, SQL |
| Teknologiak | HTML, CSS, Git, JDBC |
| Paradigmak | Objektuetara Bideratutako Programazioa |
| Datu-baseak | MySQL |
| Bestelakoak | UML, MVC, plataforma anitzeko garapena |

#### Formazioa:
  **Plataforma Anitzeko Aplikazioen Garapeneko goi-mailako gradua**
 Prestakuntza Teknologikoko Zentroa (2023 – 2025)

#### Kode zati bat (Java):
```java
import java.util.Scanner;

public class LoginSimple {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Sartu erabiltzailea: ");
        String usuario = sc.nextLine();

        System.out.print("Sartu pasahitza: ");
        String password = sc.nextLine();

        if (usuario.equals("admin") && password.equals("1234")) {
            System.out.println("Sarbidea emanda");
        } else {
            System.out.println("Sarbidea ukatuta");
        }

        sc.close();
    }
}
```
