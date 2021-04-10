# gaze-com-classification

Esse repositório é uma réplica do repositório GazeCom, com resultados da classificação pelo algoritmo IBD-T.

Cada* pasta representa um vídeo do GazeCom. Dentro delas há:
  - Um arquivo com dados do rastreamento por usuário para o vídeo em formato arff.
  - Uma pasta correspondendo a cada arquivo mas identificada por um número. Dentro há:
    - journal.txt: é basicamente o arquivo correspondente em formato txt
    - reviewd.csv: ground truth
    - classification.csv: resultado da classificacção pelo IBD-T
    - mismatch.txt: listagem das classificações erradas
    - confusionMat.csv: matriz de confusão
    - <id_usuario>_<nome_do_vídeo>_origin: arquivo em branco só para identificar qual arquivo do GazeCom originou

* A exceção é a pasta 'métricas', que traz os resultados das métricas de cada classificação e o resultado geral. Dentro há uma pasta para cada vídeo, com um arquvio csv com as métricas por usuário e um png com a média para o vídeo.

