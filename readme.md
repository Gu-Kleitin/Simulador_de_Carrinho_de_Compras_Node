# 🛒 Simulador de Carrinho de Compras 🛍️
### Desafio: Formação Node.js - Digital Innovation One (DIO)

<p align="center">
  <img alt="Node.js Badge" src="https://img.shields.io/badge/Node.js-20.x-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img alt="JavaScript Badge" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img alt="Status do Projeto" src="https://img.shields.io/badge/STATUS-CONCLUÍDO-BRIGHTGREEN?style=for-the-badge"/>
</p>

---

## 📄 Sobre o Projeto

Este projeto é um simulador de carrinho de compras de e-commerce (inspirado na Shopee), desenvolvido como parte do desafio prático da **Formação Node.js** da DIO.

O foco é estritamente na **lógica de *backend***, executada em ambiente de linha de comando (terminal). O sistema é modularizado, utilizando **Programação Orientada a Objetos (POO)** para gerenciar de forma eficiente a adição, remoção e cálculo de itens no carrinho, conforme o tempo for passando eu tendo disponibilidade, irei melhorar algumas coisas (como atualizar o valor total do carrinho após remover itens), ou adicionar um front-end no projeto

### 🎯 Estrutura e Objetivos

* **Tecnologia Central:** Node.js (v20.10.0).
* **Modularização:** Código dividido em módulos com responsabilidades claras (definidas nas pastas `src/services`).
* **POO:** Uso de Classes para modelar o domínio (`Cart`, `Item`).

### 📂 Estrutura de Pastas

A organização do código segue um padrão limpo e modular:

```

src/
├── services/
│   ├── cart.js    // ⬅️ Lógica principal do carrinho (métodos de manipulação e cálculo).
│   └── itens.js   // ⬅️ Definição dos itens.
└── index.js       // ⬅️ Controlador que executa as funcionalidades.

````

---

## 🚀 Funcionalidades Implementadas

O projeto implementa o ciclo de vida completo de uma compra em um carrinho:

* **`addItem(item, quantity)`:** Adiciona um produto e sua quantidade ao carrinho.
* **`removeItem(item)`:** Remove **todas** as unidades de um produto específico.
* **`deleteItem(item)`:** Remove **uma unidade** de um produto, sem retirá-lo totalmente do carrinho.
* **`displayCart()`:** Exibe uma lista formatada dos produtos, quantidades, subtotais e o total geral.
* **`calculateTotal()`:** Retorna o valor final de todos os itens no carrinho.

---

A saída do terminal demonstrará as operações de adicionar/remover itens e o cálculo final do carrinho.

-----
