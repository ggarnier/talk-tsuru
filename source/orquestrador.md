# Orquestrador

- ao executar um deploy, as units são distribuídas em diferentes nós, para aumentar a resiliência
- não existia kubernetes, foi criado docker-cluster
- units distribuídas para minimizar os efeitos em caso de falha em um node (se possível, em nodes de diferentes zonas)
