# Dev Week 2025
Java RESTful API criada para a Dev Week 2025

## Diagrama de Classes

```mermaid
classDiagram
    class Usuario {
        -String name
        -Account account        
        -Card card
        -Feature[] features
        -News[] news
    }

    class Account {
        -String number
        -String agency
        -float balance
        -float limit
    }

    class Card {
        -String number
        -float limit
    }

    class Feature {
        -String icon
        -String description
    }

    class News {
        -String icon
        -String descripton
    }

    Usuario --> Account
    Usuario --> Card
    Usuario --> Feature
    Usuario --> News
```
