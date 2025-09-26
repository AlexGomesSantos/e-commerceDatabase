# e-commerceDatabase
E-commerce Database project

## 📌 Descrição
Este projeto implementa a modelagem lógica de um banco de dados para um cenário de e-commerce, com suporte a:
- Clientes PF e PJ (CPF e CNPJ exclusivos)
- Produtos, fornecedores e vendedores
- Vários métodos de pagamento por cliente
- Pedidos com itens, entregas e status
- Relacionamentos N:N (produtos ↔ fornecedores, produtos ↔ vendedores)

## 🗂 Estrutura
- schema.sql → Criação do banco (`ecommerce`) e inserção de dados de teste
- queries.sql → Consultas SQL de exemplo (JOIN, GROUP BY, HAVING, ORDER BY, atributos derivados)

## 🚀 Como executar
1. Clone este repositório
2. Crie o schema em um MySQL 8+:
   ```bash
   mysql -u usuario -p < schema.sql
