# Next.js - Consumo de API (Mock API)

Aplicação web em **Next.js (App Router)**, **TypeScript** e **Tailwind CSS** focada no consumo, exibição e gerenciamento dinâmico de produtos através de uma API simulada.

## 🚀 Funcionalidades

- **Listagem Dinâmica:** Exibição assíncrona de produtos com preço e nome.
- **CRUD Operacional:** Botões prontos para **Adicionar Novo Produto**, **Editar** e **Excluir**.
- **Componentização Reativa:** Uso de componentes modulares (`ProductCard`, `ProductList`) e feedback visual dinâmico de sucesso no clique do botão `AddToCartButton`.

---

## 🛠️ Tecnologias Utilizadas

- **Framework:** Next.js (App Router)
- **Linguagem:** TypeScript
- **Estilização:** Tailwind CSS
- **Ícones:** React Icons (`react-icons/fa`)

---

## 📁 Estrutura do Projeto

```text
src/app/
├── (components)/      # Componentes isolados (AddToCartButton, ProductCard, etc.)
├── api/                # Endpoints locais para a Mock API
├── product/            # Rotas dinâmicas da aplicação
├── layout.tsx          # Layout global
└── page.tsx            # Página inicial ("Nossos Produtos")


Demonstração
Interface do Usuário: Listagem limpa e organizada dos produtos.

(Mapeado no arquivo: Captura de tela de 2026-06-06 18-41-23.png)

Estrutura de Código: Lógica reativa implementada com React Hooks.

(Mapeado no arquivo: Captura de tela de 2026-06-06 18-40-41.jpg)

🔧 Como Executar
Clone o repositório:

Bash
   git clone <link-do-seu-repositorio>
Acesse a pasta e instale as dependências:

Bash
   cd nextjs-consumo-api-mock-api && npm install
Rode o projeto em modo de desenvolvimento:

Bash
   npm run dev
Acesse: http://localhost:3000