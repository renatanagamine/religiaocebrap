# Observatório da Religião e Interseccionalidades

Este repositório abriga o site do Observatório da Religião e Interseccionalidades, um núcleo de pesquisa e análise de dados que monitora o debate público sobre religião e suas intersecções com raça, etnia, gênero, sexualidade e classe social.

## 🌐 Acesso ao site

Você pode acessar o site diretamente pelo GitHub Pages:

👉 [https://renatanagamine.github.io/religiaocebrap](https://renatanagamine.github.io/religiaocebrap)

## 📁 Estrutura de diretórios

- `index.html`: Página de apresentação do Observatório
- `sobre.html`: Página institucional com informações sobre missão, equipe e vinculação
- `contato.html`, `em-debate.html`: Outras seções informativas
- `pesquisas/`: Diretório com páginas específicas para cada linha de pesquisa
- `static/`: Contém as imagens das logos e eventuais outros recursos estáticos

## 🔧 Como editar

As páginas são escritas em HTML puro com estilo interno via CSS. Para editar:

1. Abra o arquivo desejado (ex: `sobre.html`)
2. Edite o conteúdo dentro das tags `<div class="main-content">...</div>`
3. Salve e faça commit com uma descrição clara

> ⚠️ Lembre-se: **o conteúdo pode não atualizar automaticamente no GitHub Pages devido ao cache**. Use `Ctrl + F5` ou abra em guia anônima para verificar mudanças.

## ✅ Checklist de funcionamento

- [x] Links relativos entre as páginas
- [x] Estrutura responsiva básica
- [x] Logos clicáveis (Cebrap redireciona para https://cebrap.org.br/)
- [x] Menu lateral com hierarquia de pesquisas
- [x] Layout compatível com GitHub Pages

## 🧪 Testes locais

Você pode abrir o projeto localmente com um navegador ou usar um servidor leve:

```bash
# Com Python 3
python -m http.server
