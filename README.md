## Instancias-ec2AWS
EC2- Elastic Compute Cloud: São as máquinas virtuais na AWS, podendo ser criadas com sistema operacional Windows ou Linux.
O Amazon Elastic Computer Cloud (EC2) Nos fornece a capacidade de computação na cloud da AWS.
As imagens de máquinas da Amazon estão disponíveis para escolha no momento da sua criação.
Existe vários tipos de otimização de recursos sendo eles: Desligando instâncias não utilizadas; Removendo recursos ociosos ou não utilizados e Escalar recursos no sistema.
O EC2 tem possibilidade de 03 instâncias, sendo elas: Sob demandas; Instâncias Reservadas e Instâncias SPOT. 
A instância sob demanda: On-demand são compradas a uma taxa fixa por hora e são recomendadas para aplicativos com carga de trabalho irregulares de curto prazo que não podem ser interrompidas. Elas geralmente são adequadas para uso durante teste e desenvolvimento de aplicativos no EC2.
Instâncias Reservadas: Costumam ser mais baratas que as instâncias sob demanda, mas você precisa realizar o pagamento do ano inteiro de uso. É uma desvantagem pra quem não precisa utilizar a instância com muita frequência.
Instâncias SPOT: Garante a disponibilidade das aplicações sob demanda com descontos de até 90%. A desvantagem das instâncias SPOT é que elas podem ser encerradas pela Amazon Web Service (AWS) a qualquer momento, com um aviso de dois minutos.


## EBS
O Amazon Elastic Block Store (EBS) é um serviço para fornecer armazenamento em discos rígidos. Ele foi concebido para ser utilizado com instâncias do Amazon Elastic Compute Cloud (EC2). 
Observação: O snapshot do EBS é um serviço de backup nativo do AWS que faz backup dos volumes do EBS em um determinado momento.

#Diferença entre Imagem e Snapshot?
No amazon EC2, uma imagem de máquina da AMazon (AMI) faz o backup de um servidor inteiro, incluindo todos os volumes EBS anexados e um snapshot é uma cópia pontual de um determinado volume.
Os snapshot do Amazon EBS são cópias em pontos no tempo de um volume do Amazon EBS, aumentando a durabilidade dos dados e fornecendo mecanismos de backup e restauração para volumes do EBS.
