# Projeto Integrador

Este projeto é uma aplicação web desenvolvida com o framework Laravel, visando consolidar conhecimentos adquiridos ao longo do curso. O objetivo principal é proporcionar uma plataforma funcional que integre diversas tecnologias e boas práticas de desenvolvimento.

## 🚀 Tecnologias Utilizadas

- **Backend:** Laravel (PHP)
- **Frontend:** Blade Templates, Bootstrap
- **Banco de Dados:** MySQL
- **Gerenciamento de Dependências:** Composer, NPM
- **Controle de Versão:** Git
- **Ambiente de Desenvolvimento:** Docker (via `docker-compose.yml`)
- **Testes:** PHPUnit

## 📁 Estrutura do Projeto

- `app/`: Contém os arquivos principais da aplicação, incluindo Models, Controllers e Providers.
- `bootstrap/`: Arquivos de inicialização do framework.
- `config/`: Arquivos de configuração da aplicação.
- `database/`: Migrations, seeders e factories para o banco de dados.
- `public/`: Diretório público acessível via web, contendo o `index.php` e ativos como imagens, CSS e JS.
- `resources/`: Views Blade, arquivos de idioma e recursos brutos como SASS e JS.
- `routes/`: Definição das rotas da aplicação.
- `storage/`: Logs, cache e outros arquivos gerados pela aplicação.
- `tests/`: Testes automatizados utilizando PHPUnit.
- `docker-compose.yml`: Configuração para ambiente de desenvolvimento com Docker.
- `composer.json` & `package.json`: Gerenciamento de dependências PHP e JS, respectivamente.

## 🛠️ Instalação e Configuração

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/fisicopeculiar/Projeto-integrador.git
   cd Projeto-integrador
