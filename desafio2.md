# Entendendo Desafio 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos abordados até aqui, aplique os conhecimentos adquiridos nas aulas e documente sua experiência para demonstrar sua compreensão dos temas discutidos.

## Descrição do Desafio
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Neste laboratório prático, você irá aprender a configurar e gerenciar o monitoramento de recursos no Microsoft Azure, com foco em máquinas virtuais (VMs). O objetivo é demonstrar como manter visibilidade, controle e resposta proativa sobre eventos críticos no ambiente de nuvem, como a exclusão de uma VM. Como entregável, o desafio proposto é a criação de um repositório contendo resumos, anotações e dicas sobre o uso da Azure, servindo como material de apoio para estudos e futuras implementações.

## Objetivos de Aprendizagem 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Ao concluir este desafio, você será capaz de: 

Aplicar os conceitos aprendidos em um ambiente prático;
Documentar processos técnicos de forma clara e estruturada; 
Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica. 

## 🔍 Recursos de Estudo
- [Treinamento oficial Microsoft](https://learn.microsoft.com/pt-br/training/modules/configure-monitoring-virtual-machines/)

# Resumo: Monitoramento de recursos no Microsoft Azure

### 🟢 Conceitos básicos

- **Monitoramento**: Coleta e exibição de métricas básicas (CPU, memória, etc.), dashboards e gráficos.
- **Observabilidade**: Monitoramento avançado com alertas, ações automáticas e integração com ferramentas externas (Teams, ITSM, etc).

---

## 🧰 Ferramentas abordadas

- **Azure Monitor**: Plataforma central de monitoramento no Azure.
- **Log Analytics**: Análise e armazenamento de logs.
- **Application Insights**: Monitoramento de desempenho e disponibilidade de aplicações.
- **VM Insights**: Monitoramento de máquinas virtuais.
- **Container Insights**: Monitoramento de clusters AKS e containers.
- **Network Insights**: Monitoramento de redes virtuais.
- **Diagnostic Settings**: Exportação de logs para destinos externos (Storage Account, Event Hub, etc).

---

## 🛠️ Principais Funcionalidades do Azure Monitor

- **Coleta de Métricas**
  - Exemplo: CPU, memória, etc.

- **Análise de Logs**
  - Eventos de segurança, performance, diagnósticos.
  - Linguagem KQL (Kusto Query Language) para consultas avançadas.

- **Alertas**
  - Baseados em métricas ou logs.
  - Envio por: Email, SMS, Webhook, Teams, Logic Apps.
  - Suporte a ações automáticas (ex: restart de VM via Automation Runbook).

- **Dashboards e Workbooks**
  - Visualizações customizadas e relatórios.

- **Diagnóstico e Exportação de Logs**
  - Para Log Analytics, Storage Account, Event Hub ou soluções parceiras.

## 🎓 Dicas para Provas (AZ-104)

- Diferença entre **métricas** (valores numéricos) e **logs** (eventos e registros textuais).
- Tipos de dados monitoráveis:
  - Aplicação
  - Sistema Operacional convidado
  - Recursos Azure
  - Subscription
  - Tenant


## 🛠️ Laboratório prático
- [Lab interativo](https://mslabs.cloudguides.com/en-us/guides/AZ-104%20Exam%20Guide%20-%20Microsoft%20Azure%20Administrator%20Exercise%2017)

## ✅ Conclusão

Ter uma boa estratégia de observabilidade e monitoramento é essencial para garantir a saúde e desempenho de aplicações e infraestrutura no Azure, além de ser tema muito cobrado nas certificações.
