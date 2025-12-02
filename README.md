# Estimador-de-precos

Objetivo da Aplicação: 
A Uber oferece diferentes categorias de serviço, cada uma com um preço distinto baseado em 
múltiplos fatores, como distância, tempo estimado, demanda e condições de tráfego. O desafio é criar 
modelos de Machine Learning capazes de prever o preço estimado das corridas para três categorias: 
UberX, Uber Comfort e Uber Black. 
Como extra, podem utilizar dados de outras empresas como 99 ou transporte público para estimar a 
forma mais barata de chegar no local desejado. Gerando assim um estimador dentre vários serviços


Desafio: 
Desenvolver modelos de Machine Learning que possam prever o campo `Price` da tabela 
`rideestimative`, utilizando como entrada: - As características da corrida registradas nas tabelas ride (sem utilizar o campo `Price` dessa 
tabela), rideestimative e product. - As estimativas de preços de outras categorias de serviço como variáveis auxiliares.
