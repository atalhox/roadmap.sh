# Introdução ao HTML

## 1. Introdução

O HTML (HyperText Markup Language) é a base da estrutura de qualquer página web.

Ele define a organização do conteúdo e permite a interação com outros elementos da web, como CSS e JavaScript.

Para um desenvolvedor Full Stack, é essencial compreender não apenas a sintaxe básica do HTML, mas também suas boas práticas e otimizações para garantir acessibilidade, desempenho e integração com tecnologias modernas.

## 2. Objetivo

Este documento tem como objetivo fornecer um guia estruturado sobre HTML, abordando desde conceitos básicos até técnicas avançadas, boas práticas e dicas para um desenvolvedor Full Stack.

## 3. Público-alvo

Desenvolvedores Full Stack, iniciantes e experientes, que desejam aprimorar seus conhecimentos em HTML e garantir um desenvolvimento web eficiente e moderno.

## 4. Conteúdo

### 4.1. Fundamentos do HTML

Estrutura básica de um documento HTML:

- Elementos essenciais: `<html>`, `<head>`, `<body>`
- Tags de texto: `<h1>-<h6>`, `<p>`, `<span>`, `<strong>`, `<em>`
- Listas: `<ul>`, `<ol>`, `<li>`
- Links e navegação: `<a>`
- Imagens e mídia: `<img>`, `<audio>`, `<video>`

!!! tip "Dica"
    Sempre comece seu documento HTML com a declaração `<!DOCTYPE html>` para garantir que o navegador interprete o documento corretamente.

### 4.2. Estruturação e Semântica

- Importância da semântica HTML
- Tags semânticas: `<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- Formatação avançada com `<div>` e `<span>`
- Uso correto das tabelas: `<table>`, `<tr>`, `<td>`, `<th>`
- Elementos de formulários: `<form>`, `<input>`, `<label>`, `<textarea>`, `<button>`

!!! warning "Atenção"
    Evite o uso excessivo de `<div>` e `<span>` para estruturar o conteúdo. Prefira sempre que possível as tags semânticas para melhorar a acessibilidade e SEO do seu site.

### 4.3. HTML e Acessibilidade (A11Y)

- Importância da acessibilidade
- Uso adequado de atributos `alt`, `aria-label` e `role`
- Navegação acessível com teclado
- Contraste e legibilidade

!!! warning "Atenção"
    Ignorar práticas de acessibilidade pode tornar seu site inutilizável para pessoas com deficiências e afetar negativamente a experiência do usuário.

### 4.4. Performance e SEO

- Estratégias de carregamento eficiente
- Minificação e compressão de código
- Uso correto de metatags (`<meta>`) para SEO
- Estrutura correta de heading tags (`<h1>-<h6>`) para hierarquia de conteúdo
- Uso de `lazy-loading` para otimização de imagens

!!! info "Info"
    O uso de `lazy-loading` para imagens ajuda a melhorar o tempo de carregamento da página, carregando as imagens apenas quando elas entram na área visível do usuário.

### 4.5. HTML Moderno

- Novas tags do HTML5
- Uso de APIs modernas: Geolocation, Web Storage, Canvas
- Integração com CSS Grid e Flexbox
- Componentização com Web Components

!!! tip "Dica"
    Web Components permitem a criação de elementos reutilizáveis e encapsulados, facilitando a manutenção e escalabilidade do código.

### 4.6. Boas Práticas e Padrões de Código

- Identificação e formatação correta do código
- Uso de atributos globais (`id`, `class`, `data-*`)
- Separar estrutura (HTML), estilo (CSS) e comportamento (JavaScript)
- Compatibilidade entre navegadores

!!! info "Info"
    Manter a estrutura, estilo e comportamento separados facilita a manutenção e colaboração entre diferentes áreas de desenvolvimento.

## 5. Guia de Uso

### 5.1. Configuração Inicial

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página HTML</title>
</head>
<body>
    <header>
        <h1>Bem-vindo ao HTML</h1>
    </header>
</body>
</html>
```

!!! tip "Dica"
    Definir o atributo `lang` no elemento `<html>` ajuda os motores de busca e leitores de tela a entenderem o idioma da página, melhorando a acessibilidade e SEO.

### 5.2. Exemplos de Uso

#### 5.2.1. Links e imagens

```html
<a href="https://exemplo.com">Visite nosso site</a>
<img src="imagem.jpg" alt="Imagem descritiva">
```

!!! info "Info"
    Sempre forneça um texto descritivo no atributo `alt` das imagens para melhorar a acessibilidade e SEO.

#### 5.2.2. Formulários

```html
<form action="submit.php" method="POST">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" required>
    <button type="submit">Enviar</button>
</form>
```

!!! tip "Dica"
    Utilize atributos como `required`, `minlength` e `pattern` para realizar validações básicas diretamente no HTML, melhorando a experiência do usuário.

## 6. Referências

- [Documentação oficial do HTML MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [W3C HTML Specification](https://www.w3.org/TR/html52/)
- [Google Lighthouse para Performance e SEO](https://developers.google.com/web/tools/lighthouse)

