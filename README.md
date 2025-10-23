🧩 CRUD com FastAPI, PostgreSQL e Streamlit

Este projeto demonstra a criação completa de um CRUD (Create, Read, Update, Delete) utilizando FastAPI, PostgreSQL e Streamlit, com ambiente totalmente containerizado via Docker.

⚙️ Tecnologias Principais

FastAPI → Backend moderno e performático para construção de APIs.

SQLAlchemy + Pydantic → ORM e validação de dados robusta e segura.

PostgreSQL → Banco de dados relacional escalável e confiável.

Streamlit → Interface web simples e intuitiva para interação com a API.

Docker Compose → Orquestração de containers (backend, frontend e banco).

🧠 Estrutura do Projeto
├── backend        # FastAPI + SQLAlchemy + Pydantic
├── frontend       # Streamlit + Requests + Pandas
├── docker-compose.yml
└── README.md

🚀 Execução

Instale e suba os containers:
docker-compose up -d --build

Frontend: http://localhost:8501

API Docs: http://localhost:8000/docs

☁️ Deploy (em construção)

Implementação planejada no AWS ECS (Fargate) para execução escalável de containers sem necessidade de gerenciar servidores.