# API Django - Projeto desenvolvido com Django REST Framework

Este repositório contém uma API RESTful desenvolvida durante a formação **Django REST Framework: Crie APIs com Python**, da [Alura](https://www.alura.com.br). A aplicação tem como objetivo demonstrar a construção de APIs modernas utilizando boas práticas e os recursos avançados do Django REST Framework (DRF).

## 📚 Tecnologias e Conceitos Aplicados

Durante o desenvolvimento deste projeto, foram estudados e implementados os seguintes tópicos:

- **Django REST Framework (DRF)**: criação de endpoints RESTful
- **Validações**: personalizadas e automáticas com serializers
- **Paginação**: controle de quantidade de dados retornados por página
- **Filtros e busca**: parâmetros na URL para consultas dinâmicas
- **Versionamento de API**
- **Permissões e autenticação**: controle de acesso aos recursos
- **CORS (Cross-Origin Resource Sharing)**: configuração para acesso externo
- **Deploy na AWS**: hospedagem da API na nuvem
- **Documentação automática da API**: Swagger/OpenAPI
- **Testes unitários e de integração**: validação do comportamento da API

## 🔧 Como rodar o projeto localmente

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/api-django.git
cd api-django
```
# Crie um ambiente virtual e ative:
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows

# Instale as dependências:
pip install -r requirements.txt

# Execute as migrações:
python manage.py migrate

#Inicie o servidor:
python manage.py runserver

#🚀 Endpoints e Documentação:
/swagger/     # Swagger UI
/redoc/       # ReDoc UI

#✅ Testes
Para rodar os testes automatizados:
python manage.py test


#📦 Deploy
O deploy foi realizado utilizando os serviços da AWS. A aplicação está configurada para produção com segurança, CORS e performance.
