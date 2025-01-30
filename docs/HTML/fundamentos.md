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

Claro! Vou combinar todos os elementos fornecidos em uma única tabela para facilitar a visualização:

| **Elemento**    | **Descrição**                                                                                                                                                        |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `<html>`        | Envolve todo o conteúdo da página web, definindo o início e o fim do documento HTML.                                                                                 |
| `<head>`        | Contém informações que não são exibidas diretamente na página, como metadados, links para arquivos de estilo (CSS) e scripts (JavaScript), além do título da página. |
| `<body>`        | Abriga todo o conteúdo que será exibido aos usuários, incluindo textos, imagens, vídeos, links, etc.                                                                 |
| `<h1>` a `<h6>` | São utilizados para definir títulos e subtítulos, onde `<h1>` representa o nível mais alto (mais importante) e `<h6>` o mais baixo.                                  |
| `<p>`           | Serve para estruturar textos em parágrafos, facilitando a leitura e organização do conteúdo.                                                                         |
| `<span>`        | Um elemento inline usado para aplicar estilos ou manipular partes específicas do texto sem quebrar o fluxo do conteúdo.                                              |
| `<strong>`      | Indica que o texto tem forte importância, geralmente renderizado em negrito pelos navegadores.                                                                       |
| `<em>`          | Denota ênfase no texto, frequentemente exibido em itálico, sugerindo uma entonação diferenciada na leitura.                                                          |

!!! warning "Atenção"
    Evite usar `<h1>` mais de uma vez na mesma página. Utilize títulos em ordem hierárquica para melhor acessibilidade.

### 4.4 Listas

HTML permite a criação de listas ordenadas e não ordenadas:
Claro! Vou atualizar a tabela para incluir os novos elementos que você forneceu. Além disso, atualizarei a **Descrição Detalhada dos Elementos** para abranger todos os itens listados até agora.

### Tabela Atualizada dos Elementos HTML

| **Elemento** | **Descrição**                                                                                                             |
| ------------ | ------------------------------------------------------------------------------------------------------------------------- |
| `<ul>`       | Utilizado para criar uma lista não ordenada (com marcadores). É ideal para itens que não seguem uma sequência específica. |
| `<ol>`       | Utilizado para criar uma lista ordenada (numerada). É apropriado para itens que seguem uma sequência ou ordem lógica.     |
| `<li>`       | Representa um item dentro de uma lista (`<ul>` ou `<ol>`). Cada `<li>` define um ponto ou entrada na lista.               |

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
    Sempre utilize o atributo `target="_blank"` ao criar links externos para abrir em uma nova aba.

### 4.6 Imagens e Mídia

HTML permite incorporar imagens e mídia:
Claro! Aqui está a nova tabela contendo apenas os elementos `<img>`, `<audio>` e `<video>`:

| **Elemento** | **Descrição**                                                                                                                                                                                  |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `<img>`      | Utilizado para inserir imagens na página web. É um elemento vazio que requer o atributo `src` para especificar o caminho da imagem e o atributo `alt` para fornecer uma descrição alternativa. |
| `<audio>`    | Permite a reprodução de arquivos de áudio na página. Pode incluir controles de reprodução e suporta diferentes formatos de áudio.                                                              |
| `<video>`    | Usado para incorporar vídeos na página web. Suporta múltiplas fontes de vídeo e pode incluir controles de reprodução, bem como opções para reprodução automática, mudo, entre outros.          |

Exemplo de uso:
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



