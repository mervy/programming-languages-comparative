# ⚡ Linguagens de Programação Comparadas

Tabela interativa comparando **9 linguagens de programação** lado a lado:
**JavaScript, PHP, Golang, Python, Rust, C, C++, C# e Java**.

O objetivo é oferecer um material de consulta rápida para quem deseja entender como cada
linguagem aborda conceitos fundamentais — da história e instalação até estruturas de
controle, manipulação de strings, acesso a bancos de dados e casos de uso.

> 🔗 **Acesse a página online:** <https://mervy.github.io/programming-languages-comparative/>

## ✨ Funcionalidades

- 🔎 Busca por palavra-chave (ex.: `loop`, `string`, `postgres`)
- 🗂️ Filtro por tópico
- 📊 Tabela com coluna de tópicos fixa (rolagem horizontal e vertical)
- 🧩 Códigos de exemplo prontos para copiar

## 📚 Tópicos comparados

| Tópico |
| --- |
| História (quem, quando, por quê) |
| Playground online |
| Instalação (Windows / Linux) |
| Comandos: criar / rodar programas |
| Tipos de dados |
| Função |
| Entrada de dados no terminal (prompt) |
| Cálculos |
| Strings |
| Loops |
| if / else / match / switch |
| Arrays / Listas |
| Datas e horas |
| Banco de dados (Postgres / MySQL) |
| CRUD: ler, editar, apagar |
| Principais usos |

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
└── README.md
```

## 🧑‍💻 Sobre

Projeto educacional para estudo e revisão de linguagens de programação.
Atualizado em 2026.
