# Fernando Horas

**Liderança Técnica em GenAI | Agentes de IA, RAG e Cloud AWS, Google | AI-Driven**

Diretor de TI na BSP PROMPT, consultoria especializada em IA generativa, com soluções estratégicas e produtos baseados em modelos como Claude e Gemini, focados em implementação prática para clientes corporativos.

[![Website](https://img.shields.io/badge/Website-000000?style=for-the-badge)](https://www.fchdigital.com.br/p%C3%A1gina-inicial)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/fernandohoras/)
[![Twitter](https://img.shields.io/badge/Twitter-000000?style=for-the-badge)](https://twitter.com/FERNANDOHORAS)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge)](https://www.youtube.com/channel/UC5aMWGP2UyQN--oJR9eEqcw)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge)](https://wa.me/5511995143947)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge)](https://t.me/fernandohoras)

## Sobre

Sou Diretor de TI na BSP PROMPT, onde lidero a implementação prática de IA generativa para empresas: agentes de IA, RAG e arquitetura em nuvem AWS e Google. Minha base é infraestrutura e cloud, com migração de ambientes on-premises para a nuvem e de arquitetura monolítica para microsserviços. Hoje aplico essa base para colocar GenAI em produção com governança, controle de custo e compliance.

Atualmente estou construindo o Farol, o TableVision e o Oráculo.

![Snake animation](https://raw.githubusercontent.com/fch-bsp/fch-bsp/output/github-contribution-grid-snake.svg)

## Especialidades

- Agentes de IA, protocolo MCP e conectores com e-mail e plataformas
- RAG e aplicações com modelos de linguagem em produção
- Governança e observabilidade de IA: custo por pessoa e por modelo, tetos de gasto por departamento e compliance
- Arquitetura cloud em AWS e Google Cloud

## Projetos em destaque

### [Farol](https://farol.bspprompt.com/)

Ferramenta de uso, custo e compliance de Claude no Amazon Bedrock, por pessoa, em um único painel, rodando dentro da conta AWS do próprio cliente.

- Gasto por modelo e por dia, dividido pelos tokens de cada pessoa, como estimativa proporcional, já que o Bedrock não fatura por usuário
- Troca de modelo com um clique via IAM Identity Center, com conjunto de modelos e teto de gasto por departamento: ao atingir o teto o acesso é cortado e volta no dia 1 ou quando o teto é aumentado, com notificação dos cortes
- CPF e CNPJ validados por dígito verificador e temas sensíveis por sessão encerrada
- Relatório em PDF para diretores e histórico de 180 dias
- A equipe continua usando o Claude Desktop sem mudança: o Farol observa e controla por fora

### TableVision

SaaS em AWS para ocupação de mesas de restaurante, com detecção na borda e inteligência na nuvem.

- Câmera existente no restaurante e detecção local: sobem para a AWS apenas os eventos de ocupação, sem envio contínuo de vídeo
- Roteiro em fases: ocupação de mesas, tempo de atendimento e, depois, o que está sobre a mesa e onde o tempo se perde
- Identificação do garçom sem biometria e sem reconhecimento facial, pensada para a LGPD: marcador ArUco impresso e discreto no boné ou no avental, combinado com cor do uniforme, comportamento e lógica de entrada na zona da mesa

### Oráculo

Assistente em linguagem natural sobre um banco de dados de gestão de obras, em PostgreSQL com busca vetorial por embeddings. O usuário pergunta em português e recebe a resposta com os dados do banco, sem precisar escrever SQL.

- Base com 1.393 tabelas e visões e mais de 14 mil campos, organizada por projeto
- Perguntas respondidas a partir de consultas prontas e validadas, sempre com a origem de cada número
- Somente leitura no banco, com regras para não somar versões, cenários ou semanas, e sem expor dados pessoais sensíveis

## Stack

### GenAI e IA

<div>
<img align="center" alt="Anthropic" src="https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white" />
<img align="center" alt="Amazon Bedrock" src="https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=for-the-badge&logo=amazonbedrock&logoColor=white" />
<img align="center" alt="OpenAI" src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img align="center" alt="Google Gemini" src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
</div>

### Linguagens e frameworks

<div>
<img align="center" alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img align="center" alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
<img align="center" alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
<img align="center" alt="Go" src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" />
<img align="center" alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
<img align="center" alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
</div>

### Cloud e DevOps

<div>
<img align="center" alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" />
<img align="center" alt="Google Cloud" src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
<img align="center" alt="Microsoft Azure" src="https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" />
<img align="center" alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img align="center" alt="Kubernetes" src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
<img align="center" alt="Terraform" src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
<img align="center" alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
<img align="center" alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</div>

### Dados

<div>
<img align="center" alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
<img align="center" alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
<img align="center" alt="MariaDB" src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" />
<img align="center" alt="Amazon DynamoDB" src="https://img.shields.io/badge/Amazon_DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white" />
<img align="center" alt="Elasticsearch" src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white" />
</div>

## Estatísticas do GitHub

<div>
  <a href="https://github.com/fch-bsp">
    <img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=fch-bsp&theme=github_dark"/>
    <img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=fch-bsp&theme=github_dark"/>
  </a>
</div>
