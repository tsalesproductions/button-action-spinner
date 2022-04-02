![](https://www.freakyjolly.com/wp-content/uploads/2020/06/react-bootstrap-loading-spinner-2.gif)

### O que o plugin faz?
Ao adicionar o acionador, o código identifica o seu botão e prepara ele mostrando um callback de loading

### Recursos
- spinner circular
- spinner grow
----
| Acionadores  | Valores |
| ------------- | ------------- |
| data-action  | empty/sm  |
| data-grow  | empty/sm  |
| data-color  | hexadecimal color |

### Como usar?

##### Spinner circular
O acionador é identificado por `data-action`.
```HTML
<button type="submit" data-action>Acessar</button>
```
##### Spinner circular pequeno
```HTML
<button type="submit" data-action="sm">Acessar</button>
```

##### Spinner circular pequeno colorido
```HTML
<button type="submit" data-action="sm" data-color="#f00">Acessar</button>
```
----
##### Spinner circular
O acionador é identificado por `data-grow`.
```HTML
<button type="submit" data-grow>Acessar</button>
```
##### Spinner circular pequeno
```HTML
<button type="submit" data-grow="sm">Acessar</button>
```

##### Spinner circular pequeno colorido
O acionador responsável por adicionar cor é `data-color`, e a cor deve estar em hexadeciomal.
```HTML
<button type="submit" data-grow="sm" data-color="#f00">Acessar</button>
```

###End
