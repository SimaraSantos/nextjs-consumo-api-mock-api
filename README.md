# Catálogo Dinâmico de Produtos - Next.js & TypeScript

Aplicação web moderna para listagem e gerenciamento dinâmico de produtos, consumindo rotas de API internas e renderizando dados com foco em performance e tipagem estrita.

## 🔗 Links Úteis
- 🚀 [Acesse o Projeto Online](https://nextjs-consumo-api-mock-dpm71doxe-simarasantos-projects.vercel.app/)
- 💻 [Acesse o Projeto Online](https://nextjs-consumo-api-mock-api-git-te-5fcc16-simarasantos-projects.vercel.app/)

## 🛠️ Tecnologias Utilizadas
- **Framework:** Next.js 15 (App Router)
- **Linguagem:** TypeScript
- **Estilização:** Tailwind CSS
- **Hospedagem & CI/CD:** Vercel

## 🧠 Desafios Técnicos Solucionados
Durante o desenvolvimento e o deploy desta aplicação, enfrentei e resolvi desafios reais de engenharia de software:
1. **Gerenciamento de Ambientes (Variáveis de Ambiente):** Configuração da variável `NEXT_PUBLIC_API_BASE_URL` na Vercel para isolar o ambiente de desenvolvimento local (`localhost`) do ambiente de produção em nuvem.
2. **Segurança de Mídias Externas:** Implementação de políticas de controle de segurança via `remotePatterns` no arquivo `next.config.ts` para permitir o consumo seguro de imagens externas do Unsplash.
3. **Conformidade de Segurança (CI/CD):** Resolução de vulnerabilidades de pacotes na esteira de build da Vercel através da atualização e alinhamento estrito de dependências do ecossistema React/Next.js.


📄 Descrição Geral
Uma aplicação web moderna desenvolvida para simular um fluxo real de e-commerce ou catálogo. O sistema realiza o consumo de rotas dinâmicas de API e renderização de dados no lado do servidor, garantindo performance e uma interface fluida.
Gerenciamento de Infraestrutura e Ambientes: Configuração de variáveis de ambiente globais (NEXT_PUBLIC_API_BASE_URL) para isolar com segurança a comunicação com as APIs entre os ambientes de desenvolvimento local e produção na nuvem.

Segurança e Otimização de Mídias Externas: Implementação de políticas de controle de segurança de imagens nativas do Next.js via remotePatterns no arquivo next.config.ts para permitir o consumo seguro de mídias externas do Unsplash.

Correção de Vulnerabilidades: Ajuste fino e atualização de dependências críticas de pacotes diretamente no gerenciador de pacotes para cumprir requisitos rígidos de conformidade e segurança na esteira de build (CI/CD).


# Next.js - Consumo de API (Mock API)

Aplicação web em **Next.js (App Router)**, **TypeScript** e **Tailwind CSS** focada no consumo, exibição e gerenciamento dinâmico de produtos através de uma API simulada.

##  Funcionalidades

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

