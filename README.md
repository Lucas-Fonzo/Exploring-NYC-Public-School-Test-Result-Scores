# Projeto: Análise de Desempenho Escolar em Nova York

![New York City schoolbus](schoolbus.jpg)

Foto por [Jannis Lucas](https://unsplash.com/@jannis_lucas) em [Unsplash](https://unsplash.com).

## Introdução
Todo ano, estudantes do ensino médio dos Estados Unidos realizam o SAT, um teste padronizado destinado a medir habilidades de leitura, matemática e escrita. Com três seções - leitura, matemática e escrita - cada uma com uma **pontuação máxima de 800 pontos**, esses testes são extremamente importantes tanto para os estudantes quanto para as faculdades, desempenhando um papel crucial no processo de admissão.

A análise do desempenho das escolas é fundamental para uma variedade de partes interessadas, incluindo profissionais de política e educação, pesquisadores, governo e até mesmo pais que estão considerando em qual escola seus filhos devem estudar.

Este projeto visa responder três perguntas-chave sobre o desempenho do SAT nas escolas públicas da cidade de Nova York (NYC), utilizando o conjunto de dados fornecido.

## Conjunto de Dados
O conjunto de dados fornecido, chamado `schools.csv`, contém informações sobre o desempenho das escolas públicas de NYC no SAT. Ele inclui variáveis como nome da escola, média das pontuações de matemática, leitura e escrita, bem como o bairro em que cada escola está localizada.

## Questões Chave

### 1. Quais escolas de NYC têm os melhores resultados em matemática?
Para determinar as escolas com os melhores resultados em matemática, consideramos que os melhores resultados são aqueles que representam pelo menos 80% da **pontuação máxima possível de 800** em matemática. 

### 2. Quais são as 10 melhores escolas com base nas pontuações combinadas do SAT?
Para responder a esta pergunta, calculamos uma pontuação combinada do SAT para cada escola, somando as pontuações médias de matemática, leitura e escrita. Em seguida, classificamos as escolas com base nessa pontuação combinada e selecionamos as 10 melhores.

### 3. Qual bairro tem o maior desvio padrão na pontuação combinada do SAT?
Para identificar o bairro com o maior desvio padrão nas pontuações combinadas do SAT, agrupamos as escolas por bairro e calculamos a média, desvio padrão e número de escolas para cada bairro. O bairro com o maior desvio padrão indica a maior variabilidade nas pontuações do SAT entre suas escolas.

## Análise Exploratória de Dados (EDA)
Este projeto emprega várias técnicas de Análise Exploratória de Dados (EDA), incluindo:

- **Filtragem de Dados**: Para identificar escolas com os melhores resultados em matemática e as 10 melhores escolas com base nas pontuações combinadas do SAT.
  
- **Agregação de Dados**: Agrupando as escolas por bairro e calculando estatísticas resumidas, como média e desvio padrão, para cada bairro.

- **Visualização de Dados**: Embora não tenhamos usado visualizações neste exemplo específico, a EDA muitas vezes inclui gráficos e visualizações para entender melhor os dados.

Ao realizar essa análise, podemos obter insights valiosos sobre o desempenho das escolas em NYC, identificando áreas de sucesso e áreas que podem precisar de mais apoio ou recursos.

Este projeto fornece uma visão abrangente do desempenho do SAT nas escolas públicas de NYC, destacando a importância da análise de dados na tomada de decisões educacionais e políticas.
