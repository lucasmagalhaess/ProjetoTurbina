Esse projeto consiste em uma análise de eficiência de turbinas eólicas, fazendo um comparativo entre a eficiência real e a eficiência ideal.

 Iniciei o projeto importando o pandas, o matplotlib.pyplot e o seaborn, com o objetivo de me auxiliar na análise.
 
  O segundo passo foi importar o banco de dados, fazendo a limpeza e reorganizando da melhor forma para fazer a análise. 
  
  O terceiro passo foi plotar o gráfico do comportamento da potência real das turbinas e o gráfico da potência ideal, para um futuro comparativo entre os dois. 
  
  O quarto paso foi criar um limite de 5% para mais e 5% para menos, tendo como base o gráfico de potência ideal, para traçar métricas de parâmetro e usar como comparativo.
  
  O quinto passo foi adicionar a lista de parâmetro ao dataframe. 
  
  O sexto e último passo, foi gerar um gráfico de calor baseado nos parâmetros calculados no quarto passo, podendo enxergar as turbinas que se encontram dentro da potência esperada para o seu funionamento, e analisar as demais que apresentam um rendimento abaixou do redimento esperado, acima do rendimento esperado e até mesmo rendimento nulo. 

  Conclusão: Através dessa análise, foi possível enxergar a baixa potência de algumas turbinas, a alta potência de outras e até mesmo algumas turbinas com potência nula. A análise permitiu idenficar cada uma delas e agrupar de acordo com seu desempenho, para uma análise mais detalhada no futuro. Eu tomaria a decisão de fazer uma análise específica para cada grupo, uma para tentar descobrir o baixo funcionamento de algumas turbinas (o que provavelmente pode ser uma falha no sensor ou o posicionamento das hélices), uma análise para as turbinas que estão com uma potência maior do que deveria (o que pode ser uma falha na sensibilidade do sensor ou em outro componente), e por fim, uma análise para as turbinas com potência nula.