# 📱 TelecomX

## 📃Sobre o Desafio
O desafio 'TelecomX' tem como objetivo analisar os dados de uma empresa de telecomunicações para identificar os principais fatores que contribuem para a evasão de clientes. 

## ✍️Desenvolvimento
No desenvolvimento desse projeto, realizei o processo de ETL (Extract, Transform and Load) dos dados, seguido da criação de visualizações analíticas que possibilitam compreender o perfil dos clientes que mais cancelam os serviços. A partir dos insights obtidos, elaborei recomendações estratégicas que podem ajudar a empresa a reter seus atuais clientes e atrair novos de forma mais eficaz.

## 📉Gráficos e Insights
![Gráfico Pizza](images/newplot(1).png)
Análise da distribuição de evasão através do gráfico de pizza. Entendemos que a evasão de cliente qualifica cerca de 27% dos clientes, um número bem expressivo e preocupante para a empresa.

![Gráfico Barras Subplots Geral 1](images/newplot(2).png)
![Gráfico Barras Subplots Geral 2](images/newplot(3).png)
Gráficos simples de barras através de subplots, todas as variáveis de forma geral.

![Gráfico Barras Subplots Churn x No Churn 2](images/newplot(4).png)
![Gráfico Barras Subplots Churn x No Churn 2](images/newplot(5).png)
Análise através de gráficos de barras e subplots, porém agora analisando dados de Churn e No Churn lado a lado (vermelho=Churn, azul=No Churn).

## 💡 Insights
Analisando os gráficos e ligando os fatos podemos concluir que:
- Clientes com contratos mensais e recentes (1 a 5 meses) possuem altíssimo índice de evasão, podendo ser indicativo de problemas na fase inicial de experiência com a empresa e também a flexibilidade do contrato mensal facilita a evasão.
- Clientes sem serviços adicionais tem maior tendência ao cancelamento (maior índice no suporte técnico).
- Pagamento por cheque físico também está associado a evasão, enquanto que os meios digitais não têm relação tão forte.
- Clientes sem dependentes ou parceiros tendem a cancelar mais, indicando que clientes que tenham com quem compartilhar seus benefícios tenham maior chances de permanecer seu contrato com a empresa.
- Clientes que menos gastam são o que mais cancelam, podendo ter relação com o tempo permanecido na empresa e também com o fato de não obter serviços adicionais.

## ✅ Recomendações
Após analisar os dados da empresa TelecomX e gerar visualizações que ajudaram a entender melhor o perfil dos clientes, seguem as principais recomendações para que a empresa consiga tratar seu problema com cancelamento e evasão de clientes.
- Procurando atingir clientes com parceiros e dependentes, ofererer planos familiares, que incluam serviços que atendem a toda a família.
- Incentivar a alteração dos contratos de atuais clientes para contratos de longo prazo e ofertar apenas contrato anuais ou bienais para novos clientes, se possível oferecendo benefícios para quem aderir esses tipos de contrato.
- Façam pacotes promocionais para adesão de serviços adicionais, se possível focar principalmente no serviço de suporte, pois estes fazem com que fidelize o cliente
- Incentivar atuais clientes a alterar sua forma de pagamento de cheque físico para algum modo de pagamento digital e ofertar apenas pagamentos digitais para novos clintes.
- Aumentar os tipos de pagamentos digitais, como PIX e boleto bancário, por exemplo.
- Aprimorar os primeiros meses de experiência do cliente com onboarding eficaz e suporte proativo nos primeiros meses de contrato, buscando assim maior fidelização.

## 🔨 Ferramentas Utilizadas
- **Google Collab**: para leitura do notebook.
- **Python**: para desenvolvimento do código do projeto.
- **Biblioteca Pandas**: para leitura e manipulação dos dados.
- **Biblioteca Matplotlib, Seaborn e Plotly**: para geração de gráficos e visualizações.
- **Biblioteca Requests**: para normalização de arquivo JSON
