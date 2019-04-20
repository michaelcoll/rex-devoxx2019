### Synchro bi-directionnelle d'un legacy et d'une archi micro-services
- remplacement graduelle sur des features fixé avec Canary release
- le legacy et la nouvelle archi microservice doivent cohabiter elles modifient les même données
- pas de gestion de conflit le legacy a toujours raison
- CQRS et Event sourcing pour gérer la synchro