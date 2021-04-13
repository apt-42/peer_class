# 42 peer classes

<p align="center">
  <img src="assets/clean-secure.jpg" alt="Amazing artwork" width="500" />
</p>

## Clean code

> "Clean code can be read, and enhanced by a developer other than its original author. It has unit and acceptance tests. It has meaningful names. It provides one way rather than many ways for doing one thing. It has minimal dependencies, which are explicitly defined, and provides a clear and minimal API."

All quotes are from [Clean code](https://www.goodreads.com/work/quotes/3779106-clean-code-a-handbook-of-agile-software-craftsmanship-robert-c-martin).

#### Des spaghettis

<p align="center">
  <img src="assets/Cablespaghetti2.jpg" alt="spaghetti" />
</p>

- [Wiki: Syndrome du plat de spaghettis](https://fr.wikipedia.org/wiki/Syndrome_du_plat_de_spaghettis)
- [Wiki: Programmation spaghetti](https://fr.wikipedia.org/wiki/Programmation_spaghetti)
- [Wiki: Couplage (informatique](https://fr.wikipedia.org/wiki/Couplage_(informatique))

#### Clair

> "It is not the language that makes programs appear simple. It is the programmer that make the language appear simple!"  
> "Clean code is simple and direct. Clean code reads like well-written prose"

- [Wiki: Programmation modulaire](https://fr.wikipedia.org/wiki/Programmation_modulaire)
- [How to Organize Clean Architecture to Modular Patterns in 10 Minutes](https://www.codeproject.com/Articles/1210984/How-to-Organize-Clean-Architecture-to-Modular-Patt)

Code propre :
- facile à lire et à comprendre
- modulaire
- 1 fonction -> 1 action

#### Bien nommer

> "A long descriptive name is better than a long descriptive comment."

- [Naming cheatsheet](https://github.com/kettanaito/naming-cheatsheet)

#### Flowcharts

- [Flowchart In Programming](https://www.programiz.com/article/flowchart-programming)
- Flowcharts: [app.diagrams.net](https://app.diagrams.net/)

#### Tester

> "It is unit tests that keep our code flexible, maintainable, and reusable. The reason is simple. If you have tests, you do not fear making changes to the code! Without tests every change is a possible bug."

- [Wiki: Test driven development](https://fr.wikipedia.org/wiki/Test_driven_development)

Plusieurs types de tests :
- **test unitaire / unit testing :** on vérifie le bon fonctionnement d'une partie précise, d'une "unité"
- **test d'intégration / integration testing :** on intègre les modules testés à l'unité et on teste l'ensemble
- **test de validation / acceptance testing :** on vérifie l'intégralité du logiciel et qu'il répond aux exigences exprimées par le client

Faites vos propres tests et automatisez-les (Github Actions, Circle CI, Travis CI...).

Il faut écrire les tests avant le programme en y allant petit à petit.

- [Unit testing with asserts](http://www.electronvector.com/blog/unit-testing-with-asserts)
