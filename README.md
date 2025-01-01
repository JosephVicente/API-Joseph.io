# Joseph.io

Este repositório contém a API para um sistema de cursos online, que permite a criação, leitura, atualização e exclusão de cursos, alunos e inscrições. A API foi projetada para ser simples e fácil de usar, permitindo que administradores e alunos interajam com o sistema de forma eficiente.

First, Start and then run the development server:

```bash
npm i
npm run dev


## Stack

- Node.js
- TypeScript
- Express.js
- MongoDB
- REST Endpoints
  
- `Required`

          DB_URL = ""
          PORT = "8080"
          REDIS_URL = ""

          SMTP_HOST = "smtp.gmail.com"
          SMTP_PORT = "587"
          SMTP_SERVICE = "gmail"
          SMTP_MAIL = ""
          SMTP_PASSWORD = ""

          ACTIVATION_SECRET = ""
          ACCESS_TOKEN = ""
          REFRESH_TOKEN = ""

          CLOUD_NAME = ""
          CLOUD_API_KEY = ""
          CLOUD_SECRET_KEY = ""

## Visão Geral

A API Joseph.io oferece funcionalidades para gerenciar cursos, alunos e inscrições. Ela permite que administradores e alunos interajam com o sistema de forma programática, criando e gerenciando cursos, inscrevendo alunos, e permitindo que os alunos acompanhem seu progresso.

-- Notificações
sistema de notificações push e e-mails automáticos para lembrete de aulas.

## Autenticação

A API utiliza **autenticação via token JWT**. Para acessar os endpoints protegidos, você deve incluir o token JWT no cabeçalho da requisição.

### Como obter um token JWT

1. Envie uma requisição `POST` para o endpoint `/auth/login` com as credenciais do usuário.
2. O servidor retornará um token JWT que deve ser incluído nas requisições subsequentes.

### Implementações

# Cliente

Mobile [✅] Admin Dashboard ad Custumer
Web [❌]

- o repositorio sera publico em breve

**Exemplo de requisição para obter o token:**

Joseph.io é uma plataform que Oferece recursos inovadores para os educadores,
promovendo uma educação mais dinâmica e interativa.
Permite criar, organizar, gerenciar e disponibilizar cursos e treinamentos online
