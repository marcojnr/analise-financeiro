## Analise Exploratória de Ações
#### Analise foi feita a partir dos dados coletados do yahoo para indicar oportunidades de mercado e  solucionar o problema ficticio abaixo.

##

#### Problema:
O preço de uma ação sempre flutua, mas existe uma relação entre o preço de fechamento e suas médias móveis?

Um analista quer mostrar como o estoque se moveria, ele tem 5 anos de dados de preços de estoque com ele, nos quais precisa realizar a análise.

#### Objetivo:
Encontre o possível movimento futurista das ações.

##

#### Passos:
   * Obter dados de 5 anos do pacote Finance com simbolo 'GOOG'.
   * Criar 50DMA e 200DMA.
   * Gráfico do preço atual.
   * Ajuste o Statsmodel OLS para encontrar os melhores recursos possíveis


##

| Variaveis | Descrição | 
| :---         |     :---        
| Date   | Data dos valores     
| Open     |   Preço de abertura do estoque naquele dia     
| High   | Preço máximo do stoke naquele dia     
| Low   | Preço minimo do stoke naquele dia     
| Close   | preço de fechamento do estoque naquele dia    
| Volume   | Total de Volume naquele dia