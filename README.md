# Inteligência de Negócios - Trabalho 3
Sistemas de recomendação por meio de aprendizado não-supervisionado utilizando algoritmos de Clusterização

## Base de Dados
- Base de dados escolhida: [Kaggle](https://www.kaggle.com/datasets/niharika41298/nutrition-details-for-most-common-foods/code)
- Base de dados tratada: [Google Planilhas](https://docs.google.com/spreadsheets/d/1-nJOtXDaHU-WekuMImalBGv_LQBZ3n-whrviVCkw6F4/edit?usp=sharing)

## Melhores Coeficiente de Silhuetas
| Algoritmo | CS(i) | Clusters |
| --- | :---: | :---: |
| **k-Means** | 0.371 | 3 |
| **Fuzzy** | 0.396 | 7 |
| **k-Medoids** | 0.320 | 9 |
| **Hierárquico (Manhattan)** | 0.722 | 2 |

## Respectivos Gráficos

![Imagem - gráfico do k-Means](https://github.com/JoaoAugusto2020/IN-Trab3/blob/main/imgs/k-Means%20(3%20Clusters).png "k-Means")
![Imagem - gráfico do Fuzzy](https://github.com/JoaoAugusto2020/IN-Trab3/blob/main/imgs/Fuzzy%20(7%20Clusters).png "Fuzzy")
![Imagem - gráfico do k-Medoids](https://github.com/JoaoAugusto2020/IN-Trab3/blob/main/imgs/k-Medoids%20(9%20Clusters).png "k-Medoids")
![Imagem - gráfico do Hierárquico](https://github.com/JoaoAugusto2020/IN-Trab3/blob/main/imgs/Hierárquico-Manhattan%20(2%20Clusters).png "Hierárquico")
