
# Análise de Cancelamentos de Clientes

## Descrição do Projeto
Este projeto realiza uma análise exploratória de dados de cancelamentos de clientes, identificando padrões e causas que contribuem para a decisão de cancelamento. Ele utiliza Python e bibliotecas como **pandas** para manipulação de dados e oferece insights úteis para estratégias de retenção de clientes.

## Estrutura dos Dados
O arquivo `cancelamentos_sample.csv` contém as seguintes colunas:
- **CustomerID**: Identificador único do cliente.
- **idade**: Idade do cliente.
- **sexo**: Gênero do cliente (Male/Female).
- **tempo_como_cliente**: Tempo em meses como cliente.
- **frequencia_uso**: Frequência de uso mensal.
- **ligacoes_callcenter**: Número de chamadas para o call center.
- **dias_atraso**: Dias de atraso nos pagamentos.
- **assinatura**: Tipo de assinatura (Basic, Standard, Premium).
- **duracao_contrato**: Duração do contrato (Annual/Monthly).
- **total_gasto**: Valor total gasto pelo cliente.
- **meses_ultima_interacao**: Meses desde a última interação.
- **cancelou**: Indicador se o cliente cancelou o serviço (1 para cancelou, 0 para não).

## Passos do Notebook
1. **Importação e visualização dos dados**: Carregamento dos dados e verificação inicial.
2. **Limpeza dos dados**: Tratamento de valores ausentes e exclusão de colunas irrelevantes.
3. **Análise exploratória**: Identificação de tendências e correlações nos dados.
4. **Estudo das causas de cancelamento**: Avaliação de fatores que influenciam o cancelamento.

## Como Usar
1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale as bibliotecas necessárias:
   ```bash
   pip install pandas jupyter
   ```
3. Abra o arquivo `main.ipynb` em um ambiente Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
4. Execute as células sequencialmente para reproduzir a análise.

## Objetivos
O projeto visa:
- Compreender melhor o comportamento do cliente.
- Identificar fatores que aumentam o risco de cancelamento.
- Propor ações que possam melhorar a retenção de clientes.

## Autor
Este projeto foi desenvolvido como parte de um estudo sobre análise de dados utilizando Python. 
