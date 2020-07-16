# projeto_AM_AirQuality
Trabalho Final da disciplina de Aprendizado de Máquinas da UFF

Aqui nós temos a descrição de como foi separado os documentos deste repositório

1) /metodologia corresponde aos dois dados utilizadas para a elaboração do experimento. Dentro dela, temos
    1.1) Base Completa consiste na base completa do dataset Air Quality
    1.2) seasons base de treino para estações do ano
        1.2.1 autumn base de teste do período do outono e os 10 bases de testes aleatórias
        1.2.2 spring base de teste do período da primavera e os 10 bases de testes aleatórias
        1.2.3 summer base de teste do período do verão e os 10 bases de testes aleatórias
        1.2.4 winter base de teste do período do inverno e os 10 bases de testes aleatórias

2) /papers pasta com as principais referências para o experimento realizado, são elas
    *S. De Vito, E. Massera, M. Piga, L. Martinotto, G. Di Francia, On field calibration of an electronic nose for benzene estimation in an urban pollution monitoring scenario, Sensors and Actuators B Chemical, Volume 129, Issue 2, 22 February 2008, Pages 750-757, ISSN 0925-4005.
    *Saverio De Vito, Marco Piga, Luca Martinotto, Girolamo Di Francia, CO, NO2 and NOx urban pollution monitoring with on-field calibrated electronic nose by automatic bayesian   regularization, Sensors and Actuators B Chemical, Volume 143, Issue 1, 4 December 2009, Pages 182-191, ISSN 0925-4005.
    *Zhang, S et al, Cautionary Tales on Air-Quality Improvement in Beijing. Proceedings of the Royal Society A, Volume 473, No. 2205, Pages 20170457, 2017.

3) /resultados pasta com os resultados obtidos aplicando os algoritmos SimpleLinearRegression, LinearRegression, MultilayerPerceptron e SMOreg no WEKA.
    3.1) Base Completa prints dos resultados obtidos no WEKA
    3.2) seasons prints dos resultados obtidos no WEKA
