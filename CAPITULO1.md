# CAPITULO 1

## Introdução

> Apresenta uma contextualização sobre o Big Data,
> mostrando a importância e a necessidade de se
> trabalhar com grandes volumes de dados, e como
> isso pode ser benéfico para as empresas. O
> capítulo também aborda a evolução do Big Data,
> mostrando como ele se tornou uma ferramenta
> essencial para as empresas, e como ele pode
> ser utilizado para melhorar a eficiência e
> a eficácia dos processos de negócios.

## Understanding Big Data

Demostra através de exemplos(como: "2.5 quintillion bytes of data are
generated every day") que um grande volume de dados não estruturados(isto é,
dados que não estão organizados em um formato que possa ser facilmente
analisado) são gerados diariamente, e que esses dados podem ser utilizados
para melhorar a eficiência e a eficácia dos processos de negócios.

Além disso, destaca a difilculdade de se trabalhar com grandes volumes de
dados, apresentando tecnologias disponíveis para lidar com esses dados, como
o [Hadoop](https://hadoop.apache.org/): [HDSF](https://www.databricks.com/br/glossary/hadoop-distributed-file-system-hdfs)
e [MapReduce](https://www.devmedia.com.br/hadoop-mapreduce-introducao-a-big-data/30034).

## Evolution of Big Data

Expresa como o problema de visualização de grandes volumes de dados foi
registrado pela primeira vez em 1997 pela NASA [(Nesse relatório podemos ver
a quantidade de dados que a NASA estava gerando em 1997)](https://nssdc.gsfc.nasa.gov/nssdc/annual/1997/),
demostrando que o problema de lidar com grandes volumes de dados não é novo.
E que seu crescimento é exponencial, indo de 600 MB em 1950 de dados gerados
para em 2010 100 petabytes de dados gerados.

## Failure of Traditional Database in Handling Big Data

Mostra que os bancos de dados tradicionais não são capazes de lidar com
grandes volumes de dados, pois foram projetados para lidar com dados
estruturados, e não com dados não estruturados. Além disso, destaca que
devido ao grande volume de dados gerados diariamente, é necessário utilizar
hardware de ponta para armazenar e processar esses dados, gerando custos
elevados para as empresas. Isto combinado com falta de capacidade de
armazenar os dados na velocidade que são gerados, torna os bancos de dados
tradicionais[(RDBMS)](https://www.oracle.com/br/database/what-is-a-relational-database/)
inadequados para lidar com grandes volumes de dados.

| **Attributes**    | **RDBMS**              | **Big Data**                     |
|:-----------------:|:----------------------:|:--------------------------------:|
| **Data volume**   | Gigabytes to terabytes | Petabytes to zettabytes          |
| **Organization**  | Centralized            | Distributed                      |
| **Data type**     | Structured             | Unstructured and semi-structured |
| **Hardware type** | High-end model         | Commodity hardware               |
| **Updates**       | Read/write many times  | Write once, read many times      |
| **Schema**        | Static                 | Dynamic                          |

- **Data Mining**
  
  - Data mining é o processo de descobrir o conhecimento subjacente dos conjuntos de dados.
  - Trabalha com dados estruturados provenientes de planilhas, bancos de dados relacionais, etc.
  - É capaz de processar grandes conjuntos de dados, mas os custos de processamento são altos.
  - Pode processar conjuntos de dados que variam de gigabytes a terabytes.

- **Big Data**
  
  - Big data refere-se a grandes volumes de dados caracterizados por volume, velocidade e variedade.
  - Inclui dados estruturados, não estruturados ou semi-estruturados provenientes de bancos de dados não relacionais, como NoSQL.
  - Ferramentas e tecnologias de big data são capazes de armazenar e processar grandes volumes de dados a custos relativamente mais baixos.
  - É capaz de armazenar e processar dados que variam de petabytes a zettabytes.

> [Data Mining](https://cetax.com.br/data-mining/)

## 3Vs of Big Data

- Volume
  - Refere-se à quantidade de dados gerados diariamente e à capacidade de armazenar e processar esses dados.
  - Exemplo: 2.5 quintillion bytes of data are generated every day.
- Velocidade
  - Refere-se à velocidade com que os dados são gerados e processados.
  - Exemplo: Twitter processes 500 million tweets per day.
- Variedade
  - Refere-se aos diferentes tipos de dados gerados diariamente(estruturados, não estruturados e semi-estruturados).
  - Exemplo: 80% of the world's data is unstructured.

## Sources of Big Data

- **Social Media**
  - Exemplo: Facebook, Twitter, Instagram, etc.
- **Sensors**
  - Exemplo: GPS, RFID, etc.
- **Internet of Things(IoT)**
  - Exemplo: Smart devices, wearables, etc.
- **Machine-generated data**
  - Exemplo: Logs, clickstreams, etc.
- **Black Box Data**
  - Exemplo: Flight data recorders, etc.
- **Healthcare data**
  - Exemplo: Electronic health records, etc.
- **Organizational data**
  - Exemplo: Sales data, customer data, etc.

## Different Types of Data

- **Structured Data**
  - Refere-se a dados organizados em um formato que pode ser facilmente analisado.
  - Exemplo: Banco de dados relacional.
- **Unstructured Data**
  - Refere-se a dados que não estão organizados em um formato que possa ser facilmente analisado.
  - Exemplo: E-mails, vídeos e imagens.
- **Semi-structured Data**
  - Refere-se a dados que estão parcialmente organizados em um formato que pode ser facilmente analisado.
  - Exemplo: XML, JSON.

## Big Data Infrastructure

- **Hadoop**
  - É um framework de código aberto que permite o processamento distribuído de grandes volumes de dados em clusters de computadores.
  - É composto por dois principais componentes: HDFS e MapReduce.
- **HDFS**
  - É um sistema de arquivos distribuído que permite o armazenamento de grandes volumes de dados em clusters de computadores.
  - É altamente tolerante a falhas e escalável.
- **MapReduce**
  - É um modelo de programação que permite o processamento paralelo de grandes volumes de dados em clusters de computadores.
  - Divide o trabalho em tarefas menores que são executadas em paralelo.

## Big Data Life Cycle

As tecnologias de big data capturam e analisam esses dados com eficiência, utilizando
infraestruturas que processam computações distribuídas e paralelas, com armazenamento
escalável. Componentes como Hadoop, HDFS e MapReduce suportam esse processo. O ciclo
de vida do big data inclui captura de dados em alta velocidade, armazenamento em
plataformas como HDFS e NoSQL, pré-processamento para adequação à análise, e uso
de ferramentas analíticas como MapReduce e YARN para extrair conhecimento dos dados.
Técnicas de aprendizado de máquina e análise preditiva são aplicadas, especialmente
na análise de textos oriundos de mídias sociais e e-mails. Por fim, os resultados
são apresentados em visualizações claras, por ferramentas como Tableau, para apoiar a tomada de decisões.

- **Smoothing**
  - Refere-se ao processo de suavização dos dados para remover ruídos e tornar os padrões mais visíveis.
  - Exemplo: Média móvel.
- **Aggregation**
  - Refere-se ao processo de combinar dados de várias fontes para obter uma visão mais ampla.
  - Exemplo: Somar as vendas de várias lojas para obter as vendas totais.
- **Generalization**
  - Refere-se ao processo de simplificar os dados para torná-los mais fáceis de entender.
  - Exemplo: Agrupar os dados por região para obter uma visão geral das vendas.
- **Discretization**
  - Refere-se ao processo de transformar dados contínuos em dados discretos.
  - Exemplo: Agrupar as idades dos clientes em faixas etárias.

## Big Data Technology

O avanço tecnológico transformou as formas de geração, captura, processamento e análise de dados,
aumentando significativamente a eficiência desses processos. O Apache Hadoop, uma plataforma
open-source, é uma das principais tecnologias de big data, criada por Doug Cutting e
Mike Cafarella com o objetivo inicial de indexar a web, em um projeto chamado "Nutch".
O nome "Hadoop" veio do elefante de brinquedo do filho de Doug. O Hadoop é um framework
para armazenamento e processamento distribuído de grandes volumes de dados, sendo capaz
de lidar com dados estruturados, semiestruturados e não estruturados de forma econômica
graças ao uso de hardware comum. Seus componentes principais incluem HDFS (sistema de
arquivos distribuídos), Hadoop Common (utilitários básicos), MapReduce (processamento de
dados) e YARN (gerenciador de recursos distribuídos). O YARN, introduzido no Hadoop 2.0,
substituiu o gerenciamento de recursos do MapReduce do Hadoop 1.0, permitindo que o Hadoop
execute outros tipos de tarefas além do MapReduce. O Hadoop Common fornece serviços essenciais
e scripts necessários para o funcionamento do Hadoop.

## Big Data Applications And Big Data Use Cases

- Bancos e Valores Mobiliários: Detecção de fraudes em cartões de crédito/débito, alertas para fraudes em valores mobiliários, relatórios de risco de crédito e análises de dados de clientes.
- Setor de Saúde: Armazenamento e análise de dados de pacientes para identificar doenças em estágios iniciais.
- Marketing: Análise do histórico de compras dos clientes para direcionar produtos recém-lançados ao público-alvo.
- Análise Web: Dados de mídias sociais e mecanismos de busca são analisados para exibir anúncios com base nos interesses dos usuários.
- Análise de Call Centers: Identificação de problemas recorrentes e padrões de comportamento da equipe por meio do processamento do conteúdo das chamadas.
- Agricultura: Uso de sensores para otimizar a eficiência das colheitas e análise dos dados gerados por esses sensores.
- Smartphones: Utilização de reconhecimento facial para desbloqueio de dispositivos e recuperação de informações previamente armazenadas.
- Transporte: Análise de dados de tráfego para otimizar rotas e reduzir o tempo de viagem.
- Energia: Monitoramento do consumo de energia para identificar padrões de uso e reduzir custos.
- Educação: Análise de dados de desempenho dos alunos para identificar áreas de melhoria e personalizar o ensino.
- Governo: Análise de dados de cidadãos para identificar tendências e padrões de comportamento.
- Seguros: Análise de dados de sinistros para identificar fraudes e avaliar riscos.
- Varejo: Análise de dados de vendas para prever a demanda e otimizar o estoque.
- Entretenimento: Análise de dados de visualização para recomendar conteúdo personalizado aos usuários.
