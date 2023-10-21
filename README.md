# ETL - Utilizando IA Generativa para Mensagens de Marketing para Investidores

## Santander Dev Week 2023 (ETL com Python)

### Contexto

Você é um cientista de dados no Santander e recebeu a tarefa de envolver seus clientes de maneira mais personalizada. Seu objetivo é usar o poder da IA Generativa para criar mensagens de marketing personalizadas que serão entregues a cada cliente.

### Condições do Problema

Você recebeu duas planilhas em formato CSV:

**client.csv**: 
- id_cliente
- nome_cliente
- data_nascimento
- sexo
- endereco
- cidade
- CPF
- email
- telefone

**transaction.csv**: 
- id_cliente
- ativo
- quantidade (- para Venda; + para Compra)

Com esses dados, você irá organizar a carteira de cada cliente, determinando quais ativos ele possui. Após obter os dados dos clientes, você usará a API do ChatGPT (OpenAI) para gerar uma mensagem de marketing personalizada para cada cliente. Essa mensagem deve enfatizar a importância dos investimentos. Uma vez que a mensagem para cada cliente estiver pronta, você salvará uma tabela com o id do cliente, nome, email e mensagem.

### Instruções de Execução

1. Certifique-se de ter o Python instalado em seu ambiente de desenvolvimento.

2. Clone este repositório em seu ambiente local:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

