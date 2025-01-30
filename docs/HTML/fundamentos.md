# Fundamentos do HTML

## 1. Introdução

HTML (HyperText Markup Language) é a linguagem padrão para criação de páginas web.

Ele define a estrutura de um documento web por meio de elementos e tags que organizam e apresentam o conteúdo.

!!! info "Informação"
    HTML é a base para a criação de páginas web e trabalha em conjunto com CSS e JavaScript para estruturar e estilizar conteúdos interativos.

## 2. Objetivo

Este documento tem como objetivo apresentar os fundamentos do HTML, explicando a estrutura básica de um documento HTML, os elementos essenciais e os principais componentes utilizados na construção de páginas web.

## 3. Público-alvo

Este material é indicado para iniciantes em desenvolvimento web, estudantes de tecnologia e profissionais que desejam compreender os conceitos fundamentais do HTML.

## 4. Conteúdo

### 4.1 Estrutura Básica de um Documento HTML

Todo documento HTML segue uma estrutura padrão, conforme mostrado no exemplo abaixo:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Primeira Página HTML</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Este é um parágrafo em HTML.</p>
</body>
</html>
```

!!! tip "Dica"
    Sempre utilize `<!DOCTYPE html>` no início do documento para garantir a compatibilidade com os navegadores modernos.
    
!!! tip "Dica"
    Utilize sempre a tag `<meta charset="UTF-8">` no `<head>` para garantir a correta codificação dos caracteres.

### 4.2 Elementos Essenciais

Os elementos essenciais de um documento HTML incluem:

| **Elemento** | **Descrição**                                            |
| ------------ | -------------------------------------------------------- |
| `<html>`     | Elemento raiz do documento.                              |
| `<head>`     | Contém metadados, título e links para estilos e scripts. |
| `<body>`     | Contém o conteúdo visível da página.                     |

!!! note "Nota"
    O `<head>` pode conter elementos importantes como `<meta>`, `<link>` e `<script>`, que ajudam a melhorar a performance e acessibilidade do site.

### 4.3 Tags de Texto

As tags de texto são utilizadas para definir hierarquia e estilo:

| **Elemento**    | **Descrição**                                                                        |
| --------------- | ------------------------------------------------------------------------------------ |
| `<h1>` a `<h6>` | Definem títulos e subtítulos. `<h1>` é o mais importante, `<h6>` o menos importante. |
| `<p>`           | Cria parágrafos.                                                                     |
| `<span>`        | Elemento inline para aplicação de estilos ou manipulação de partes do texto.         |
| `<strong>`      | Texto em negrito para dar ênfase.                                                    |
| `<em>`          | Texto em itálico para denotar ênfase leve.                                           |

!!! warning "Atenção"
    Evite usar `<h1>` mais de uma vez na mesma página. Utilize títulos em ordem hierárquica para melhor acessibilidade.

### 4.4 Listas

HTML permite a criação de listas ordenadas e não ordenadas:

| **Elemento** | **Descrição**                                                                      |
| ------------ | ---------------------------------------------------------------------------------- |
| `<ul>`       | Lista não ordenada (com marcadores). Ideal para itens sem sequência específica.    |
| `<ol>`       | Lista ordenada (numerada). Usada para sequências lógicas.                          |
| `<li>`       | Item dentro de uma lista (`<ul>` ou `<ol>`). Cada `<li>` define um ponto na lista. |

Exemplo:
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>

<ol>
    <li>Primeiro</li>
    <li>Segundo</li>
</ol>
```

### 4.5 Links e Navegação

A tag `<a>` é usada para criar links:
```html
<a href="https://www.exemplo.com">Visite o site</a>
```

!!! tip "Dica"
    Utilize `target="_blank"` para abrir links externos em uma nova aba.

### 4.6 Imagens e Mídia

HTML permite incorporar imagens e mídia:

| **Elemento** | **Descrição**                                                                                |
| ------------ | -------------------------------------------------------------------------------------------- |
| `<img>`      | Insere imagens. O atributo `src` define o caminho e `alt` fornece uma descrição alternativa. |
| `<audio>`    | Reproduz arquivos de áudio. Pode incluir controles e suporta diferentes formatos.            |
| `<video>`    | Incorpora vídeos. Pode incluir controles, autoplay e opções de mudo.                         |

Exemplo:
```html
<img src="imagem.jpg" alt="Descrição da imagem">
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
</audio>
<video controls width="320">
    <source src="video.mp4" type="video/mp4">
</video>
```

!!! info "Informação"
    Sempre utilize o atributo `alt` em imagens para melhorar a acessibilidade e otimização para mecanismos de busca (SEO).

## 5. Guia de Uso

Para utilizar HTML, basta criar um arquivo com extensão `.html` e abri-lo em um navegador.

Recomendamos editores de código como Visual Studio Code ou Sublime Text para facilitar o desenvolvimento.

!!! tip "Dica"
    Utilize extensões como "Live Server" no Visual Studio Code para visualizar suas alterações em tempo real.

## 6. Referências
- [Documentação Oficial do HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [W3Schools - HTML](https://www.w3schools.com/html/)

