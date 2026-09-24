# ⚡ Linguagens de Programação Comparadas

Tabela interativa comparando **9 linguagens de programação** lado a lado:
**JavaScript, PHP, Golang, Python, Rust, C, C++, C# e Java**.

O objetivo é oferecer um material de consulta rápida para quem deseja entender como cada
linguagem aborda conceitos fundamentais — da história e instalação até estruturas de
controle, manipulação de strings, acesso a bancos de dados e casos de uso.

> 🔗 **Acesse a página online:** <https://mervy.github.io/programming-languages-comparative/>

## ✨ Funcionalidades

- 🧪 **Exemplos completos e testados**: cada célula traz um programa que compila e roda, não só um trecho solto
- ▶️ **Como rodar** em cada exemplo (comando do terminal, bibliotecas e flags necessárias)
- 🖥️ **Saída real** logo abaixo do código, mostrando o que aparece no terminal
- 📋 Botão **copiar** em cada bloco de código
- 🏷️ Logo de cada linguagem no cabeçalho, com link para o site oficial (abre em nova aba)
- 🔎 Busca por palavra-chave (ex.: `loop`, `string`, `postgres`)
- 🗂️ Filtro por tópico
- 📊 Tabela com cabeçalho e coluna de tópicos fixos (rolagem horizontal e vertical)

## 📚 Tópicos comparados

| Tópico | O que mostra |
| --- | --- |
| História (quem, quando, por quê) | Criadores, ano e motivação |
| Playground online | Onde testar sem instalar nada |
| Instalação (Windows / Linux) | Comandos oficiais (nvm, rustup, `dotnet-sdk-10.0`, OpenJDK/Temurin 25…) |
| Comandos: criar / rodar programas | Criar projeto, rodar, compilar, instalar pacotes |
| Tipos de dados | Tipos primitivos e compostos, inferência e conversões |
| Funções | Parâmetro padrão, vários retornos, closures, funções como parâmetro, recursão |
| Entrada de dados no terminal (prompt) | Ler texto e número com validação |
| Cálculos | Divisão inteira, resto, arredondamento, overflow, juros compostos |
| Strings | Interpolação, fatiar, buscar, substituir, split/join, bytes x caracteres |
| Loops | for, for-each com índice, while, do-while, break/continue, rótulos |
| if / else / match / switch | Ternário, switch, `match`/pattern matching |
| Arrays / Listas / Dicionários | Adicionar/remover, map/filter/reduce, ordenar, dicionários |
| Datas e horas | Formatar, ler texto, somar dias, diferença entre datas, fuso horário |
| Classes / POO | Encapsulamento, herança (ou composição), interfaces, polimorfismo |
| Tratamento de erros | Exceções personalizadas, `Result`, `error`, finally/defer |
| Banco de dados: conectar e listar (MySQL) | Conexão → query → exibição dos dados na tela |
| CRUD (Postgres) | INSERT, SELECT, UPDATE e DELETE com parâmetros, listando a tabela após cada passo |
| API HTTP (teste com curl) | Servidor mínimo que devolve JSON + comando `curl` para testar |
| Frameworks e bibliotecas populares | React, NestJS, Laravel, FastAPI, Spring Boot, ASP.NET Core, Axum… |
| Principais usos | Onde cada linguagem é mais usada |

## 🧪 Como os exemplos foram testados

Todos os programas foram executados de verdade (e a saída mostrada na página é a saída real) com:
Node.js 22, PHP 8.4, Go 1.25, Python 3.11, Rust 1.94, GCC/G++ 13 (C17 / C++20),
.NET 10 e Java 21, contra MySQL/MariaDB e PostgreSQL 16 locais.

## 🚀 Rodando localmente

Não há dependências — basta abrir o arquivo `index.html` no navegador.

```bash
# Opção 1: abrir direto
open index.html   # macOS
xdg-open index.html   # Linux

# Opção 2: servidor local
python3 -m http.server 8000
# acesse http://localhost:8000
```

## 🌐 Publicando no GitHub Pages

1. Suba o projeto para o GitHub.
2. Em **Settings → Pages**, em *Build and deployment*, selecione:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` · **Folder:** `/ (root)`
3. Clique em **Save**. A página ficará disponível em:

```
https://mervy.github.io/programming-languages-comparative/
```

> O arquivo `index.html` na raiz do repositório é o ponto de entrada da página.

## 📁 Estrutura

```
programming-languages-comparative/
├── index.html   # Página da tabela comparativa (GitHub Pages)
├── logos/       # Logos SVG das linguagens (Devicon, licença MIT)
└── README.md
```

## 🧑‍💻 Sobre

Projeto educacional para estudo e revisão de linguagens de programação.
Atualizado em 2026.

Logos das linguagens: [Devicon](https://devicon.dev) (licença MIT). As marcas pertencem aos respectivos donos.
