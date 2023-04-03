# Examen révision

## Installation

Créer un fork du repository

Cloner le repository git

Se rendre dans le dossier du projet, puis installer les dépendances avec NPM

```
cd <nom-du-projet>
npm install
```

Lancer le serveur de développement

```
npm run dev
```

## Consigne

Pour chaque chapitre, choisissez **une des options** (A, B ou C) et reproduisez le visuel de la colonne de droite.

La réussite d'une option vous permet d'obtenir la note suivante:
A => 4
B => 5
C => 6

### Attention

- Vous n'avez **pas besoin** d'intégrer les trois options (A, B et C)
- Pour une meilleure organisation, créez un module SCSS par section (flexbox, bootstrap, etc.)
- Il n'y a pas besoin d'intégrer au pixel perfect.
- Lorsqu'il est spécifié _Mobile_ et _Desktop_, vous devez réaliser un seul élément qui s'adapte en fonction de la largeur de l'écrant.
- Installez Bootstrap et le layout highlighter pour réaliser la section concernée.
- Pour appliquer une CSS spécifique à un exercice, utilisez l'id de l'exercice:

```scss
#flexbox-a1 {
  .wrapper {
    display: flex;
  }

  .item {
    background: red;
  }
}
```

## Barème

| **Sujet**                        | **points** |
| -------------------------------- | ---------- |
| Installation et organisation CSS | 12         |
| Flexbox                          | 18         |
| Bootstrap                        | 18         |
| Positions                        | 12         |
| Media Queries                    | 12         |
| Transitions                      | 6          |
| JavaScript                       | 6 (bonus)  |
| **Total**                        | **78**     |
