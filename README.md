<h1 align="center">Olá, me chamo Vinicius! 👋</h1>

<p align="center">
  <strong>Analista de Desenvolvimento</strong> · Node.js · Java · Python · Integrações de sistemas · Dados
</p>

<p align="center">
  <a href="https://linkedin.com/in/viniciusalnogueira/">
    <img src="https://img.shields.io/badge/LinkedIn-viniciusalnogueira-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:vinicius.alnog@gmail.com">
    <img src="https://img.shields.io/badge/E--mail-vinicius.alnog%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="E-mail">
  </a>
  <a href="https://github.com/vinicius-alnog?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Repositórios-181717?style=flat-square&logo=github&logoColor=white" alt="Repositórios">
  </a>
</p>

## Sobre mim

Sou **Analista de Desenvolvimento Trainee na AEBEL**, maior grupo de saúde do Norte do Paraná, onde desenvolvo em **Node.js** e trabalho em **integrações entre sistemas** de um ambiente hospitalar, contexto em que confiabilidade, regra de negócio e rastreabilidade não são detalhes, são requisitos. Em 2026 fui o desenvolvedor responsável por um portal de solicitação de prontuário médico que está **em produção**, atendendo o público externo do hospital.

Cheguei ao desenvolvimento por um caminho menos comum: sou **formado em Administração pela UEL** e passei anos trabalhando com análise de dados, mapeamento de processos e projetos ágeis antes de escrever código profissionalmente. Hoje curso **Análise e Desenvolvimento de Sistemas na Unifil** e uso as duas formações juntas: entendo o processo antes de propor a solução técnica.

Antes da AEBEL, apliquei programação dentro da operação da **TCS**, onde desenvolvi automações em Python e um agente de IA para apoio às operações, com **+40% em indicador de qualidade operacional**.

> Antes de escrever a primeira linha, eu entendo o processo que ela vai mudar.

## Case profissional

Publico meu trabalho corporativo como **estudo de caso documentado**: o problema real, a decisão técnica com o custo que ela impôs, o que foi construído e o que mudou depois. Sem código-fonte, esquema de banco, endpoints, credenciais ou dado de paciente, os diagramas são desenhados para o documento e os exemplos são fictícios.

### [Portal de Solicitação de Prontuário - SAME](https://github.com/vinicius-alnog/case-solicitacao-prontuario-aebel)

Transformou a solicitação de cópia de prontuário do **Hospital Evangélico de Londrina** em um fluxo digital, rastreável e com prazo controlado. O processo anterior era presencial e a entrega final do documento clínico saía por **link de WhatsApp**: sem prazo de expiração, sem registro de quem baixou e sem nenhuma trilha de auditoria.

| | |
|---|---|
| **Meu papel** | Desenvolvedor responsável pelo sistema realizando a modelagem de dados, backend, frontend, integração institucional e implantação |
| **O que construí** | 15 tabelas em 16 migrations versionadas · 36 rotas divididas em **3 superfícies de acesso com posturas de segurança distintas** · 18 telas · 42 arquivos de teste automatizado |
| **Decisões técnicas** | Autenticação institucional lendo a identidade do MV, sem cadastro paralelo de colaborador · trilha de auditoria somente-inclusão imposta no próprio banco · validação de anexo pelos bytes iniciais em vez da extensão · rotinas agendadas de expiração, retenção e remoção definitiva |
| **Tecnologias** | `Node.js` `Express` `Oracle` `Knex` `JWT` `Socket.IO` `node-cron` `Jest` `Supertest` - interface em HTML, CSS e JavaScript sem framework |
| **Resultado** | Tempo médio de atendimento de **~20 dias para ~7 dias corridos** (≈65% de redução) · entrega fora do WhatsApp, com janela de download e registro de cada acesso · processo auditável de ponta a ponta · retenção de dado pessoal com prazo definido · operação conduzida pela equipe existente de 3 pessoas do SAME |

O repositório traz também a análise técnica, o registro de cada escolha de projeto com o preço que ela cobrou, a postura de proteção de dados e a ressalva metodológica sobre a comparação de prazos.

## Outros projetos pessoais/freelances

