# Desenvolvimento de soluções de armazenamento com o Amazon Simple Storage Service (Amazon S3)

## Armazenamento de objetos
<img src="../images/Architecture09172021/Arch_Storage/64/Arch_Amazon-Simple-Storage-Service_64.png" alt="certifications" title="Amazon S3"></img>
Amazon S3: O Amazon Simple Storage Service (Amazon S3) é um serviço de armazenamento de objetos que oferece escalabilidade, disponibilidade de dados, segurança e performance líderes do setor. Isso significa que clientes de todos os tamanhos e setores podem usá-lo para armazenar e proteger qualquer volume de dados em vários casos de uso, como data lakes, sites, aplicações para dispositivos móveis, backup e restauração, arquivamento, aplicações empresariais, dispositivos IoT e análises de big data. O Amazon S3 fornece recursos de gerenciamento fáceis de usar, de maneira que você possa organizar os dados e configurar os controles de acesso refinados para atender a requisitos específicos comerciais, organizacionais e de conformidade. O Amazon S3 foi projetado para 99,999999999% (11 noves) de durabilidade e armazena dados de milhões de aplicações para empresas em todo o mundo.
<br/>

### Grande variedade de classes de armazenamento econômicas
É possível usar o <b>S3 Storage Class Analysis </b> para descobrir dados que deveriam ser migrados para uma classe de armazenamento de custo reduzido, com base em padrões de acesso, e configurar uma política do S3 Lifecycle para executar a transferência.

Você também pode armazenar dados com padrões de acesso desconhecidos ou em constante mudança no 
<b> S3 Intelligent-Tiering </b>, 
que classifica objetos com base em padrões de acesso mutáveis e oferece economia automaticamente

Com a classe de armazenamento <b> S3 Outposts</b>, você pode atender aos requisitos de residência de dados e armazenar dados on-premises em seu ambiente Outposts usando S3 on Outposts.

### Recursos incomparáveis de segurança, conformidade e auditoria

Armazene os dados no Amazon S3 e os proteja contra acesso não autorizado com recursos de criptografia e ferramentas de gerenciamento de acesso. O S3 é o único serviço de armazenamento que permite que você bloqueie o acesso público a todos os seus objetos no bucket ou na conta com o S3 Block Public Access. O S3 mantém programas de conformidade como PCI-DSS, HIPAA/HITECH, FedRAMP, EU Data Protection Directive e FISMA para ajudar a cumprir requisitos normativos. O S3 se integra ao Amazon Macie para descobrir e proteger seus dados confidenciais.


<img src="../images/Architecture09172021/Arch_Storage/64/Arch_Amazon-Simple-Storage-Service-Glacier_64.png" alt="certifications" title="Amazon S3 Glacier">
</img>
<b>Amazon S3 Glacier :</b> Armazenamento de arquivos de baixo custo e altamente durável na nuvem

<br/>

## Armazenamento de arquivos

<img src="../images/Architecture09172021/Arch_Storage/64/Arch_Amazon-Elastic-File-System_64.png" alt="certifications" title="Amazon EFS">
</img>
<b>Amazon-Elastic File System :</b> Armazenamento de arquivos de rede escalável para instâncias do Amazon EC2
<br/>

<img src="../images/Architecture09172021/Arch_Storage/64/Arch_Amazon-Simple-Storage-Service-Glacier_64.png" alt="certifications" title="Amazon S3 Glacier">
</img>
Armazenamento de arquivos de baixo custo e altamente durável na nuvem

<br/>

## Armazenamento em blocos
<img src="../images/Architecture09172021/Arch_Storage/64/Arch_Amazon-Elastic-Block-Store_64.png" alt="certifications" title="Elastic-Block-Store">
</img>
<b> Elastic Block Store </b> Volumes conectados à rede que fornecem armazenamento durável em nível de bloco para instâncias do Amazon EC2.
<br/>
<br/>


