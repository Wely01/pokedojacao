# pokedojacao
# Introdução

Esse Projeto tenta reproduzir com Html, CSS e Javascript a pokedex do anime e game Pokemon.

![233459737-46aa426a-7c0a-439c-8ebc-b0a6ca89ba01](https://github.com/user-attachments/assets/049ddd1d-4919-4069-8826-a425f79485de)


# tecnologias usadas no projeto
* HTML: Linguagem de marcação.


* CSS: Linguagem Utilizada para estilizar a tela.


* JavaScript: JavaScript é uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica fraca e multiparadigma.

# Requisitos

* Ter o VSCode para editar os códigos

* Ter um Browser para visualizar o resultado

# HTML da Pagina 
```py
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Links -->
  <link rel="shortcut icon" href="./images/favicon.png" type="image/x-icon">
  <link rel="stylesheet" href="./style/style.css">

  <!-- Main JS (defer para que o JS carregue somente depois do HTML) -->
  <script defer src="./js/script.js"></script>

  <title>Pokédex</title>
</head>

<body>
  <main>
    <img alt="Pokemón" class="pokemon__image">

    <h1 class="pokemon__data">
      <span class="pokemon__number"></span>
      <span class="pokemon__name"></span>
    </h1>

    <h1 class="pokemon__infos">
      <span class="pokemon__height"></span>
      <span class="pokemon__weight"></span>
    </h1>

    <form class="form">
      <input type="search" class="input__search" placeholder="Encontrar Pokémon" required>
      </label>
    </form>

    <img src="./images/pokedex.png" alt="Pokédex" class="pokedex">
  </main>

</body>

</html>


```

# Link Vercel
https://vercel.com/welys-projects/pokedojacao
