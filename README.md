# Projeto Final - EDA LEGO (Rebrickable)

PUC-SP - Especialização em IA - Big Data e Data Engineering

## Grupo
- Douglas Esteves
- Ricardo Calvoso
- Thiago Americo
- Vitor Gregory

## Sobre
Análise exploratória do catálogo LEGO da Rebrickable (sets, temas, peças, cores e minifigs) usando PySpark (RDD, Spark SQL e MLlib), pandas, numpy e seaborn.

## Perguntas
1. Quantos sets são lançados por ano?
2. Os sets ficaram mais complexos com o tempo?
3. Quais temas tem os sets maiores?
4. Quais as cores mais usadas? A lego usa mais cores hoje?
5. Cada tema tem cores características?
6. Quais categorias de peças são mais usadas? E as minifigs?
7. Dá pra descobrir o tema de um set pelas cores e peças (machine learning)?

## Principais resultados
- Os lançamentos foram de 110 sets em 1980 para 1.555 em 2026.
- A mediana de peças por set chegou a 245 em 2026.
- 5 cores somam 55% de todas as peças.
- A lego chegou a usar 113 cores em 2004 e depois cortou para ~60.
- A troca dos cinzas antigos pelos "bluish gray" em 2004 aparece nos dados.
- Cada tema tem suas cores: Star Wars cinza, Friends rosa/azul, Ninjago dourado.
- Um Random Forest do MLlib acertou o tema de 93% dos sets usando só cores e tipos de peça.

## Como rodar
Abrir o notebook no Google Colab e rodar todas as células. Os dados são baixados automaticamente do site da Rebrickable.
