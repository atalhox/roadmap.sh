# Roadmap.sh - Fullstack

## 1. Introdução

MkDocs é uma ferramenta de geração de documentação estática escrita em Markdown e baseada em Python. 

Ela permite criar documentações bem estruturadas e fáceis de navegar.

!!! info "Informação"
    MkDocs é amplamente utilizado para criar sites de documentação técnica devido à sua simplicidade e suporte para temas personalizáveis.

Esta documentação da minha jornada full-stack fará uso do mkdocs.

## 2. Objetivo

Este documento tem como objetivo ensinar a instalar, configurar e rodar o MkDocs localmente para criação de documentações.

## 3. Público-alvo

Este guia é indicado para desenvolvedores, documentaristas e qualquer pessoa interessada em criar documentações utilizando o MkDocs.

## 4. Pré-requisitos

Antes de começar, certifique-se de ter os seguintes requisitos instalados:
- Python 3.6 ou superior
- Pip (gerenciador de pacotes do Python)

!!! warning "Atenção"
    Verifique se o Python e o Pip estão corretamente instalados rodando `python --version` e `pip --version` no terminal.

## 5. Instalação do MkDocs

Para instalar o MkDocs, utilize o comando abaixo:
```sh
pip install mkdocs
```

Verifique se a instalação foi bem-sucedida rodando:
```sh
mkdocs --version
```

!!! tip "Dica"
    Caso encontre erros na instalação, tente rodar o comando com `pip install --upgrade pip` antes de instalar o MkDocs.

## 6. Projeto MkDocs

A uma estrutura básica é com o arquivo `mkdocs.yml` e a pasta `docs/`.

!!! note "Nota"
    O arquivo `mkdocs.yml` contém as configurações do projeto, enquanto a pasta `docs/` armazena os arquivos Markdown da documentação.

## 7. Rodando o MkDocs Localmente

Dentro da pasta do projeto, execute:
```sh
mkdocs serve
```
O servidor local será iniciado e a documentação poderá ser acessada no navegador em `http://127.0.0.1:8000/`.

!!! tip "Dica"
    O MkDocs recarrega automaticamente as alterações feitas nos arquivos Markdown enquanto o servidor está rodando.

## 8. Referências
- [Documentação Oficial do MkDocs](https://www.mkdocs.org/)
- [Guia de Publicação no GitHub Pages](https://www.mkdocs.org/user-guide/deploying-your-docs/)

## 9. Código

Esta documentação no projeto github visa contemplar o código das soluções apresentadas. 


