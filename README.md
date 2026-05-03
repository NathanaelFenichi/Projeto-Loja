# Loja Simples — Processo Seletivo ESO

Projeto feito para o processo seletivo da ESO.  
A ideia aqui é mostrar o básico de um e-commerce: cadastro, login, catálogo, compra, devolução e visualização de usuários.
optei por ultilizar cores claras para o publico mais adulto e um desgn moderno e arredondado para o publico jovem, busquei mesclar os dois lados da moeda.
pelas linguagens usem o JQuery para integrar as APIs(o que estou recentemente aprendendo na faculdade), e como backend usei o php basico(aprendi no curso do senac), com mysql (HeidSql) como banco de dados.
é ultilizado uma Api gratuita de loja do fortinite https://fortnite-api.com/
 

---

## 🔧 funcionalidades

### 🛒 Loja
- Catálogo com paginação.
- Página de produto.
- Busca por nome.
- Perfil público e privado.

### 👤 Usuário
- Cadastro e login.
- Compra de item.
- Devolução de item.
- Lista de itens adquiridos.

### 🗄️ Banco
- MySQL funcionando com todas as tabelas necessárias.
- registro de usuarios cadastro, e registro de compras,

### 🌐 Front e Back
- HTML, CSS e JavaScript basico, estou aprendendo.
- PHP no back-end com as regras de compra, devolução, login, etc.
- integração com API funcionando junto dos filtros.
- docker funcionando

---

## 🚫 O que ainda não tem
- Testes automatizados.
- histórico de compras e devoluções feitas pelo usuario
- 

---

```text
processo-seletivo-eso/
│
├── index.php              # Ponto de entrada
├── mydb.sql               # banco de dados
│
├── backend/               # Lógica de negócio e APIs
│   ├── conecta.php        # Configuração da Base de Dados
│   ├── validaCadastro.php
│   ├── validaLogin.php
│   ├── comprar.php        # Lógica de transação
│   ├── devolver.php       # Lógica de estorno
│   ├── obtidos.php
│   ├── verifica_Posse.php
│   └── js/                # Scripts de interação
│
├── paginas/               # Interfaces de utilizador (Views)
│   ├── cadastro.php
│   ├── catalogo.php
│   ├── login.php
│   ├── perfil.php
│   └── ...
│
└── css/ & img/            # Estilos e Assets

````

## Como rodar localmente

### Requisitos
- docker
- PHP 8+
- MySQL 5.7+ ou MariaDB

### Passo a passo

1. Clone o repositório:
   ```bash
   git clone https://github.com/NathanaelFenichi/processo-seletivo-eso.git
2. tenha o Docker instalado em seu dispositivo (e funcionando).
3. clique com o botão direito sobre o arquivo "docker-composr.yml" e clique em compose Up
4. Abra no navegador:
Copiar código
http://localhost/processo-seletivo-eso/
e estara funcionando normalmente

### Observações diretas sobre o código
O funcionamento de sessão tem pontos a melhorar, a aplicação do docker foi feita em ultimo instante pode ter algum bug,
design e layout tem pontos a fixar, e a tela de usuarios tem o histŕico de compras a ser fixado, fora o cigo de usuario cadastrado tambêm

## Observações pessoais
Eu considerei fazer este projeto um belo de um desafio para quem nunca tinha feito um projeto, tenho a agradecer a oprtunidade do aprendizado, a revisão de meus conhecimentos, apesar de tudo estou satisfeito com o meu resultado, reconheço que tem muitos pontos de melhoria, e aprimoramento tanto no front-end quanto no back-end.

## 📞 Contato
Email: nathanael.essantos@gmail.com
