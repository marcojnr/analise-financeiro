## Analise Exploratória de Ações
#### Analise foi feita a partir dos dados coletados do yahoo para indicar oportunidades de mercado e  solucionar o problema ficticio abaixo.

##

#### Problema:
O preço de uma ação sempre flutua, mas existe uma relação entre o preço de fechamento e suas médias móveis?

Um analista quer mostrar como o estoque se moveria, ele tem 5 anos de dados de preços de estoque com ele, nos quais precisa realizar a análise.

#### Objetivo:
Encontre o possível movimento futurista das ações.

#### Arquivo:
**estatistica.ipynb**

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

##

### Veja o Projeto

Analise completa do projeto está no arquivo jupyter **estatistica.ipynb**

##### Para teste siga os comando abaixo.
1. Clonar o projeto 
   * Instalar git na maquina
   * Usar o comando (**git clone https://github.com/marcojnr/analise-financeiro.git**) 

2. Instalar os pacotes necesários
   * Abra o terminal e utilize o comando (**pip install -r requirements.txt**)
3. Agora inicie o teste rodando os notbooks

#

##### Veja a Analise Exploratória no arquivo **estatistica.ipynb**