
# 🏨 Hotel Millane

Sistema web do Hotel Millane, desenvolvido em PHP, MySQL, HTML, CSS e Tailwind CSS.

## ✨ Sobre o projeto

O Hotel Millane é um site de hotel boutique com uma interface elegante e moderna.

O projeto permite visualizar as acomodações e cadastrar quartos, utilizando banco de dados MySQL.

## 🚀 Tecnologias utilizadas

- PHP
- MySQL
- HTML5
- CSS3
- Tailwind CSS
- JavaScript

## 📁 Estrutura do projeto

- `index.php` — página inicial.
- `assets/css/` — arquivos de estilização.
- `db/` — conexão com o banco de dados.
- `database/` — arquivo SQL do banco.
- `pages/` — páginas do sistema.
- `pages/partials/` — componentes reutilizáveis.

## ⚙️ Como executar localmente

1. Instale o XAMPP.
2. Inicie o Apache e o MySQL.
3. Coloque a pasta `hotel-millane` em `C:\xampp\htdocs\`.
4. Acesse o phpMyAdmin.
5. Crie ou importe o banco de dados `hotel_millane`.
6. Importe o arquivo `database/hotel_millane.sql`.
7. Confira as configurações de conexão em `db/conexao.php`.
8. Acesse pelo navegador:

http://localhost/hotel-millane/

## 🗄️ Banco de dados

Nome: `hotel_millane`

Tabela principal: `quartos`.

Campos previstos:
- id_quarto
- nome
- tipo
- capacidade
- preco_diaria
- descricao

## 👨‍💻 Desenvolvimento

Projeto desenvolvido para fins de aprendizado e prática de desenvolvimento web.
