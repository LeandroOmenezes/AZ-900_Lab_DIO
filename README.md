## 🚀 AZ-900_Lab_DIO

Este projeto eu entendi como se concentra os componentes essenciais da arquitetura do Azure.

### 👋 Olá, pode me chamar de Leandro Menezes!

### 😊 Sobre mim
Sou um entusiasta da tecnologia e apaixonado por resolver problemas. Meu sonho é ser um profissional em nuvem e ajudar empresas a crescerem seus negócios
com as tecnologias mais atuais. Atualmente, minha área de atuação é **Analista de Suporte Pleno** mas a desejada é **DevOps Cloud** ou **Arquiteto de Cloud**.

![Top Langs](https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=LeandroOmenezes&bg_color=000&border_color=30A3DC&title_color=E94D5F&text_color=FFF)

### Arquitetura e serviços do Azure

### AZ-900 : Introdução aos Conceitos Básicos do Microsoft Azure

### Principais componentes arquitetônicos do Azure

* Descrever regiões, pares de regiões e regiões soberanas do Azure.
* Descrever as zonas de disponibilidade.
* Descrever os datacenters do Azure
* Descrever os recursos e os grupos de recursos do Azure.
* Descrever as assinaturas.
* Descrever os grupos de gerenciamento.
* Descrever a hierarquia de grupos de recursos, 
* assinaturas e grupos de gerenciamento.

### Contas do Azure

* Conta do Azure
* Conta gratuita do Azure
* Conta de estudante gratuita do Azure
* Área restrita do Microsoft Learn

> [!NOTE]
 >
> Uma conta pode conter diversas assinaturas, e uma assinatura só pode responder apenas para uma única conta AZURE!

### Regiões

* O Azure oferece mais regiões globais do que qualquer outro provedor de nuvem, com mais de 60 regiões representando mais de 140 países

As regiões são compostas de um ou mais datacenters muito próximos.
Eles fornecem flexibilidade e escala para reduzir a latência do cliente.
As regiões preservam a residência dos dados com uma oferta abrangente de conformidade.

### Zonas de disponibilidade

Fornece proteção contra tempo de inatividade devido a falha do datacenter.

Separe fisicamente os datacenters dentro da mesma região.

Cada datacenter é equipado com alimentação, resfriamento e rede independentes. 

Conectadas por meio de redes privadas de fibra óptica.


### Pares de Regiões

No mínimo 300 milhas de separação entre pares de regiões.
Replicação automática para alguns serviços.
Recuperação de região priorizada em caso de interrupção.

Regiões soberanas do Azure

Serviços Governamentais dos EUA

Atende às necessidades de segurança e conformidade das agências federais, governos estaduais e locais dos EUA e seus provedores de soluções.

Regiões soberanas do Azure

### Azure Governamental:

Instância separada do Azure.
Fisicamente isolada de implantações que não sejam do governo dos EUA.
Acessível somente a pessoal verificado e autorizado.

## Recursos do Azure

* Os recursos do Azure são componentes como armazenamento, máquinas virtuais e redes que estão disponíveis para criar soluções de nuvem.

### Grupos de recursos

Um grupo de recursos é um contêiner que você usa para gerenciar e agregar recursos em uma única unidade. 
Os recursos podem existir em apenas um grupo de recursos.
Os recursos podem existir em diferentes regiões.
Os recursos podem ser movidos para diferentes 
grupos de recursos. 
Os aplicativos podem utilizar vários grupos de recursos.

![Imagem do Portal AZURE](PROJETO_LAB1.png)
 
### Assinaturas do Azure

* Uma assinatura do Azure fornece a você acesso autenticado e autorizado às contas do Azure.

* Limite de cobrança: 
gere relatórios de cobrança e faturas separados para cada assinatura.

* Limite do controle de acesso: 
gerenciar e controlar o acesso aos recursos que os usuários podem provisionar com assinaturas específicas.

### Grupos de gerenciamento

Os grupos de gerenciamento podem incluir várias assinaturas do Azure.
As assinaturas herdam as condições aplicadas ao 
grupo de gerenciamento.

* Uma conta pode conter diversas assinaturas, e uma assinatura só podem responder apenas para uma única conta AZURE

### Recapitulando…