## Backup
<img src="../images/Architecture09172021/Arch_Storage/64/Arch_AWS-Backup_64.png" alt="certifications" title="Arch AWS Backup">
</img>
<b>AWS Backup</b> O AWS Backup permite centralizar e automatizar a proteção de dados por meio dos serviços da AWS. O AWS Backup oferece um serviço econômico, totalmente gerenciado e baseado em políticas que simplifica ainda mais a proteção de dados em grande escala. 
<br/>
<br/>

## Transferência de dados

## Armazenamento de computação de borda

Estudos de Caso:
Amazon Simple Storage Service Glacier (Amazon S3 Glacier) — serviço de armazenamento de custo acessível que oferece armazenamento altamente seguro, durável e flexível para arquivamento de dados e backup online. Armazene seus dados por apenas 0,004 USD por gigabyte ao mês.
 
Você armazena dados no Amazon S3 Glacier como arquivos. Um arquivo pode representar um único arquivo ou você pode combinar vários arquivos para fazer o upload como um único arquivo. 

Tipos de recuperação:
As recuperações aceleradas geralmente retornam dados em um a cinco minutos e são excelentes para casos de uso de arquivamento ativo. 
Geralmente, as recuperações padrão são concluídas em três a cinco horas e funcionam bem para atividades em que o tempo não é tão crucial, como dados de backup, edição de mídia ou análises a longo prazo. 
As recuperações em massa são a opção de recuperação mais barata, e retornam grandes quantidades de dados em 5 a 12 horas.

Os casos de uso incluem arquivamento de informações corporativas externas, ativos de mídia e dados científicos e de pesquisa, além de realizar preservação digital e substituição de fitas magnéticas.

Amazon Elastic File System (Amazon EFS) — O Amazon EFS oferece um sistema de arquivos de rede simples,  escalável, elástico, altamente disponível e altamente durável como serviço para as instâncias do Amazon Elastic Compute Cloud (Amazon EC2).

Ele foi projetado para fornecer um sistema de arquivos de rede altamente escalável que pode crescer até petabytes. Essa elasticidade permite o acesso maciçamente paralelo das instâncias do EC2 aos seus dados em uma região. Também está altamente disponível e é altamente durável porque armazena dados e metadados em várias zonas de disponibilidade em uma região.

O Amazon EFS é compatível a cargas de trabalho altamente paralelizadas. Ele foi projetado para atender às necessidades de performance de big data e análise, processamento de mídia, gerenciamento de conteúdo, web serving e diretórios home. 

AWS Storage Gateway: o AWS Storage Gateway conecta um dispositivo de software local ao armazenamento baseado em nuvem.  Ele fornece integração perfeita e segura entre o ambiente de TI local de uma organização e a infraestrutura de armazenamento da AWS, tais como Amazon S3, Amazon S3 Glacier, e Amazon EBS.

Os casos de uso do AWS Storage Gateway incluem o seguinte:
Compartilhamento de arquivos corporativo
Ativando aplicações de backup locais existentes para armazenar backups principais no Amazon S3
Recuperação de desastres
Espelhamento de dados em recursos de computação baseados em nuvem e, em seguida, arquivá-los no Amazon S3 Glacier

Amazon Elastic Block Store (Amazon EBS) —os volumes do Amazon EBS fornecem armazenamento durável em nível de bloco para uso com instâncias do EC2. Os volumes do Amazon EBS são um armazenamento conectado à rede que persiste independentemente da vida útil de uma única instância do EC2.
O Amazon EBS foi criado para cargas de trabalho de aplicações que se beneficiam de ajustes para obter performance, custos e capacidade melhores. Com o Amazon EBS, você também pode criar snapshots point-in-time de volumes, que são armazenados no Amazon S3.

Os casos de uso típicos do Amazon EBS incluem o seguinte: 
Mecanismos de análise de big data (como o ecossistema Hadoop/HDFS e  clusters do Amazon EMR)
Bancos de dados relacionais e NoSQL (como Microsoft SQL Server e MySQL ou Cassandra e MongoDB)
Aplicações de processamento de fluxo e log (como Kafka e Splunk)
Aplicações de Datawarehousing (como  Vertica e Teradata)

