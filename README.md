# Entrega SASS II + SEO

Para esta entrega se agregaron los metadatas para el SEO y ademas de las modificaciones necesarias para Sass

## SEO

Para el SEO se agregaron las etiquetas de meta en todas las paginas.
Utilice:

```
<meta name="description" content="...">
<meta name="keywords" content="...">
<meta name="author" content="...">
```

## Sass II

Para el Sass se maps y extends.
### [Maps](scss/_variable.scss):
```
$colors: (
    primary: #9fcc64,
    secondary: #85d6ff
);
```
### [Extends](scss/_cards.scss):
```
.flexCenter {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
}

.cardContainer {
  @extend .flexCenter;
}
```
