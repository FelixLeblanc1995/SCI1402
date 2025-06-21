# SCI1402 - Analyse de la performance de l'analyse technique

## Description
Dans ce projet, nous utilisons des données journalières provenant de plusieurs entreprises cotées sur différentes places boursières à travers le monde, dans le but d’évaluer la capacité des indicateurs techniques à générer des profits excédentaires.

Pour ce faire, nous élaborons des stratégies de trading fondées sur des indicateurs techniques populaires, puis comparons leurs performances à celle d’une stratégie de type buy and hold, en tenant compte des frais de transaction.

Par ailleurs, des tests d’hypothèses seront appliqués afin de mieux comprendre la nature des séries temporelles étudiées. Cette analyse permettra d’évaluer le caractère aléatoire des rendements et de renforcer la robustesse des conclusions tirées de l’étude.

## Données 
Pour réaliser cette analyse, j’utiliserai des données journalières sur les prix d’actions de diverses entreprises à l’échelle mondiale, provenant de la plateforme Kaggle. La base de données couvre la période du 3 janvier 2000 au 8 avril 2025, soit un total de 6 353 journées de cotation.

L’étude portera sur l’évaluation de plusieurs stratégies de trading fondées sur l’analyse technique, qui seront comparées à une stratégie passive de type buy and hold. Cette comparaison sera effectuée sur une sélection de 20 entreprises issues de secteurs d’activité et de pays variés.

Lien URL : https://www.kaggle.com/datasets/nelgiriyewithana/world-stock-prices-daily-updating

## Résultats
Les résultats démontrent qu’il ne serait pas possible de réaliser un rendement excédentaire en utilisant des stratégies se basant sur les prix passés, et ce par rapport à la stratégie de référence. Ceci est vrai aussi lorsqu'on étend l'analyse aux industries et aux pays. 
De plus, les test d'hypothèses permettent de conclure que toutes les séries de prix sont stationnaires, ce qui veut dire que le lag de la valeur ne contient alors pas d’information utile pour prédire le changement dans la variable analysée et donc qu’il est impossible de se baser sur les prix pour prédire les prix futurs, ce qui suit la logique des tests de performance.
