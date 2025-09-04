# BMG-Technical-Challanger

# Backend do Big E-Commerce

Bem-vindo ao repositório do **backend do Big E-Commerce**, a espinha dorsal de um sistema de comércio eletrônico robusto e completo.  
Este projeto foi concebido para gerenciar toda a lógica de negócio, garantindo uma experiência fluida e segura para clientes e administradores.

---

## 🚀 Visão Geral do Projeto
Este backend é o **motor** por trás de uma plataforma de e-commerce preparada para **alto tráfego** e **funcionalidades críticas**.  
Foi arquitetado para suportar operações diárias e também eventos de grande escala, como a campanha de inauguração na **Black Friday**, que exige estabilidade e controle de concorrência.

---

## ⚙️ Funcionalidades Principais

### 🔑 Autenticação de Usuários
- Gerencia o acesso e as permissões de diferentes tipos de usuários.  
- Suporte a sessões ativas com distinção de perfis: **clientes** e **administradores**.  

### 📦 Catálogo de Produtos
- Controle total do catálogo pelos administradores.  
- Funcionalidades: **criar, atualizar, listar e excluir produtos**.  
- Gestão eficiente do inventário.  

### 🛒 Pedidos e Carrinho de Compras
- Clientes podem selecionar produtos, definir quantidades e adicionar ao carrinho.  
- Estoque atualizado automaticamente.  

### 💳 Pagamento
- Pedido confirmado apenas após a **conclusão do pagamento**.  
- Suporte a **Pix** e **Cartão de Crédito**.  

### 📜 Histórico e Acompanhamento de Pedidos
- Clientes podem acessar o **histórico completo** de compras.  
- Acompanhamento **em tempo real** do status dos pedidos.  

---

## 🏷️ Campanha Especial: Black Friday
Em preparação para o lançamento, o backend foi otimizado para lidar com **altíssimo volume de acessos** durante a Black Friday.

📌 **Oferta especial**:  
- A cada **1 hora**, serão disponibilizados **100 iPhones por apenas R$ 1,00**.  

O sistema foi projetado para garantir:  
- **Controle preciso de estoque**  
- **Concorrência segura**  
- **Experiência estável para milhares de clientes simultâneos**

---

## 📂 Estrutura de APIs

- **Auth API** → Autenticação e autorização de usuários.  
- **Catalog API** → Gestão de produtos e categorias.  
- **Orders API** → Carrinho e pedidos.  
- **Payments API** → Processamento e confirmação de pagamentos.  
- **History API** → Histórico e acompanhamento de pedidos.  
- **Orchestrator** → Orquestrar todo o fluxo e ações compensatórias.
- **FlashSale** → Venda de itens relampagos como o iphone.
- **Api Gateway** → Fluxo de autenticação e RateLimit das API

---

# Desafio Técnico

Você é o desenvolvedor responsável por viabilizar todo o back end de um E-COMMERCE.  

O sistema deve conter funcionalidades de autenticação de usuários, gestão de produtos, 

criação e acompanhamento de pedidos. 

 

1. Autenticação de usuários: Permitir que os usuários façam login e mantenham 

   suas sessões autenticadas (clientes e administradores) com distinção de  

   permissões. 

2. catálogo de produtos: Permitir ao administrador criar, atualizar, listar e excluir produtos. 

3. Pedidos/carrinho: Permitir ao cliente definir a quantidade do item, incluir um ou mais produtos e atualizar automaticamente o estoque. 

4. Pagamento: O pedido será confirmado após a conclusão do pagamento via pix ou cartão.  

5. Histórico e acompanhamento de pedidos: Os clientes poderão visualizar e acompanhar a situação dos seus pedidos 

 

Pontos importantes: 

O BIG E_COMMERCE irá lançar uma grande campanha de inauguração do seu site na próxima black friday. 

A cada 1 hora, será disponibilizada uma oferta de 100 iphones por apenas R$ 1,00. É isso mesmo: 

 

0h - 100 Iphones por R$ 1,00 

1h - +100 Iphones por R$ 1,00 

2h - +100 Iphones por R$ 1,00 

.. 

23h - +100 Iphones por R$ 1,00 

