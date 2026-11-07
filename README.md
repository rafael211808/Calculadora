# 🧮 Calculadora Web Simples

Uma aplicação de calculadora web interativa desenvolvida com **HTML5**, **CSS3** e **JavaScript vanilla**, focada em estudos de manipulação do DOM e persistência de dados local.

---

## 🚀 Funcionalidades

* **Operações Básicas:** Soma (`+`), Subtração (`-`), Multiplicação (`*`) e Divisão (`/`).
* **Cálculo Dinâmico:** Avaliação das expressões matemáticas ao clicar no botão `=` e exibição imediata do resultado na tela.[cite: 12]
* **Limpeza de Tela (`Clear`):** Botão para reiniciar o cálculo e limpar o histórico armazenado.[cite: 12]
* **Persistência de Dados (`localStorage`):** O cálculo atual é automaticamente salvo no navegador, permitindo que o estado anterior seja mantido mesmo após atualizar a página.[cite: 12, 13]

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura dos botões, visor de resultado e inclusão dos scripts.[cite: 12]
* **CSS3:** Estilização visual inspirada em calculadoras padrão (botões arredondados em tons de cinza e laranja, tema escuro).[cite: 14]
* **JavaScript:** Lógica de atualização de expressão, manipulação do DOM e gerenciamento do `localStorage`.[cite: 12, 13]

---

## 📂 Estrutura de Arquivos

```text
Calculadora/
│
├── calculator.html       # Estrutura principal da calculadora e eventos dos botões
│
├── styles/
│   └── calculator.css    # Estilização visual dos botões e do visor
│
└── scripts/
    └── calculator.js     # Lógica do cálculo e persistência no localStorage
```

## ⚠️ Nota de Aprendizado

* **Observação:** Este projeto utiliza a função nativa eval() do JavaScript para calcular o resultado das expressões. Essa abordagem foi utilizada estritamente para fins educacionais e de aprendizado. Em projetos de produção real, é recomendado evitar o uso de eval() devido a riscos potenciais de segurança.[cite: 12]
