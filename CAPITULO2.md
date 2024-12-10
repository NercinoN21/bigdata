# CAPITULO 2

## Computação em Cluster

> Apresenta uma revisão geral sobre conceitos básicos, como replicação e armazenamento de dados em um sistema, tolerância a falhas (master-slave e peer-to-peer), replicação, armazenamento em discos, técnicas de escalabilidade e como são utilizadas em bancos de dados.

É um sistema composto de diversos computadores autônomos conectados juntos,
trabalhando como um único recurso integrado e altamente disponível.

Clusters adotam o mecanismo **Failover**.

### Tipos De Clusters

- Os de **Alta Disponibilidade**

> Focados em ficar disponível sempre, tendo 1,2,3... de reserva caso o anterior caia.

- Os de **Balanceamento de Carga**

> Focados em garantir a distribuição da carga de trabalho.

### Tipos De Agrupamentos

- **Agrupamentos Simétricos**

> Todas as maquinas trabalham como iguais, onde cada uma representa um nó na rede.

- **Agrupamentos Assimétricos**

> Tem uma maquina principal que distribui o trabalho para as outras maquinas, um nó maior dentro os outros nós.

### Modelos De Distribuição

- **Replicação**

> Salva o mesmo dados em varios nós.

- **Fragmentação**

> Separa o dado em varios pedaços e salva cada pedaço em diferentes nós.

## Sistema De Arquivos Distribuídos

Menor unidade de armazenamento da rede, possui mecanismos
para garantir que sempre seja visualizado a versão atualizada
do arquivo. Alta disponibilidade devido a replicação dos dados.

## Bancos NoSQL

- [ACID Vs BASE](https://aws.amazon.com/pt/compare/the-difference-between-acid-and-base-database/)
- [NoSQL](https://aws.amazon.com/pt/nosql/)

## NewSQL

- [Wikipedia](https://en.wikipedia.org/wiki/NewSQL)

- Clustrix, NuoDB, MemSQL...

## Escalabilidade

- **Vertical:** Adiciona a um ou mais computadores da rede, mais memoria ram,
disco rígido... ficando limitada a capacidade de adicionar novos componentes
  nos computadores.

- **Horizontal** Adiciona um novo computador a rede.
