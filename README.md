# Metaforando-Webcam

Essa aplicação utiliza modelos de classificação de emoções gerado pelo keras. A classificação do modelo é apresentada em tempo real de acordo com a imagem recebida pela webcam em tempo real.
Para isto, o algoritmo precisa reconhecer cada rosto e classificar a expressão facial de acordo com o modelo.

Essa aplicação utiliza dois modelos de reconhecimentos faciais:
* OpenCV Haar Cascades  - https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html
* Face Recognition - https://pypi.org/project/face-recognition/

O modelo da biblioteca Face Recognition possui uma acurácia de 99.38% para reconhecimento de faces, mas é necessário a execução em um ambiente com GPU CUDA. Para ambientes que não possuem GPU CUDA, será utilizado o modelo de reconhecimento de rosto do OpenCV Haar Cascades, que mostrou resultados satisfatórios.  
