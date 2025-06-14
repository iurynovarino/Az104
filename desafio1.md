# Entendendo Desafio 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos abordados até aqui, aplique os conhecimentos adquiridos nas aulas e documente sua experiência para demonstrar sua compreensão dos temas discutidos.


## Descrição do Desafio
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Neste laboratório prático será abordado um resumo sobre gerenciar máquinas virtuais no Microsoft Azure. O desafio proposto é a criação de um repositório contendo resumos, anotações e dicas sobre o uso da Azure, servindo como material de apoio para estudos e futuras implementações.

## Objetivos de Aprendizagem 
**Ao concluir este desafio, você será capaz de:** 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Aplicar os conceitos aprendidos em um ambiente prático;
Documentar processos técnicos de forma clara e estruturada; 
Utilizar o GitHub como ferramenta para compartilhamento de documentação técnica. 

## 🔍 Recursos de Estudo

[implantar e gerenciar os recursos de computação do Azure](https://learn.microsoft.com/pt-br/training/paths/az-104-manage-compute-resources/)


# Máquinas Virtuais no Azure

## Conceito de máquina virtual
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Uma máquina virtual é um ambiente computacional isolado que simula um computador físico, executando sistemas operacionais e aplicativos de forma independente.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; As VMs do Azure são um dos vários tipos de recursos de computação escalonáveis sob demanda oferecidos pelo Azure. Com as VMs, você tem controle total sobre a configuração e pode instalar qualquer coisa que precisar para realizar o trabalho. Você não precisa comprar o hardware físico quando precisar dimensionar ou estender o datacenter. Por fim, o Azure oferece serviços adicionais para monitorar, proteger e gerenciar atualizações e patches para o sistema operacional.

📌 **Configuração de Máquinas Virtuais no Azure**

Você pode criar uma VM no Azure via Portal Azure, Azure CLI, PowerShell ou templates ARM/Bicep.

**Parâmetros principais:**

**Imagem** (Windows, Linux, etc.)

**Tamanho** (SKU): Define CPU, memória e disco.

**Rede:** Associação a uma VNet, com sub-redes, endereços IP públicos/privados e NSG (Network Security Group).

**Autenticação:** Por senha ou chave SSH (Linux).

**Discos:** Disco do SO e discos de dados adicionais (Standard ou Premium SSD).

**Tags:** Úteis para organização e controle de custos.
