---
title: "DevOps & Pipeline CI/CD"
image: 
  path: /assets/images/oatmeal-cookies-lg.jpg
  thumbnail: /assets/images/oatmeal-cookies-400x200.jpg
  caption: "Photo from [Erivando Sena](https://www.erivanosena.com.br)"
---

É um projeto holístico que engloba todas as fases da implantação de uma stack completa de DevOps, desde a transformação da cultura até a criação de uma esteira de software por meio de Pipeline CI/CD. 

Este projeto destaca minha expertise em remodelar processos, implementar tecnologias modernas e aprimorar a colaboração entre equipes, permitindo uma entrega de software mais eficiente, segura e com entrega de valor.

## Fase de Adoção da Cultura DevOps

O projeto começou com a mudança de paradigma, uma transformação cultural que alinhou as equipes de desenvolvimento e operações em busca de objetivos comuns. Adotamos práticas colaborativas, comunicação transparente e uma mentalidade de melhoria contínua. Essa mudança cultural foi essencial para estabelecer uma base sólida para a automação e a adoção das práticas DevOps e DevSecOps.

## Fase de Seleção e Implantação de Ferramentas DevOps

Nesta etapa, foram selecionadas e implementadas um conjunto de ferramentas DevOps e DevSecOps que atenderiam às necessidades do projeto. Cada ferramenta desempenhava um papel crucial em uma parte específica do ciclo de vida do desenvolvimento de software.

**GitLab**: Inicialmente o GitLab foi adotado como plataforma padrão para o controle de versão, gestão de projetos apenas, consolidando fluxos de trabalho e melhorando a colaboração.

**Harbor**: O Harbor foi adotado como o registro privado de contêineres, garantindo a qualidade e a integridade das imagens Docker usadas em todo o pipeline de entrega.

**Jenkins**: O Jenkins foi integrado como a ferramenta de integração contínua, entrega e integração contínua (CI/CD), automatizando os processos de construção, testes e implantação, aumentando a eficiência e a confiabilidade do desenvolvimento.

**SonarQube**: O SonarQube ficou a cargo aa análise estática de código, identificando vulnerabilidades e problemas de qualidade do código. Isso nos permitiu melhorar a segurança e a robustez do código produzido pelas equipes de desenvolvimento.

**Vault**: O Vault para o gerenciamento seguro de segredos e chaves, garantindo a segurança da infraestrutura e das configurações sensíveis.

**Consul**: Já o Consul foi adotado para a descoberta de serviços e o gerenciamento da rede e backend mantendo dados do Vault em um ambiente de alta disponibilidade garantindo maior confiabilidade e robustez tornando a comunicação entre os componentes mais eficiente e resiliente.

**Kubernetes**: O Kubernetes teve um papel importante como plataforma de orquestração de contêineres, permitindo também a aplicação dos agentes Jenkins para o processamento das pipelines de maneira otimizada. A integração dessas tecnologias permitiu a automação robusta e o gerenciamento eficaz dos fluxos de trabalho, proporcionando uma infraestrutura moderna e ágil.

**Wiki.js**: O Wiki.js foi adotao para criar uma base de conhecimento compartilhada, fornecendo informações e documentação essenciais para todas as equipes envolvidas.

**ELK Stack (Elasticsearch, Logstash, Kibana)**: Por fim a ELK Stack foi definiada para monitorar e analisar logs, fornecendo insights valiosos sobre o desempenho e a operação dos aplicativos.

## Fase de Conversão de Monolíticos em Contêineres e Pipeline CI/CD

Será uma necessidade constante transformar aplicações monolíticas legadas em contêineres Docker para uma maior flexibilidade e portabilidade. 
Para as fases de CI/CD, foram criadas pipelines que automatizou a construção, teste e implantação de aplicações. A cada mudança de código no repositório Git, o pipeline era acionado, permitindo uma entrega contínua e confiável de novas funcionalidades.

## Benefícios e Resultados

O projeto resultou em um ecossistema DevOps altamente sustentável e eficiente, onde a colaboração, automação e segurança eram prioridades. A entrega contínua possibilitou uma resposta ágil às necessidades dos usuários, e a análise estática de código reduziu significativamente os riscos de vulnerabilidades e bugs. A adoção de uma cultura DevSecOps garantiu que a segurança fosse incorporada em todas as etapas do ciclo de vida.

## Ferramenta na stack que desempenhou um papel crítico na eficiência do processo

* *GitLab*: Controle de versão e gestão de projetos com GitOps.
* *Harbor*: Garantia da qualidade e segurança das imagens Docker.
* *Jenkins*: Automação e agilidade na entrega de software.
* *SonarQube*: Melhoria da qualidade e segurança do código.
* *Vault*: Gerenciamento seguro de segredos e chaves.
* *Consul*: Descoberta e gerenciamento de serviços.
* *Kubernetes*: Orquestração e gerenciamento eficiente de contêineres.
* *Wiki.js* Compartilhamento de conhecimento e documentação.
* *ELK Stack*: Monitoramento, observabilidade e análise detalhada de logs.

Este projeto é um testemunho da minha capacidade de transformar cultura em código, alavancando tecnologias avançadas para criar ambientes de desenvolvimento e operações altamente colaborativos, ágeis e seguros. É um exemplo inspirador de como a colaboração entre equipes, a automação e a modernização tecnológica podem resultar em benefícios tangíveis para uma oganização.

## Localização do Projeto

Este projeto foi implementado com sucesso na instituição federal de ensino superior [Universidade da Integração Internacional da Lusofonia Afro-Brasileira](https://unilab.edu.br/) (UNILAB), localizada em Redenção, Ceará, Brasil. A T.I. da UNILAB conseguiu transformar sua cultura de desenvolvimento e operações, adotando as práticas DevOps em todas as etapas do ciclo de vida do software. A seleção cuidadosa das ferramentas e a implementação de uma infraestrutura de microsserviços baseada em Kubernetes permitiram que a universidade alcançasse maior agilidade, segurança e eficiência em suas atividades acadêmicas e administrativas.