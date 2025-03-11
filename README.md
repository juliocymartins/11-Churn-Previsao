# Previsão de Churn

<img align="center" alt="Coding" width="400" src="https://propz.com.br/wp-content/uploads/2022/12/capa-6-jpg-1200x900.webp">

# Introdução
Este projeto foca na criação de um algoritmo preditivo para analisar dados de clientes e prever cancelamento de serviços, auxiliando na retenção de clientes. O conjunto de dados inclui informações sobre cancelamento de clientes, serviços assinados, detalhes da conta e dados demográficos. O objetivo é desenvolver modelos preditivos e ajudar a obter insights que possam aprimorar as estratégias de retenção.

### Churn
Termo em inglês que se refere a taxa de cancelamento de clientes dentro de um determinado período. No contexto de negócios, especialmente em serviços por assinatura, representa a porcentagem de clientes que deixaram de usar um serviço. Analisar o churn ajuda empresas a entenderem os motivos das saídas e criarem estratégias para melhorar a retenção de clientes.

# Sobre o Conjunto de Dados

### Contexto
"Preveja comportamentos para reter clientes. Você pode analisar todos os dados relevantes dos clientes e desenvolver programas focados na retenção de clientes." [IBM Sample Data Sets]

### O conjunto de dados inclui informações sobre:
- Clientes que cancelaram ou não nos últimos meses – essa informação está na coluna Churn.
- Serviços assinados por cada cliente – como telefone, múltiplas linhas, internet, segurança online, backup online, proteção de dispositivo, suporte técnico e streaming de TV e filmes.
- Informações da conta do cliente – tempo como cliente, tipo de contrato, método de pagamento, faturamento sem papel, cobranças mensais e cobranças totais.
- Dados demográficos dos clientes – gênero, faixa etária e se possuem parceiros ou dependentes.
  
Link para acessar o Dataset: [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

# Pacotes Necessários
- pandas
- matplotlib
- seaborn
- numpy
- scikit-learn 
- imbalanced-learn
- TensorFlow

# Como Usar
- Copie o repositório para sua máquina local.
- Certifique-se de que os dados brutos estão no mesmo diretório do notebook.
- Instale os pacotes necessários.
- Execute o Jupyter Notebook ou os scripts Python nos respectivos capítulos para rodar o código.

# Arquivos no Repositório
- clean_data: Contém os dados limpos.
- final_model: Contém o modelo final salvo como um arquivo pickle.
- raw_data: Contém os dados brutos.
- visualizations: Contém gráficos utilizados no projeto.
- churn_prediction.ipynb: Contém o arquivo do Jupyter Notebook para previsão de Churn.

# Autor
Julio Cesar Yamashita Martins

# E-mail
yamashitajulio@gmail.com
