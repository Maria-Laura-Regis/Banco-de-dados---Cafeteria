# Banco de Dados - Sistema de Cafeteria

## Funcionalidades Principais

### 🛒 **Gestão de Produtos**
- Cadastro de produtos com categorias (cafés, alimentos, merchandising, roupas)
- Controle de estoque, preços e fornecedores
- Imagens para catálogo (grande/pequena)

### 👥 **Cadastro de Clientes**
- Dados pessoais e endereço completo
- Sistema de login com níveis de acesso:
  - `admin` (gerenciamento total)
  - `user` (cliente comum)
  - `foreign` (clientes internacionais)

### 📦 **Sistema de Pedidos**
- Registro completo de pedidos
- Acompanhamento por status:
  1. Pagamento Confirmado
  2. Pagamento Pendente
  3. Cancelado pelo cliente
  4. Cancelado pela empresa
- Gestão de transportadoras e entregas

### 🏪 **Gestão de Franquias**
- Cadastro de lojas físicas
- Informações de gerentes e localização
- Controle de faturamento por unidade

### 🤝 **Relação com Fornecedores**
- Cadastro de empresas fornecedoras
- Contatos por departamento (financeiro, comercial, etc.)

## Estrutura do Banco
12 tabelas relacionadas com modelagem normalizada, incluindo:
- `clientes`, `produtos`, `pedidos`, `fornecedores`, `franquias`, `categorias`, etc.

> **Nota:** Este banco de dados foi desenvolvido como exercício do curso de **Desenvolvedor Web** do instrutor certificado Adobe **André Fontenelle**, representando um sistema completo para gestão de uma rede de cafeterias.
