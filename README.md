# Resumo Bootcamp DIO - Microsoft Azure AZ900

## Introdução ao ambiente cloud:
- Modelos de cloud
  - Privada
  - Publica
  - Hibrid
- Despesas:
  - CapEx - Despesas de capital
    - Gasto com infraestrutura fisica
    - Valor que reduz com o tempo
  - OpEx - Despesas Operacionais
    - Gasto com produtos e serviços conferme necessario, pagamento conforme o uso
    - Cobrado imediatamente
- Principais vantagens de usar cloud:
  - Baseado em consumo
  - previsão de custos
  - preços por recursos e serviços individuais
  - pagamento conforme o uso
  
## Beneficios da Nuvem Azure
- Alta Disponibilidade - contrato de nivel de serviço SLA
  - Em caso de indisponibilidade acima do SLA, recebera credito.
- Escalabilidade e Elasticidade
    - Adicionar mais recursos ou serviços a medida que necessita
- Confiabilidade
  - Design descentralizado, infraestrutura confiavel e resiliente
  - Escala global
- Previsibilidade
  - Previsão para no desempenho e custos
- Segurança
  - Oferece muitas ferramentas de segurança, implementação por parte do cliente
- Governança
  - Auditoria
  - Segurança conforme modelo operacional
- Gerenciabilidade
  - Gerenciamento facilitado
  - Implantação de recursos com base em modelos pre-configurdos
    - Via portal
	- API
	- Linha de comando
	- Ferramentas de terceiros como Terraform

## Tipos de serviços de nuvem
- IaaS, PaaS, SaaS
  - IaaS - infraestrutura como serviço
    - Serviço de uso da infraestrutura como rede, servidor e firewall
  - PaaS - Plataforma como serviço
    - Serviço de uso de software como plataforma, sem configurar servidor
  - SaaS - Software como serviço
    - Software em gerar baseado em liceciamento
- Modelo responsabilidade Compatilhada
  - Dependendo do modelo as reponsabilidades mudam, no caso do IaaS o usuario tem maior responbilidades enquanto no SaaS o provedor da nuvem que tem a maior responsabilidade.

## Arquitetura e Serviços da Azure
- Regiões: Zonas de Disponibilidade
  - Datacenters distribuidos em varias regiões do mundo.
  - Proteção contra tempo de inatividde
  - Replicação entre datacenters
  - Datacenters separados fisicamente em cada zona de disponibilidade
  - Conectados por meio de redes privadas com fibra optica
- Pares de região
  - 300 milhas de separação em entre pares de regiões
  - Replicação automatica de alguns serviços
- Regiões Soberanas
  - Serviços governamentais
  - Não acessives ao publico
- Recursos do Azure
  - EX: 
    - Maquinas virtuais
    - Contas de armazenamento
    - Redes virtuais
    - Serviços de aplicativos
    - Bancos de dados
    - Funções
  - Organização por Grupos de recursos
    - Recursos podem estar em mais de uma região
	- Aplicativos podem utilizar varios grupos
- Assinaturs do Azure
  - Uma conta pode ter mais de uma assinatura, as assinaturas pertecem apenas a uma conta.
  - Para cada assinatura tem uma fatura
  - Limite de cobrança
  - Controle de acesso
- Grupos de Gereenciamento
  - Podem incluir varias assinturas
  - Assinaturas herdam as condições no grupo de gerenciamento
