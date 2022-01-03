# Requis architecturaux

## Responsabilité des classes

Durant les premiers laboratoires, vous avez vu quelques notions d'architecture logicielle, comme la séparation des requêtes et réponses, ou encore les responsabilités des couches du domaine et du UI. Pour le TP2, vous verrez 3 nouvaux types de classes qui aideront grandement à améliorer la qualité de votre code, c'est-à-dire à le rendre plus facilement évoluable et testable. Ainsi, vos classes de type *Resource* devraient être largement simplifiées et ne plus contenir de logique, mais bien seulement de l'*ordonnancement* (prendre et renvoyer).

Vous devrez donc vous assurer de faire une bonne utilisation des classes suivantes :

- Requête
- Réponse
- Entité
- Exception Mapper
- *Factory
- *Assembler
- *Repository

Ces trois nouvelles classes vous seront montrées lors du premier laboratoire du TP2.

## Packages

Afin de bien séparer ces classes, on vous demande également de choisir une **structure de dossiers** afin de séparer votre code en packages. Pour se faire, recherchez des stratégies existantes sur le Web. On parle souvent de "vertical slicing vs. horizontal slicing". Quelques degrés de séparations inclus :

- couches (api, domaine, etc.)
- modules (seller, product, etc.)
- type (requests, assemblers, etc.)

Certaines séparations sont plus adaptées à votre projet et permettre d'évoluer plus facilement. Assurez-vous de bien faire vos recherches et d'en discutter en équipe!
