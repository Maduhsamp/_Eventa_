🎯 Eventa — Event Management Platform

Aplicação web desenvolvida com Laravel para gerenciamento de eventos, permitindo que usuários criem, visualizem e participem de eventos.

💡 Projeto criado com foco em prática real e reforço de conhecimentos no ecossistema Laravel.

📸 Preview
<img width="1863" height="840" alt="image" src="https://github.com/user-attachments/assets/381c0b1c-0c0a-488c-a851-fdadf7a19ca8" />

🧠 Objetivo do Projeto

Este projeto foi desenvolvido com o objetivo de:

-Reforçar conhecimentos em Laravel
-Revisitar conceitos importantes de backend
-Aplicar boas práticas de desenvolvimento
-Simular um cenário real de aplicação web

⚙️ Funcionalidades
✅ Cadastro e autenticação de usuários
✅ Criação de eventos
✅ Edição e exclusão de eventos
✅ Participação em eventos
✅ Listagem e busca de eventos

🛠️ Tecnologias Utilizadas
-PHP
-Laravel
-MySQL
-Blade
-Bootstrap

💻 Ambiente de Desenvolvimento

O projeto foi desenvolvido utilizando:

-XAMPP (Apache + MySQL)
-phpMyAdmin para gerenciamento do banco de dados

🗄️ Banco de Dados
-Banco relacional com MySQL
-Estrutura gerenciada via Migrations do Laravel
-Relacionamentos utilizando Eloquent ORM

⚡ Como Rodar o Projeto

# Clone o repositório
git clone https://github.com/Maduhsamp/_Eventa_.git

# Acesse a pasta
cd eventa

# Instale as dependências
composer install

# Copie o arquivo de ambiente
cp .env.example .env

# Gere a chave da aplicação
php artisan key:generate

🔧 Configure o banco de dados no .env:

DB_DATABASE=nome_do_banco
DB_USERNAME=root
DB_PASSWORD=

# Rode as migrations
php artisan migrate

# Inicie o servidor
php artisan serve

Acesse a URL gerada

📚 Sobre o Projeto

Este projeto foi baseado em um curso gratuito de Laravel, porém com adaptações e melhorias próprias, com foco em aprofundamento prático e evolução técnica.

🚀 Aprendizados

Durante o desenvolvimento, trabalhei com:

-Estrutura MVC
-Eloquent ORM e relacionamentos
-Autenticação com Laravel
-Organização de código e boas práticas

✨ Considerações

Este é um projeto de estudo, mas construído com atenção a detalhes e boas práticas utilizadas no mercado.

“Transformando aprendizado em soluções reais.” 🚀
