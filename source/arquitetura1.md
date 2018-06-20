# Arquitetura

## Conceitos

- **nós**: máquinas rodando Docker, responsáveis por executar as units (containers) das aplicações
- **pools**: conjuntos de nós, isolam recursos por grupo/área/projeto

  pool1  | pool2
[] [] [] |
         | [] []
 [] []   |
