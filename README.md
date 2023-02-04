# desafio-BigBoost-BigDataCorp
## Desafio
A arquitetura poderia ser composta por vários microserviços, cada um responsável por uma parte específica da solução. Por exemplo:

Microserviço de disponibilidade de ingressos: responsável por verificar e atualizar a disponibilidade de ingressos em tempo real.

Microserviço de fila de espera: responsável por gerenciar a fila de espera para a compra de ingressos, garantindo que todas as solicitações sejam atendidas de maneira equilibrada e justa.

Microserviço de venda de ingressos: responsável por finalizar a venda de ingressos, verificando primeiro a disponibilidade de ingressos com o microserviço de disponibilidade.

Todos os microserviços poderiam se comunicar entre si através de uma API REST, garantindo que todas as informações estejam sempre sincronizadas e atualizadas. Além disso, a implementação de cache de dados e técnicas de otimização de desempenho, como o uso de filas, poderiam ser utilizadas para garantir a escalabilidade e a alta disponibilidade do sistema.
<img width="564" alt="Microserviços" src="https://user-images.githubusercontent.com/99920388/216793108-f02dcc35-0591-43fa-82b6-ab7616078b94.png">
