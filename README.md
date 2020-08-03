## Motivo da existência

Este projeto simples existe para dar suporte as integrações necessárias no
desafio de implementação do sistema de pagamento da jornada dev eficiente.

A ideia foi implementar um tiquinho de caos para que as requisições fiquem
mais lentas ou que gerem algum erro inesperado. Isso pode ser legal para verificar
o comportamento do sistema no teste para verificar escalabilidade e resiliência.

## Como liberar o caos

Para liberar o caos você utilizar a variável ```enderecos-externos.caos-liberado```
do ```application.properties``` e definir o valor para ```true```.

 