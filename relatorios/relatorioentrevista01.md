# Relatório – Sistema de Pedidos para Loja de Bebidas

## 1. Introdução
A modernização dos processos comerciais é essencial para empresas que buscam maior eficiência e competitividade. No caso da loja de bebidas, o controle manual de pedidos e vendas tem gerado problemas como erros de registro, falta de organização e dificuldade em acompanhar clientes inadimplentes.

O sistema proposto tem como objetivo automatizar o gerenciamento de pedidos, cadastro de clientes e produtos, controle de estoque e geração de relatórios gerenciais. Dessa forma, busca-se reduzir falhas operacionais, otimizar o tempo dos funcionários e melhorar o atendimento ao cliente.

## 2. Problema
Atualmente, o controle de vendas é feito manualmente em cadernos, o que ocasiona:

- Erros frequentes em pedidos e cálculos de valores  
- Falta de clareza na entrada e saída de dinheiro  
- Dificuldade em identificar clientes inadimplentes  
- Ausência de relatórios para apoiar decisões de compra e reposição de estoque  
- Falta de histórico consolidado de clientes e produtos  

## 3. Objetivo
O sistema tem como proposta:

- Automatizar o processo de registro de pedidos e vendas  
- Reduzir erros e inconsistências nos registros  
- Facilitar a gestão de clientes, produtos e estoque  
- Melhorar a eficiência operacional e o atendimento ao cliente  
- Fornecer relatórios gerenciais para apoiar a tomada de decisão  
- Garantir segurança e integridade dos dados  

## 4. Escopo

### Cadastro de Clientes
- Nome completo  
- CPF  
- Celular  
- Endereço  
- Email  
- Histórico de compras  

### Cadastro de Produtos
- Nome  
- Quantidade em estoque  
- Data de validade  
- Valor unitário  
- Categoria (ex.: cerveja, refrigerante, destilado)  
- Fornecedor  

### Registro de Pedidos
- Cliente vinculado (já cadastrado)  
- Produtos selecionados e quantidade  
- Forma de pagamento (PIX, cartão, dinheiro)  
- Valor total do pedido  
- Status do pagamento (pago, em débito)  
- Data e hora do pedido  

### Relatórios
- Clientes inadimplentes e valores em aberto  
- Vendas por período (diário, semanal, mensal)  
- Produtos mais vendidos  
- Estoque disponível e alertas de baixa quantidade  
- Comparativo de vendas por categoria de produto  
- Histórico de compras por cliente  

## 5. Especificação de Requisitos

### Requisitos Funcionais
- **RF01** – Cadastrar cliente  
- **RF02** – Cadastrar produto  
- **RF03** – Registrar pedido vinculando cliente e produtos  
- **RF04** – Editar dados de clientes, produtos e pedidos  
- **RF05** – Gerar relatórios de vendas, estoque e inadimplência  
- **RF06** – Consultar histórico de pedidos por cliente  
- **RF07** – Emitir alerta de estoque baixo  
- **RF08** – Controlar status de pagamento (pago, em débito)  
- **RF09** – Exportar relatórios em PDF/Excel  
- **RF10** – Pesquisar clientes e produtos por filtros (nome, categoria, período)  

### Requisitos Não Funcionais

#### Eficiência
- Tempo de resposta < 3 segundos  
- Sincronização de dados em até 10 segundos  

#### Usabilidade
- Interface intuitiva e de fácil aprendizado  
- Usuário apto a operar o sistema após até 2 horas de treinamento  
- Operações comuns realizadas em menos de 30 segundos  

#### Segurança
- Autenticação por login e senha (mínimo 8 caracteres)  
- Criptografia de senhas e dados sensíveis  
- Controle de acesso por perfil (administrador, vendedor)  

#### Disponibilidade
- Sistema disponível 99% do tempo  
- Recuperação de dados em caso de falha  

#### Integridade
- Garantia de consistência entre pedidos, clientes e estoque  
- Backup automático diário  

## 6. Arquitetura Proposta
- **Frontend**: Interface web responsiva, acessível em computadores e dispositivos móveis  
- **Backend**: API REST desenvolvida em linguagem moderna (ex.: Java, Python ou Node.js)  
- **Banco de Dados**: Relacional (ex.: MySQL ou PostgreSQL) para garantir integridade e consistência  
- **Segurança**: Autenticação JWT, criptografia de senhas e controle de acesso por perfil  
- **Infraestrutura**: Hospedagem em servidor local ou nuvem (AWS, Azure, GCP)  

## 7. Benefícios Esperados
- Redução de erros em pedidos e cálculos financeiros  
- Maior controle sobre clientes inadimplentes  
- Organização eficiente do estoque e reposição preventiva  
- Agilidade no atendimento ao cliente  
- Apoio à gestão com relatórios claros e objetivos  
- Segurança e confiabilidade dos dados  
- Escalabilidade para crescimento da loja  

## 8. Considerações Finais
O sistema de pedidos para a loja de bebidas proporcionará maior eficiência operacional, segurança e organização. Além disso, permitirá que gestores tenham informações estratégicas para tomada de decisão, reduzindo falhas e aumentando a competitividade da empresa.