Regiões, pares de regiões e regiões soberanas do Azure.
Zonas de disponibilidade e datacenters do Azure.
Recursos e os grupos de recursos do Azure.
Assinaturas e grupos de gerenciamento.
Hierarquia de grupos de recursos, assinaturas 
e grupos de gerenciamento.

* Este projeto eu entendi como se concentra os componentes essenciais da arquitetura do Azure.

# Projeto de Rede na Nuvem Azure

## Visão Geral
Este projeto descreve a implementação de uma infraestrutura de rede na nuvem Azure para uma empresa de grande porte. A solução visa melhorar a escalabilidade, segurança, e eficiência operacional.

## Arquitetura da Rede

![Imagem do Portal AZURE](VNET1.png)

### 1. Rede Virtual (VNet)
- **Descrição**: Criação de uma VNet para isolar e segmentar a rede.
- **Benefícios**: 
  - Isolamento de rede para segurança.
  - Segmentação para melhor gerenciamento de tráfego.

### 2. Sub-redes
- **Descrição**: Divisão da VNet em sub-redes para diferentes departamentos (e.g., TI, RH, Vendas).
- **Benefícios**: 
  - Melhor controle de acesso.
  - Otimização do tráfego interno.

### 3. Gateway de VPN
- **Descrição**: Configuração de um Gateway de VPN para conectar a rede local à VNet.
- **Benefícios**: 
  - Conexão segura entre a rede local e a nuvem.
  - Acesso remoto seguro para funcionários.

### 4. Firewall da Azure
- **Descrição**: Implementação de um firewall para proteger a rede contra ameaças externas.
- **Benefícios**: 
  - Proteção avançada contra ameaças.
  - Monitoramento e controle de tráfego.

### 5. Balanceador de Carga
- **Descrição**: Configuração de um balanceador de carga para distribuir o tráfego entre várias instâncias de serviço.
- **Benefícios**: 
  - Alta disponibilidade.
  - Melhor desempenho e escalabilidade.

### 6. Azure Bastion
- **Descrição**: Implementação do Azure Bastion para acesso seguro às VMs sem expor IPs públicos.
- **Benefícios**: 
  - Acesso seguro às VMs.
  - Redução de riscos de segurança.

## Benefícios da Utilização da Nuvem

### 1. Escalabilidade
- **Descrição**: Capacidade de aumentar ou diminuir recursos conforme a demanda.
- **Benefícios**: 
  - Redução de custos operacionais.
  - Flexibilidade para atender picos de demanda.

### 2. Segurança
- **Descrição**: Implementação de medidas de segurança avançadas.
- **Benefícios**: 
  - Proteção contra ameaças cibernéticas.
  - Conformidade com regulamentos de segurança.

### 3. Eficiência Operacional
- **Descrição**: Automação de tarefas e gerenciamento centralizado.
- **Benefícios**: 
  - Redução de erros humanos.
  - Aumento da produtividade.

### 4. Redução de Custos
- **Descrição**: Pagamento conforme o uso e eliminação de custos com hardware.
- **Benefícios**: 
  - Economia significativa em infraestrutura.
  - Investimento em inovação.

### 5. Continuidade de Negócios
- **Descrição**: Implementação de soluções de backup e recuperação de desastres.
- **Benefícios**: 
  - Minimização de downtime.
  - Garantia de disponibilidade dos serviços.

## Conclusão
A implementação de uma rede na nuvem Azure oferece diversos benefícios para empresas de grande porte, incluindo escalabilidade, segurança, eficiência operacional, redução de custos e continuidade de negócios. Este projeto visa proporcionar uma infraestrutura robusta e segura, alinhada com as necessidades de crescimento e inovação da empresa.

## 💙 Projetos e Interesses

- Estou sempre buscando aprender mais sobre Cloud e minha primeira certificação AZ-900.
- Sou aluno da DIO.ME e estou estudando **Cloud** em parceria com **Microsoft AZURE**  .
- [![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](https://[].app)
- ![Azure](https://img.shields.io/badge/Azure-blue?style=for-the-badge&logo=microsoft%20azure&logoColor=blue&labelColor=FFFFFF&link=https%3A%2F%2Fimages.app.goo.gl%2FK7PN1jYJd57x4q7A8)
- ![AWS](https://img.shields.io/badge/AWS-000.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
