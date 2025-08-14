# 🧪 Relatório Técnico – Ferramentas de Nuvem AWS  
**Destinatário:** Abstergo Industries  
**Autor:** Rodrigo Pereira Pepato. 
**Data:** 14 de agosto de 2025  

---

## 🧾 Introdução

Este relatório técnico tem como objetivo apresentar três ferramentas de computação em nuvem da Amazon Web Services (AWS) que podem ser aplicadas em contextos estratégicos da indústria farmacêutica, com foco em inovação, segurança e escalabilidade. Cada ferramenta é descrita com seu propósito principal e um caso de uso relevante para a Abstergo Industries, considerando cenários comuns à área de pesquisa, desenvolvimento e operação farmacêutica.

---

## 🧪 Descrição do Projeto

A seleção das ferramentas foi baseada na necessidade de:

- Armazenamento seguro e escalável de dados laboratoriais e clínicos.
- Monitoramento e automação de ambientes de produção e testes.
- Integração com serviços analíticos e sistemas legados da organização.

As ferramentas abordadas neste relatório são:

1. **Amazon S3**
2. **AWS Lambda**
3. **Amazon CloudWatch**

---

## ☁️ Ferramentas AWS

### 1. Amazon S3 (Simple Storage Service)

- **Foco da ferramenta:**  
  Armazenamento de objetos com alta durabilidade e escalabilidade.

- **Descrição do caso de uso:**  
  A Abstergo Industries pode utilizar o Amazon S3 para armazenar grandes volumes de dados clínicos, como imagens de exames, relatórios de laboratório e registros históricos de pacientes e estudos. Os dados ficam criptografados, com controle de acesso granular, e podem ser facilmente integrados a outras ferramentas analíticas ou de machine learning para estudos avançados. O S3 também permite versionamento de arquivos e recuperação em caso de exclusão acidental.

---

### 2. AWS Lambda

- **Foco da ferramenta:**  
  Execução de código sem necessidade de gerenciar servidores (serverless).

- **Descrição do caso de uso:**  
  A AWS Lambda pode ser usada para automatizar tarefas no pipeline de desenvolvimento da Abstergo, como o processamento de dados ao serem enviados ao S3 (ex: conversão de arquivos, extração de metadados, verificação de integridade). Também pode ser utilizada em conjunto com APIs para responder a eventos em tempo real, como a notificação de falhas em experimentos ou o início de novos processos laboratoriais.

---

### 3. Amazon CloudWatch

- **Foco da ferramenta:**  
  Monitoramento e observabilidade de aplicações e infraestrutura.

- **Descrição do caso de uso:**  
  A CloudWatch oferece à Abstergo uma visão detalhada da performance de aplicações, serviços e infraestrutura na nuvem. Pode ser utilizada para criar alarmes quando determinados limites forem atingidos (ex: uso de memória em servidores de pesquisa), registrar métricas de experimentos e visualizar dashboards que auxiliam nas decisões operacionais e estratégicas. Ideal para manter a estabilidade e segurança dos sistemas de produção farmacêutica.

---

## ✅ Conclusão

As ferramentas aqui apresentadas são altamente recomendadas para atender às necessidades tecnológicas da Abstergo Industries, especialmente em um cenário que exige automação, segurança e escalabilidade.

- O **Amazon S3** oferece uma base sólida para o armazenamento de dados sensíveis.  
- O **AWS Lambda** permite a criação de fluxos inteligentes e automatizados sem overhead de infraestrutura.  
- O **Amazon CloudWatch** garante visibilidade e controle sobre os processos digitais da empresa.

Ao integrar essas soluções, a Abstergo estará melhor preparada para escalar seus sistemas, garantir a conformidade e acelerar inovações na área farmacêutica.
