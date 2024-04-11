### RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
Data: 11/04/2024

Empresa: Abstergo Industries 

Responsável: Henrique Mendes

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa farmaceutica ficticia Abstergo Industries , realizado por Henrique Mendes. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

# Medida 1: - Controle de Acesso Baseado em Funções (RBAC) com AWS IAM:
A empresa implementaria um modelo de Controle de Acesso Baseado em Funções (RBAC) utilizando o AWS Identity and Access Management (IAM). Serão criadas políticas de acesso granulares para diferentes funções na organização, atribuindo permissões específicas com base nas responsabilidades dos usuários. Isso garante que apenas usuários autorizados tenham acesso aos recursos da AWS e que cada usuário tenha apenas as permissões necessárias para realizar suas tarefas.

# Medida 2: - Monitoramento e Análise de Logs com Amazon CloudWatch e AWS CloudTrail:
Será configurado um sistema de monitoramento e análise de logs utilizando o Amazon CloudWatch e o AWS CloudTrail. O CloudWatch é utilizado para monitorar o desempenho dos recursos da AWS e configurar alarmes para eventos indesejados, como picos de tráfego ou uso excessivo de recursos. Já o CloudTrail registra todas as chamadas de API feitas na conta da AWS, fornecendo uma trilha de auditoria detalhada das ações realizadas, o que ajuda a identificar atividades suspeitas e responder rapidamente a possíveis ameaças.

# Medida 3: - Criptografia de Dados em Repouso e em Trânsito com AWS KMS e SSL/TLS:
Para proteger os dados armazenados e em trânsito na AWS, a empresa irá implementar criptografia de dados em repouso e em trânsito. O AWS Key Management Service (KMS) será utilizado para gerenciar chaves de criptografia e criptografar dados armazenados em serviços como Amazon S3, Amazon EBS e Amazon RDS. Além disso, a comunicação entre os serviços da AWS é protegida utilizando SSL/TLS para criptografar dados em trânsito, garantindo a confidencialidade e integridade dos dados.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado fortalecer significativamente a postura de segurança, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Henrique Mendes