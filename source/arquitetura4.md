# Deploy

- api gera img e envia pro registry; scheduler escolhe nodes para rodar as units; nodes baixam a img gerada do registry e rodam novos containers
- deploy sem downtime -> api consulta healthcheck e avisa router (novas units p/ adicionar, units velhas pra remover), depois remove units antigas. Em caso de erro em qualquer etapa, as novas units são removidas e o deploy cancelado; a app continua funcionando como antes
<img isidio>

api -> registry
 |
 |
node1 \
node2 |-> pools
node3 /
