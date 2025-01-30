# Introdução ao HTML

## 1. Introdução

O HTML (HyperText Markup Language) é a base da estrutura de qualquer página web. Ele define a organização do conteúdo e permite a interação com outros elementos da web, como CSS e JavaScript. 

Para um desenvolvedor Full Stack, é essencial compreender não apenas a sintaxe básica do HTML, mas também suas boas práticas e otimizações para garantir acessibilidade, desempenho e integração com tecnologias modernas.

## 2. Objetivo

Este documento tem como objetivo fornecer um guia estruturado sobre HTML, abordando desde conceitos básicos até técnicas avançadas, boas práticas e dicas para um desenvolvedor Full Stack.

## 3. Público-alvo
Desenvolvedores Full Stack, iniciantes e experientes, que desejam aprimorar seus conhecimentos em HTML e garantir um desenvolvimento web eficiente e moderno.

## 4. Conteúdo

### 4.1. Fundamentos do HTML
- Estrutura básica de um documento HTML
- Elementos essenciais: `<html>`, `<head>`, `<body>`
- Tags de texto: `<h1>-<h6>`, `<p>`, `<span>`, `<strong>`, `<em>`
- Listas: `<ul>`, `<ol>`, `<li>`
- Links e navegação: `<a>`
- Imagens e mídia: `<img>`, `<audio>`, `<video>`

### 4.2. Estruturação e Semântica
- Importância da semântica HTML
- Tags semânticas: `<header>`, `<nav>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- Formatação avançada com `<div>` e `<span>`
- Uso correto das tabelas: `<table>`, `<tr>`, `<td>`, `<th>`
- Elementos de formulários: `<form>`, `<input>`, `<label>`, `<textarea>`, `<button>`

### 4.3. HTML e Acessibilidade (A11Y)
- Importância da acessibilidade
- Uso adequado de atributos `alt`, `aria-label` e `role`
- Navegação acessível com teclado
- Contraste e legibilidade

### 4.4. Performance e SEO
- Estratégias de carregamento eficiente
- Minificação e compressão de código
- Uso correto de metatags (`<meta>`) para SEO
- Estrutura correta de heading tags (`<h1>-<h6>`) para hierarquia de conteúdo
- Uso de `lazy-loading` para otimização de imagens

### 4.5. HTML Moderno
- Novas tags do HTML5
- Uso de APIs modernas: Geolocation, Web Storage, Canvas
- Integração com CSS Grid e Flexbox
- Componentização com Web Components

### 4.6. Boas Práticas e Padrões de Código
- Identificação e formatação correta do código
- Uso de atributos globais (`id`, `class`, `data-*`)
- Separar estrutura (HTML), estilo (CSS) e comportamento (JavaScript)
- Compatibilidade entre navegadores

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

### 5.2. Exemplos de Uso

#### 5.2.1. Links e imagens
```html
<a href="https://exemplo.com">Visite nosso site</a>
<img src="imagem.jpg" alt="Imagem descritiva">
```

#### 5.2.2. Formulários
```html
<form action="submit.php" method="POST">
    <label for="nome">Nome:</label>
    <input type="text" id="nome" name="nome" required>
    <button type="submit">Enviar</button>
</form>
```

## 6. Referências
- [Documentação oficial do HTML MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [W3C HTML Specification](https://www.w3.org/TR/html52/)
- [Google Lighthouse para Performance e SEO](https://developers.google.com/web/tools/lighthouse)