| Projeto | O que demonstra | Stack |
|---|---|---|
| **Studio Us** - landing page de um estúdio de unhas e cílios em Londrina | Página única em 8 seções desenhada para levar ao agendamento, dados estruturados de negócio local para busca | `Next.js` `React` `TypeScript` `Tailwind CSS` `GSAP` `Lenis` |
| **Agendamento de Salão de Beleza** - agendamento para nail e lash designer | Site para agendamento de atendimentos de salão de beleza focado no nicho de nail e lash design com regras de negócio específicas para o nicho | `Node.js` `Express` `PostgreSQL` `Knex` `React` `Vite` |
| **Midiadrop** - e-commerce boutique de camisas de futebol | API REST, modelagem relacional, frontend tipado e Spec-Driven Development (SDD) | `Node.js` `Express` `PostgreSQL` `React` `TypeScript` |
| **Bolão Copa 2026** - plataforma full-stack | Autenticação JWT, regras de fase de grupos e mata-mata, ranking em tempo real, ambiente containerizado | `Java` `Spring Boot` `React` `PostgreSQL` `Docker` |
| **Automação de Inscrições via WhatsApp** | Validação de comprovante PIX por OCR e escrita automática no Google Sheets, com deploy em container — em uso real | `Python` `OCR` `Google Sheets API` `Docker` |
| **Automação de Screenshots para Exportação em PDF (TCS)** | Captura e organização de evidências operacionais em ambiente de BPO real | `Python` `Bat` |

## Meu diferencial

Não venho só da técnica nem só do negócio, trabalho no encontro dos dois.

<table>
<tr>
<td width="33%" valign="top">

**Desenvolvimento**

- Node.js, Express e APIs REST
- Java e Spring Boot
- JavaScript e TypeScript
- React e interfaces responsivas
- Next.js e Tailwind CSS
- Oracle, PostgreSQL e SQL
- Testes automatizados
- Deploy em Linux com Nginx e PM2
- Docker, Git e versionamento

</td>
<td width="33%" valign="top">

**Processos e negócio**

- Levantamento de requisitos
- Mapeamento de processos
- Metodologias ágeis
- Especificação e documentação
- Integração entre sistemas
- Comunicação com áreas de negócio
- Ambiente hospitalar e corporativo

</td>
<td width="33%" valign="top">

**Dados, segurança e automação**

- Modelagem e tratamento de dados
- Python para automação
- Auditoria e rastreabilidade
- Retenção de dado pessoal e LGPD
- Power BI, dashboards e KPIs
- OCR e processamento de arquivos
- Aplicação de IA via API

</td>
</tr>
</table>

## Tecnologias

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111827" alt="JavaScript">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827" alt="React">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="SQL">
  <img src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white" alt="Jest">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111827" alt="Linux">
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx">
  <img src="https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white" alt="PM2">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=111827" alt="Power BI">
  <img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white" alt="Excel">
</p>

Também cuido da publicação, não só do código: subo aplicações em **servidor Linux**, sirvo com **Nginx** como proxy reverso e mantenho os processos Node em pé com **PM2**, com as rotinas agendadas e o versionamento de banco que o sistema precisa para continuar rodando depois do deploy.

## Da Administração para o software

**Administração (UEL)** - aprendi a olhar processo, custo e indicador antes de olhar ferramenta.

**Análise de dados e processos** - passei a transformar dado bruto em informação para decisão.

**TCS** - apliquei programação dentro da operação: automação em Python e um agente de IA, com +40% em indicador de qualidade.

**AEBEL** - hoje desenvolvo em Node.js e integro sistemas em ambiente hospitalar. Entreguei o portal de solicitação de prontuário do SAME, que tirou um documento clínico do WhatsApp e reduziu o prazo de atendimento em cerca de 65%.

**Análise e Desenvolvimento de Sistemas (Unifil)** - fundamentação formal do que já aplico no dia a dia.

Meus projetos não existem só para praticar sintaxe: os que estão aqui resolveram problemas reais e rodaram em produção.

## Formação

- **Análise e Desenvolvimento de Sistemas** — Unifil *(em andamento)*
- **Administração** — Universidade Estadual de Londrina (UEL)

## Direção profissional

Busco crescer em posições de:

`Desenvolvedor Back-end` · `Desenvolvedor Full Stack` · `Analista de Desenvolvimento` · `Integrações de Sistemas` · `Automação` · `Healthtech`

## Contato

- **LinkedIn:** [linkedin.com/in/viniciusalnogueira](https://linkedin.com/in/viniciusalnogueira/)
- **E-mail:** [vinicius.alnog@gmail.com](mailto:vinicius.alnog@gmail.com)

---

<p align="center">
  <em>Em transição, mas não em desvantagem.</em>
</p>
