# A3 da matéria Gestão e Qualidade de software com os professores Henrique Poyatos e Magda no semestre 1/2025

### Integrantes do projeto

- Arthur Lucas Evangelista Machado - RA 324146950
- Cicera Quaresma da Silva – RA 12524150398
- Iago Luiz Simplicio Serra - RA 1272320678
- Joyce Mendonça Paixão - RA 323212772
- Bruno Almeida Vilela - RA 323124929
- Ronildo Santos da Silva – RA 823226546
- Renato Pereira - RA 322441099

# ProjetoLimpo - Biblioteca Pessoal

## Sobre o Projeto

O **ProjetoLimpo** é um sistema web simples para gerenciamento de uma biblioteca pessoal. O sistema é uma refatoração do "ProjetoSujo" que é um CRUD feito em Java, criado no primeiro semestre de 2024.

### Algumas outras características do projeto
- Foi refatorado inteiramente em PHP para ser uma aplicação WEB. Mas também há HTML, CSS e JS.
- Utiliza o paradigma de orientação á objetos (POO)
- Padrão de arquitetura MVC (model-view-controler)
- Tem uma interface web simples e responsiva
- Aplicação dos princípios SOLID, DRY, KISS e YAGNI.

O projeto foi desenvolvido com foco em boas práticas de programação, utilizando os princípios do "Clean code" para torna-lo mais legivel, modular e facilitar a manutenção e atualização.

---

## Estrutura do projeto

<img src="https://github.com/user-attachments/assets/2c2d5b5c-d290-4947-806d-d56c60889750" alt="descrição" width="300"/>

---

## Funcionalidades

- Cadastro, listagem, e exclusão de gêneros literários
- Cadastro, listagem, edição e exclusão de livros físicos e e-books

---

## Pré-requisitos

- [XAMPP](https://www.apachefriends.org/pt_br/index.html) ou outro servidor local com suporte a PHP e MySQL
- PHP 8.0 ou superior
- Navegador web moderno
- IDE de sua escoha que rode PHP (recomendavel VS-code)

---

## Instalação e Execução

1. **Clone o repositório**
   ```bash
   git clone  https://github.com/Arthur-Lukas/A3-GQS.git
   
2. **Coloque a pasta do projeto no diretório do seu servidor local**
   - Exemplo para XAMPP:  
   - Copie a pasta `A3-GQS` para `C:\xampp\htdocs\`

3. **Inicie o servidor Apache e MySQL pelo XAMPP**

4. **Crie o banco de dados**
   - Acesse o [phpMyAdmin](http://localhost/phpmyadmin)
   - Crie um banco de dados chamado `db_biblioteca` 
   - Importe o script do banco de dados que está na pasta (script_sql) do repositório 

5. **Acesse o sistema**
   - No navegador, acesse:  
     [http://localhost/A3-GQS/index.html](http://localhost/A3-GQS/index.html)
     Se o projeto estiver em uma subpasta diferente, basta ajustar o caminho após o localhost/.

---

## Licença

Este projeto é livre para fins acadêmicos e de aprendizado.

