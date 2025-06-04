### Pré-requis :

Les logiciels suivants doivent être installés sur votre machine :

- [Node.js](https://nodejs.org/) et npm (au minimum node v 10.x et npm 5.x).
- Maven 3
- Java 8

### Instructions :

  - Télécharger l'ensemble du projet
  - Démarrer la partie back dans foobarquix-back : 
  ```bash
  mvn spring-boot:run
  ```
  - Installer bootstrap si non installé dans foobarquix-ui : 
  ```bash
  npm install bootstrap@3 --save
  ```
  - Démarrer la partie front dans foobarquix-ui : 
  ```bash
  ng serve
  ```
  - Les instructions du kata se trouvent ensuite  [ici](http://localhost:4200/) 

FooBarQix

You should implement a function String compute(String) which implements the following rules.

Step 1
Rules
If the number is divisible by 3, write “Foo” instead of the number
If the number is divisible by 5, add “Bar”
If the number is divisible by 7, add “Qix”
For each digit 3, 5, 7, add “Foo”, “Bar”, “Qix” in the digits order.
