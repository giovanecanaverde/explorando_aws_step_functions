# Fundamentos de Cloud com AWS 🚀

E aí! Esse repositório foi criado para organizar e compartilhar tudo o que aprendi durante o **Bootcamp GFT - Fundamentos de Cloud com AWS** na DIO. Aqui estão as minhas anotações, os conceitos que estudei e os resumos práticos de cada módulo para fixar o conhecimento e servir de consulta futura.

O objetivo principal foi entender a infraestrutura da AWS, como os serviços se conectam e como subir recursos na nuvem de forma segura, eficiente e controlando os custos.

---

## 📖 O que foi aprendido por módulo

### 1. Introdução à AWS e Conceitos Básicos
* **O que é Nuvem:** Entendimento global de computação em nuvem, modelos de serviço (IaaS, PaaS, SaaS) e modelos de implantação.
* **Primeiros Passos na AWS:** Como criar e configurar a conta global, ativar as camadas de segurança essenciais (como o MFA) e acompanhar as métricas de faturamento para não estourar o orçamento (Controle de Custos).

### 2. Computação na Nuvem com EC2
* **Instâncias EC2:** Entendi como funcionam os servidores virtuais na nuvem (Elastic Compute Cloud), os diferentes tipos de instâncias para cada necessidade de negócio e como funciona a otimização de recursos.
* **Armazenamento de Blocos:** Introdução ao Amazon EBS (discos rígidos virtuais atrelados às instâncias) e como ele trabalha junto com o S3.

### 3. Criando Recursos na AWS (Prática)
Aqui foi a hora de colocar a mão na massa no console da AWS:
* **Minha primeira instância EC2:** Subi um servidor virtual do zero.
* **Meu primeiro Bucket no Amazon S3:** Criei um repositório de armazenamento de objetos para guardar arquivos na nuvem.
* **Minha primeira função com Amazon Lambda:** Criação de uma função *Serverless* (sem servidor), executando código sob demanda de forma super simples.

### 4. Redes na AWS
Entender como os dados trafegam com segurança:
* **Amazon VPC & Subnets:** Como isolar logicamente a nossa rede dentro da AWS e dividir essa rede em partes públicas e privadas.
* **Security Groups:** Funcionam como o nosso firewall de proteção para controlar quem pode entrar e sair das instâncias.
* **Route 53, CloudFront & Load Balancer:** Como gerenciar DNS, distribuir conteúdo de forma ultra rápida pelo mundo (CDN) e balancear a carga de acessos entre múltiplos servidores para o sistema nunca cair.

### 5. Banco de Dados na AWS
* **Bancos Relacionais (Amazon RDS):** Facilidade de criar e gerenciar bancos como MySQL ou PostgreSQL sem se preocupar com manutenção física.
* **Bancos Não-Relacionais (Amazon DynamoDB):** Banco NoSQL de altíssima performance e escalabilidade absurda.
* **Estratégias de Backup:** Importância de planejar rotinas de cópias de segurança e recuperação de desastres para proteger as informações.

### 6. Serviços de Armazenamento e CDN
* **Ciclo de Vida do Armazenamento:** Diferença prática entre o Amazon S3 (arquivos acessados a qualquer momento) e o Amazon Glacier (armazenamento de arquivamento frio, muito mais barato, voltado para dados que raramente mexemos).
* **Aplicações Práticas:** Integração dos conceitos de nuvem com código (como JavaScript) para criar arquiteturas modernas e prontas para o mercado industrial.

---

## 🛠️ Tecnologias e Ferramentas Exploradas
* **AWS Console** (EC2, S3, Lambda, VPC, RDS, DynamoDB)
* **Segurança em Nuvem** (IAM, Security Groups)
* **Arquitetura Serverless**

---

*Repositório construído para fins didáticos e conclusão de módulo na DIO!*
