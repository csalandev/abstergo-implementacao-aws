<div align="center">
  <img src="assets/aws_logo.png" width="100" alt="AWS Logo">
  <h1>Abstergo Industries: Implementação AWS</h1>
</div>

Este repositório contém o relatório de planejamento para a migração da infraestrutura local da **Abstergo Industries** para a nuvem AWS. O projeto foca em reduzir os custos fixos de TI e conferir maior segurança aos dados.

---

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 15/01/2026
Empresa: Abstergo Industries
Responsável: Alan

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo, realizado por Alan. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)
- **Foco da ferramenta:** Servidores virtuais escaláveis.
- **Descrição de caso de uso:** Em vez de a Abstergo comprar servidores físicos caros que ficam obsoletos, vamos usar instâncias do EC2 para rodar o sistema de vendas e o site da farmácia. O ganho financeiro aqui é imediato: paramos de gastar com energia elétrica para refrigerar salas de servidores e não precisamos mais de equipe para consertar peças de hardware. Além disso, se a farmácia crescer, podemos aumentar a capacidade do servidor com um clique.

Etapa 2: 
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de objetos (arquivos) de baixo custo.
- **Descrição de caso de uso:** A farmácia precisa guardar cópias de receitas digitais, notas fiscais e documentos de estoque por anos. Usar o S3 é muito mais barato do que manter HDs externos ou fitas de backup. O S3 oferece alta durabilidade e só cobra pelo espaço usado, o que reduz o custo de armazenamento de dados históricos que não precisam ser acessados toda hora, mas que são obrigatórios por lei.

Etapa 3: 
- **Nome da ferramenta:** Amazon RDS (Relational Database Service)
- **Foco da ferramenta:** Banco de dados relacional gerenciado.
- **Descrição de caso de uso:** Para o controle de estoque e cadastro de clientes, precisamos de um banco de dados seguro. Com o RDS, a AWS cuida das atualizações de segurança e dos backups automáticos. Isso reduz o custo operacional porque não precisamos gastar horas de um técnico configurando backups manuais todos os dias. Se o banco de dados falhar, o serviço tem recuperação automática, garantindo que a farmácia não pare de vender.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado redução significativa nos custos fixos de TI e maior segurança dos dados*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

1. [Documentação básica de configuração das instâncias EC2](./anexos/configuracao-ec2.md)
2. [Tabela comparativa de custos: Servidor Local vs. AWS Cloud](./anexos/comparativo-custos.md)
3. [Plano de migração de dados do banco local para o Amazon RDS](./anexos/plano-migracao.md)

Assinatura do Responsável pelo Projeto:

Alan