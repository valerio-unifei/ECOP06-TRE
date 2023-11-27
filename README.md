# ECOP06-Trabalho-Final

No âmbito da análise de dados automobilísticos, a obtenção de conjuntos de dados autênticos e abrangentes muitas vezes se mostra desafiadora. Nesse contexto, o presente trabalho propõe explorar e analisar um conjunto de dados proveniente do jogo Forza Motorsport 7, desenvolvido pela Turn 10 Studios e publicado pela Microsoft Studios. 

Apesar da origem virtual dos dados, a falta de acesso a dados reais da Fórmula 1 ou de outros campeonatos em um nível tão detalhado torna essa alternativa uma fonte valiosa para análises automobilísticas.

É importante ressaltar que, embora provenha de um jogo, o Forza Motorsport 7 é reconhecido como um dos jogos de corrida mais realistas até a presente data, proporcionando uma experiência visual e física notável. Além disso, a coleta de dados ocorreu por meio de um controle de Xbox, o que adiciona um componente de variabilidade aos valores, podendo transitar de zero ao máximo em curtos intervalos de tempo.

Base de dados para o trabalho: [Telemetria Corrida Rio](https://github.com/valerio-unifei/ECOP06-Trabalho-Final/blob/main/dataset/telemetry-rio-5-laps.zip)

Fonte da base de dados: [Kaggle: Race Telemetry - Rio de Janeiro](https://www.kaggle.com/datasets/alexhexan/fm7-rio-de-janeiro-race-telemetry)

## Proposta

Desenvolva uma aplicação on-line com Streamlit que realiza a análise de dados de um sistema de telemetria de um veículo de corrida. 

O trabalho será avaliado em etapas de desenvolvimento. As notas serão atribuídas para cada etapa funcional. O programa deve ser modular em páginas para rodar cada etapa de forma isolada, pois se o programa não funcionar por erros, não receberá nenhuma nota.

As etapas de desenvolvimento:
1. Leitura e extração de informações da base de dados (2,5 pontos)
    - Nome e tipo de variável das colunas da tabela
    - Número de linhas por volta da corrida
    - Memória RAM consumida pela tabela
2. Mapa da pista de corrida (2,5 pontos)
    - Um mapa para cada volta da corrida
    - Posicionar o mapa sobre a cidade do Rio de Janeiro - RJ
    - Montar um gráfico 3D
3. Características do carro (2,5 pontos)
    - Tempo por volta
    - Gráficos de velocidade por volta
    - Gráficos de deslizamento máximo dos pneus por volta
4. Características do motor  (2,5 pontos)
    - Maior RPM por volta
    - Histograma de tempo de marcha por volta
    - Mapa de calor de torque e acelerador