# Seleção de features

Trabalharemos com o problema de classificação. Mais especificamente, o problema de classificação de reservas de hotéis. Queremos saber se nossos clientes vão manter ou cancelar uma reserva de hotel.

No contexto deste problema, o que vamos tentar analisar são as colunas do nosso conjunto de dados, as features. Desta forma, vamos tentar identificar e estudar formas de análise e automação da seleção das melhores features, ou seja, das melhores colunas para o nosso conjunto de dados. Vamos avaliar quais colunas são redundantes e quais realmente contribuem para a classificação e para o ajuste do nosso modelo de machine learning .

Vamos usar um notebook do Google Colab e trabalhar com a biblioteca Scikit-Learn. Além disso, vamos lidar com os dados abaixo:

[Hoteis](https://github.com/mths-andrade/features/blob/776b7b78e8d1a192a8293e7448300b63d9a94054/hotel.csv)

A ideia é manter o máximo de reservas possível. Sendo assim, vamos avaliar e tentar ajustar o modelo de Machine Learning para identificar quais clientes vão manter ou cancelar sua reserva. Dessa forma, podemos realizar, por exemplo, uma ação nos clientes que possivelmente vão cancelar a reserva.

Ajustar modelo de Machine Learning

Identificar clientes que vão manter ou cancelar a reserva

Ação para reter clientes

Temos uma série de informações sobre a reserva vinculada aos clientes do hotel, como número de adultos, número de crianças, números de finais de semana, dias e noites de finais de semana que as pessoas vão passar. No final do dataset temos nossa informação de interesse, a coluna booking_status. Isso especifica o status da reserva, basicamente, que pode ser 0 ou 1. Indicando se a pessoa manteve ou não a reserva depois de um tempo.
