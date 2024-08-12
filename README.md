# Análise e Precificação do Café
Este repositório contém um projeto que visa realizar uma análise exploratória e a precificação de sacas de café, utilizando técnicas de associação de variáveis e Information Values (IV) para extrair insights sobre a propensão de um café ser classificado como premium.
Entendimento do Negócio
O AgroTech Bank, especializado no agronegócio, busca melhorar a eficiência no processo de precificação das garantias oferecidas pelos clientes ao solicitar crédito. As garantias incluem diversos bens, sendo o café uma das mais comuns. O banco enfrenta desafios na avaliação do valor das sacas de café, o que pode resultar em perdas financeiras quando o café é vendido para cobrir dívidas.
### Objetivo do Projeto
O principal objetivo deste projeto é desenvolver uma Calculadora de Garantias para Sacas de Café, que permitirá ao banco:
Identificar quais características do café aumentam a probabilidade de ele ser classificado como premium.
Fornecer um valor aproximado da garantia e o valor máximo a ser liberado para empréstimo, com base nas informações fornecidas pelo usuário.
### Base de Dados
A base de dados utilizada contém informações sobre 862 tipos de café, com características que ajudam a determinar se o café é premium ou normal. As variáveis estão divididas em:
- Quantitativas: Medidas numéricas (ex: quantidade de sacas).
- Qualitativas: Características descritivas (ex: país de origem, tipo de variedade).

#### Análise do Information Value (IV)
O Information Value (IV) é utilizado para quantificar a capacidade de uma variável em diferenciar entre classes. Neste projeto, o IV foi aplicado para identificar preditores significativos da variável "café premium". As principais conclusões incluem:
País de Origem: Um forte preditor da classificação premium.
Tipo de Variedade: Também apresenta forte correlação com a classificação premium.
Faixa de Altitude: Contribui para a propensão de um café ser premium.
####Como Usar a Calculadora
A calculadora está disponível em formato Excel neste repositório. O usuário deve inserir as seguintes informações:
- País de Origem
- Tipo de Variedade
- Faixa de Altitude
- Quantidade de Sacas de 60kg

Com essas informações, a calculadora fornecerá:
- Valor Aproximado da Garantia
- Valor Máximo a ser Liberado para Empréstimo
#### Contribuições
Contribuições para melhorar a calculadora ou a análise são bem-vindas. Sinta-se à vontade para abrir issues ou pull requests.
####Licença
Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo Excel disponível neste repositório e as análises realizadas no código.
