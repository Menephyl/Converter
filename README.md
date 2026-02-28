# 💱 Converter

Conversor de moedas desenvolvido com **HTML, CSS e JavaScript puro**, com foco em **interface limpa**, **formatação monetária internacional** e **base preparada para integração com cotações em tempo real**.

<p align="center">
  <img alt="HTML" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img alt="CSS" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-242424?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
  <img alt="MIT" src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge">
</p>

---

## 📌 Sobre o projeto

O **Converter** é uma aplicação web criada para realizar conversões monetárias de forma visual e prática, partindo do **Real Brasileiro (BRL)** para outras moedas.

Além de entregar uma experiência simples para o usuário, o projeto também demonstra fundamentos importantes de desenvolvimento front-end, como:

* **manipulação do DOM**
* **captura de eventos**
* **formatação internacional de moedas**
* **organização de interface com CSS**
* **preparação para consumo de API externa**

---

## 🚀 Funcionalidades

* Entrada de valor em **Real Brasileiro**
* Conversão visual para:

  * **Dólar Americano (USD)**
  * **Euro (EUR)**
* Formatação monetária usando `Intl.NumberFormat`
* Interface objetiva e amigável
* Estrutura simples, ideal para estudos e evolução do projeto

---

## 🧠 Técnicas aplicadas

Este projeto evidencia conhecimentos práticos em:

### Front-end

* **HTML5 semântico** para estruturar a aplicação
* **CSS3** para estilização e responsividade básica
* **JavaScript Vanilla** para lógica de conversão e interação

### Manipulação de dados

* Uso de `querySelector` para acessar elementos da interface
* Uso de `addEventListener` para capturar ações do usuário
* Atualização dinâmica de conteúdo com `innerHTML`

### Internacionalização

* Uso da API nativa **`Intl.NumberFormat`**
  para exibir valores monetários no formato correto de cada moeda

### Integração externa

* Estrutura preparada para consumo de API de câmbio em tempo real
* Uso de `fetch()` para buscar cotações externas

---

## 🛠️ Estrutura do projeto

```bash
Converter/
│
├── assets/        # Imagens e recursos visuais
├── index.html     # Estrutura da interface
├── style.css      # Estilos da aplicação
├── script.js      # Lógica de conversão
└── README.md      # Documentação do projeto
```

---

## ▶️ Como executar

Como é um projeto front-end puro, basta:

1. Clonar este repositório:

```bash
git clone https://github.com/Menephyl/Converter.git
```

2. Acessar a pasta do projeto:

```bash
cd Converter
```

3. Abrir o arquivo `index.html` no navegador

---

## 💻 Demonstração técnica

A lógica central do projeto segue este fluxo:

1. O usuário digita um valor em **BRL**
2. O JavaScript captura esse valor
3. A moeda desejada é identificada pelo `select`
4. O resultado da conversão é calculado
5. Os valores são exibidos já formatados para o padrão monetário correspondente

Esse fluxo é excelente para praticar:

* lógica condicional
* eventos de clique
* seleção de elementos HTML
* atualização dinâmica da interface
* integração futura com APIs reais

---

## 📈 Possíveis melhorias

Algumas evoluções que podem deixar o projeto ainda mais profissional:

* Buscar cotações **100% em tempo real**
* Adicionar novas moedas, como:

  * Libra (GBP)
  * Bitcoin (BTC)
  * Peso Argentino (ARS)
* Melhorar a função de troca visual da moeda selecionada
* Exibir histórico ou horário da última cotação
* Implementar responsividade avançada para mobile
* Tratar erros de API com feedback visual ao usuário
* Separar melhor a lógica para facilitar manutenção

---

## 🎯 Objetivo do projeto

Este projeto é ideal para:

* fortalecer a base em **JavaScript**
* praticar **consumo de API**
* montar portfólio com projeto visual e funcional
* demonstrar evolução técnica em aplicações web

---

## 📚 Aprendizados demonstrados

Com este projeto, é possível demonstrar domínio em:

* estruturação de páginas web
* estilização moderna com CSS
* lógica de programação aplicada à interface
* consumo inicial de dados externos
* boas práticas de apresentação de projeto no GitHub

---

## 👨‍💻 Autor

Desenvolvido por **Yan Menephyl**
🔗 GitHub: [Menephyl](https://github.com/Menephyl)

---

## 📄 Licença

Este projeto está sob a licença **MIT**.

---

## ⭐ Destaque

Um projeto simples na proposta, mas muito eficiente para mostrar domínio de fundamentos essenciais do front-end moderno.

Se este repositório te ajudou ou se você curtiu a evolução do projeto, deixe uma **star**.
