# Projeto Blog Django

## Descrição
Blog desenvolvido em Django com objetivo de aprendizado e prática de desenvolvimento web em Python. O projeto utiliza Docker para containerização e facilita a configuração do ambiente de desenvolvimento.

## Funcionalidades
- Criação, edição e exclusão de posts
- Sistema de autenticação de usuários
- Administração de conteúdo via Django Admin
- Configuração via variáveis de ambiente (`.env`)
- Suporte a containerização com Docker e Docker Compose

## Tecnologias Utilizadas
- **Backend:** Python, Django
- **Banco de Dados:** SQLite (desenvolvimento) / pode ser configurado para PostgreSQL
- **Containerização:** Docker, Docker Compose
- **Dependências:** gerenciadas via `requirements.txt`

## Estrutura do Projeto
projeto-blog-django/
│
├─ djangoapp/ # Aplicação Django principal
├─ scripts/ # Scripts auxiliares
├─ dotenv_files/ # Arquivos de configuração de ambiente
├─ Dockerfile # Configuração da imagem Docker
├─ docker-compose.yml # Orquestração de containers
├─ requirements.txt # Dependências do Python
└─ README.md

## Instalação e Execução

### 1. Clonar repositório
```bash
git clone https://github.com/johnysmn/projeto-blog-django.git
cd projeto-blog-django

2. Configurar ambiente

Copie e ajuste o arquivo de variáveis de ambiente:
cp dotenv_files/.env.example .env

3. Executar com Docker
docker-compose up --build

O projeto estará disponível em http://localhost:8000.

Contribuição

Crie uma branch para sua feature ou correção:
git checkout -b minha-feature

Faça commit das alterações:
git commit -m "Minha contribuição"

Envie para o repositório remoto:
git push origin minha-feature

Abra um Pull Request

Licença

Projeto de estudo, sem fins comerciais


