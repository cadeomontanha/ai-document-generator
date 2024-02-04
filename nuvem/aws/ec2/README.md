### Amazon EC2 (Elastic Compute Cloud)

Amazon EC2 é um serviço da AWS que fornece capacidade computacional escalável na nuvem. Permite aos usuários executar aplicações em uma rede de servidores virtuais.

#### Instâncias EC2

Uma instância EC2 é um servidor virtual para rodar aplicações. Existem diversos tipos de instâncias, cada um otimizado para diferentes casos de uso:

- *Geral:* Equilíbrio entre recursos de CPU, memória e rede.
- *Otimizadas para computação:* Ideal para tarefas que exigem mais CPU.
- *Otimizadas para memória:* Para aplicações que usam muita memória RAM.
- *Otimizadas para armazenamento:* Desenhadas para operações intensas de leitura/escrita em disco.
- *Aceleradas por GPU:* Para trabalho com gráficos e aprendizado de máquina.

#### Funcionamento das Instâncias EC2

1. *Escolha do Tipo de Instância:* Seleção baseada na necessidade da carga de trabalho.
2. *Configuração de Instância:* Escolha de sistema operacional e volume de EBS.
3. *Lançamento da Instância:* Após configuração, a instância é iniciada.
4. *Acesso à Instância:* Utilização de SSH ou RDP para acessar a instância.
5. *Gerenciamento de Instâncias:* Monitoramento e gerenciamento via console AWS, CLI ou SDKs.
6. *Dimensionamento:* Escala vertical (mudança de tipo) ou horizontal (mais instâncias).

#### Ciclo de Vida de uma Instância EC2

- *Pending:* Preparação para execução.
- *Running:* Instância operacional.
- *Stopping/Stopped:* Pausa da instância, mantendo os dados.
- *Terminating/Terminated:* Finalização e exclusão de instância.

#### Custos de Instâncias EC2

- *On-Demand:* Pagamento conforme o uso, sem compromisso de longo prazo.
- *Reserved Instances:* Contrato com desconto para 1 ou 3 anos.
- *Spot Instances:* Capacidade não utilizada com desconto, com possibilidade de interrupção.
- *Dedicated Hosts:* Servidores físicos dedicados.

#### Segurança e Storage

- Segurança com grupos de segurança e ACLs.
- Armazenamento através de EBS ou armazenamento de instância.
