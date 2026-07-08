<p align="center">
  <img src="images/banner.png" alt="ATS Inteligente" width="100%">
</p>

<h1 align="center">ATS Inteligente</h1>

<p align="center">
Plataforma de recrutamento e seleção baseada em Inteligência Artificial.
</p>

# ATS Inteligente

> Plataforma de recrutamento e seleção baseada em Inteligência Artificial para automatizar a análise de currículos, o gerenciamento de candidatos e o atendimento inteligente.

O **ATS Inteligente** é um projeto desenvolvido para demonstrar como Inteligência Artificial e automação podem transformar o processo de recrutamento e seleção.

A plataforma automatiza desde o recebimento de currículos até a comunicação com candidatos, reduzindo atividades operacionais e apoiando a tomada de decisão por meio de agentes especializados de IA.

Atualmente o projeto é composto por dois módulos integrados:

### 📄 Avaliação Inteligente de Currículos

Workflow responsável por analisar currículos recebidos em PDF, comparar o perfil do candidato com a descrição da vaga e gerar um relatório técnico contendo recomendações para o recrutador.

Principais funcionalidades:

- Extração automática do conteúdo do currículo
- Comparação entre currículo e descrição da vaga
- Avaliação utilizando múltiplos agentes especializados
- Auditoria da qualidade do currículo
- Geração de relatório executivo
- Cadastro e atualização automática de candidatos
- Envio automático do resultado por e-mail

---

### 📬 Gerenciamento Inteligente de Contato

Workflow responsável pelo tratamento das solicitações enviadas através do portal do ATS.

Principais funcionalidades:

- Classificação automática das solicitações utilizando IA
- Tratamento de solicitações relacionadas à LGPD
- Consulta e gerenciamento de candidatos no banco de dados
- Exclusão automática de cadastros quando solicitado
- Respostas automáticas utilizando e-mails profissionais em HTML
- Atendimento totalmente automatizado

---

## Objetivos do Projeto

Este projeto foi desenvolvido com o objetivo de demonstrar a aplicação prática de Inteligência Artificial, automação de processos e integração entre sistemas para apoiar áreas de Recursos Humanos, recrutamento e seleção.

Além da automação operacional, a solução busca oferecer uma experiência mais ágil tanto para candidatos quanto para recrutadores, mantendo uma arquitetura modular preparada para futuras evoluções.

## 🏗️ Arquitetura Geral

O ATS Inteligente foi projetado de forma modular, permitindo que diferentes fluxos de automação trabalhem de maneira independente, mas integrados através de uma arquitetura baseada em Inteligência Artificial, banco de dados centralizado e automações desenvolvidas em n8n.

Atualmente a plataforma é composta por dois módulos principais:

### 📄 ATS CV Evaluation

Responsável pela avaliação inteligente de currículos utilizando múltiplos agentes especializados.

Fluxo resumido:

Currículo (PDF)
→ Extração de texto
→ Agentes de IA
→ Comparação CV × Vaga
→ Relatório
→ Supabase
→ E-mail

---

### 📬 ATS Contact Management

Responsável pelo gerenciamento inteligente das solicitações enviadas pelos candidatos.

Fluxo resumido:

Formulário
→ Classificação por IA
→ Regras de negócio
→ Supabase
→ Redis
→ E-mail
