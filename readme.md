# 📚 Quiz Interativo para Programadores (HTML + CSS)
🔗 [Ver o site funcionando no GitHub Pages](https://tauanneres.github.io/Projeto-de-Estudo-em-HTML-Quiz-Interativo/)

Este projeto é um quiz interativo desenvolvido como um exercício prático para demonstrar o conhecimento e a aplicação de **HTML5** e **CSS3**.  

O objetivo principal foi construir uma página web completa, estruturada e estilizada, consolidando o aprendizado sobre **formulários, tags semânticas, tabelas e estilização visual**.

---

## 🚀 Tecnologias Utilizadas
- **HTML5** → Estrutura, conteúdo e semântica da página  
- **CSS3** → Estilização da interface, com tipografia, cores, layouts em flexbox e formatação de inputs, tabelas e listas  

---

## 🎨 Estilos Aplicados (CSS)
O arquivo `style.css` separa a camada de apresentação da estrutura HTML.  
Principais recursos aplicados:  

- **Fonte externa (Google Fonts)** → importada via `@import` para usar a tipografia *Cabin*  
- **Paleta de cores personalizada** → tons terrosos (`#331F19`, `#CCD595`, `#798252`) e neutros (`#f4f0EA`)  
- **Header e Footer estilizados** → cores de fundo, tipografia e espaçamentos ajustados  
- **Inputs e Formulários** → `input`, `select`, `textarea` e `button` com bordas arredondadas, placeholders coloridos, `accent-color` para rádio/checkbox  
- **Tabela de Pontuação** → uso de `border-collapse`, `<thead>`, `<tbody>` e `<tfoot>` estilizados  
- **Accordion de Respostas** (`<details>` e `<summary>`) com fundo, bordas e cursor customizados  
- **Listas Ordenadas** → margens e espaçamento internos ajustados  
- **Layout flexível** → uso de `flexbox` em `<main>` e `<section>` com `gap`  

---

## 📄 Estrutura do Código (HTML)

### 1. Cabeçalho (`<header>`)
- `<h1>` → Define o título principal do quiz  
- `<p>` → Breve descrição do projeto, com o nome do autor destacado em `<strong>`  

### 2. Conteúdo Principal (`<main>`)
Dividido em várias seções (`<section>`), cada uma com um propósito específico  

#### Seção de Introdução
- `<h2>` → Título da seção "Sobre esse quiz"  
- `<p>` → Explicação do propósito do quiz  
- `<strong>` e `<em>` → Ênfase visual e semântica  
- `<abbr>` → Mostra o significado completo de acrônimos como HTML e CSS ao passar o mouse  

#### Seções das Perguntas
Cada pergunta foi criada em sua própria `<section>`:  
- **Pergunta 1 (Múltipla escolha)** → `<input type="radio">`  
- **Pergunta 2 (Texto)** → `<input type="text">` com `placeholder`  
- **Pergunta 3 (Senha)** → `<input type="password">`  
- **Pergunta 4 (Data)** → `<input type="date">`  
- **Pergunta 5 (Checkbox)** → `<input type="checkbox">`  
- **Pergunta 6 (Upload de Arquivo)** → `<input type="file">`  
- **Pergunta 7 (Menu Suspenso)** → `<select>` e `<option>`  
- **Pergunta 8 (Imagem)** → `<figure>`, `<figcaption>` e `<img>`  

### 3. Seções Finais
- **Tabela de Pontuação** → Estruturada com `<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>` e `<td>`  
- **Lista de Respostas** → Utiliza `<details>` e `<summary>` para criar um accordion, exibindo respostas em `<ol>` e `<li>`  
- **Formulário de Feedback** → Criado com `<fieldset>`, `<legend>` e `<textarea>`  

### 4. Rodapé (`<footer>`)
- Link para o GitHub com `target="_blank"`  
- Informações de direitos autorais com `&copy;`  

---

## 💡 O que este projeto demonstra
✔️ Estrutura semântica do HTML5  
✔️ Estilização moderna com CSS3 (Google Fonts, cores, flexbox, formatação de inputs, tabelas e listas)  
✔️ Separação clara entre **estrutura (HTML)** e **apresentação (CSS)**  
✔️ Boas práticas de acessibilidade (uso de `alt`, `label` e `abbr`)  

---

## 👨‍💻 Autor
Desenvolvido por **Tauan Neres** 🚀
