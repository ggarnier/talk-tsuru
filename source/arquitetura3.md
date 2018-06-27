# Acessando uma app

minha-app.minha-cloud.com
    |
 router
  /  \
 [.] [.] app minha-app

- app em execução -> nodes rodando docker rodam units (containers); router fica na frente recebendo os requests, atuando como balanceador e distribuindo as requisições entre eles
