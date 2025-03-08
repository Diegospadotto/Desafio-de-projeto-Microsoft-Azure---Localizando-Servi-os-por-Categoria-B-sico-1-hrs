# Desafio-de-projeto-Microsoft-Azure---Localizando-Servi-os-por-
Estrutura Profissional do Projeto
✅ Requisitos do Sistema
📌 Objetivo: Desenvolver um portal para localizar serviços do Microsoft Azure por categoria, permitindo filtragem avançada, exibição de preços e recomendações personalizadas.
📌 Funcionalidades:
•	Buscar serviços do Azure por categoria.
•	Exibir detalhes como descrição, preços e documentação.
•	Criar favoritos e salvar consultas.
•	Implementar autenticação e controle de acesso.
•	Expor API pública para consumo de terceiros.
•	CI/CD completo com Azure DevOps.
📌 Tecnologias Utilizadas:
•	Frontend: React.js + TypeScript + TailwindCSS
•	Backend: .NET 8 (Minimal APIs)
•	Banco de Dados: Azure Cosmos DB (NoSQL)
•	Autenticação: Azure Active Directory (AAD)
•	Infraestrutura: Azure Kubernetes Service (AKS) + Application Gateway
•	CI/CD: Azure DevOps + Terraform
 
📌 Arquitetura da Solução
🟢 Frontend (React.js + TypeScript)
🟠 API Gateway (Azure API Management)
🔵 Backend (ASP.NET Core Minimal API - .NET 8)
🟣 Banco de Dados (Azure Cosmos DB - NoSQL)
🔴 Autenticação (Azure AD B2C)
🟡 Deploy e Infraestrutura (Azure Kubernetes Service + Terraform)

📌 Implementação Completa
1️⃣ Backend - API RESTful com .NET 8
Criamos uma API otimizada, utilizando Minimal APIs para performance.
📌 Endpoints:
✔ GET /services → Retorna todas as categorias e serviços do Azure
✔ GET /services/{category} → Filtra serviços por categoria
✔ POST /favorites → Salva um serviço nos favoritos do usuário
