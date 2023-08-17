---
title: "Cluster Kubernetes"
image: 
  path: /assets/images/chocolate-chip-cookies-lg.jpg
  thumbnail: /assets/images/chocolate-chip-cookies-400x200.jpg
  caption: "Photo from [Buddy](https://buddy.works)"
---

O Kubernetes é uma plataforma de código aberto que facilita a automação, o escalonamento, a implantação de aplicativos em containers. Ao adotar essa tecnologia, as equipes de T.I. podem gerenciar melhor seus serviços e aplicações, tornando o ambiente mais ágil, flexível e produtivo.

Trata-se de um projeto abrangente que aborda todas as fases do ciclo de vida de implantação e gerenciamento de um cluster Kubernetes em ambiente on-premises, desde a concepção até a configuração final utilizando ferramenta de gerenciamento Open Source KubeSphere. Esse projeto favorece a equipe de operation a manter uma infraestrutura moderna e escalável, permitindo a orquestração eficiente de containers em um ambiente controlado.

## Fase de Planejamento

Na fase inicial de planejamento, foi realizada uma análise detalhada das necessidades e requisitos do projeto. Trabalhei em estreita colaboração com as partes interessadas para entender as metas de negócios, a carga de trabalho esperada e as expectativas de escalabilidade e disponibilidade. Essa fase resultou em um plano detalhado que delineava os recursos de hardware necessários, a topologia de rede, os requisitos de segurança e a abordagem geral para a implementação do Kubernetes.

## Fase de Criação

Após a definição do plano, iniciou-se com a criação da infraestrutura. Isso envolveu a aquisição e configuração dos servidores físicos para hospedar o cluster, bem como a instalação e configuração do sistema operacional necessário. Além disso, foram implementadas práticas de alta disponibilidade para garantir que o cluster permanecesse operacional em caso de falhas de hardware ou software.

## Fase de Implantação

Com a infraestrutura preparada, teve início a fase de implantação do cluster Kubernetes. Foram utilizadas ferramentas de automação IaC para facilitar o processo de implantação, garantindo consistência e reduzindo possíveis erros humanos. Foram definidos os nós workers e Control Plane, configurado a rede do cluster e o Ingress Controller responsável por gerenciar as regras de roteamento de tráfego para os diferentes serviços. Essa fase também envolveu a configuração de armazenamento persistente NFS, políticas de segurança, SSl e outras configurações personalizadas.

## Fase de Configuração com KubeSphere

A etapa de configuração com KubeSphere trouxe a simplicidade de gerenciamento e aprimoramento das operações do cluster Kubernetes. Utilizando a ferramenta KubeSphere para fornecer uma interface amigável para facilitar para a equipe de operações e devops a administração, monitoramento e operação de aplicativos em contêineres durante a manutenção das pipelines CI/CD, políticas de acesso, escalabilidade automática e integração com sistemas de monitoramento e registro de logs.

## Fase de Concepção e Gerenciamento Contínuo

O projeto não termina com a implantação. O ciclo de vida completo de concepção e gerenciamento contínuo é uma parte vital do processo. Foi necessário estabelecer práticas de DevOps para permitir a entrega contínua de aplicativos, a atualização do cluster e a melhoria contínua. Isso incluiu a configuração de fluxos de trabalho automatizados de CI/CD, testes automatizados e a implementação de práticas de DevSecOps para garantir a segurança contínua do ambiente.

## Resultado e Benefícios
 
A conclusão bem-sucedida deste projeto resultou em um cluster Kubernetes totalmente funcional, pronto para hospedar aplicativos de maneira eficiente e escalável. A integração do KubeSphere simplificou o gerenciamento do cluster, permitindo que as equipes de devops e operações colaborem de maneira eficaz juntamento com as squads de desenvolvimento. A arquitetura on-premises garante controle total sobre a infraestrutura, mantendo a segurança dos dados e a conformidade regulatória.

Este projeto demonstra minha experiência com as ferramentas IaC utilizadas (Ansible, Terrafom), métodos DevOps, ferramentas e containerização utilizando Docker e outras tecnologias desde o planejamento até a operação contínua. Sinto-me orgulhoso de ter entregado com sucesso uma solução moderna de infraestrutura para contêineres que atende às demandas de escalabilidade, economia, desempenho e sustentabilidade digital.

## Localização do Projeto

Este projeto foi implementado com sucesso na instituição federal de ensino superior [Universidade da Integração Internacional da Lusofonia Afro-Brasileira](https://unilab.edu.br/) (UNILAB), localizada em Redenção, Ceará, Brasil. Com a operação de três clusters Kubernetes, a UNILAB agora possui uma infraestrutura de microsserviços moderna e escalável para sustentar suas aplicações nas atividades acadêmicas e administrativas.