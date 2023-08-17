---
title: "Stack de Observabilidade de Microsserviços"
image: 
  path: /assets/images/peanut-butter-cookies-lg.jpg
  thumbnail: /assets/images/peanut-butter-cookies-400x200.jpg
  caption: "Photo from [Portal Information Management](https://docmanagement.com.br)"
---

Este projeto abrangente focaliza a implantação de observabilidade e monitoramento em um ambiente de microsserviços, utilizando uma solução de código aberto construída sobre o Stack ELK (Elasticsearch, Logstash e Kibana). O objetivo é reunir métricas, logs e traces para oferecer uma visão unificada e insights práticos sobre o desempenho e a operação dos microsserviços.

## Definições e Tecnologias Open Source
O projeto se baseia em tecnologias open source para construir uma solução robusta de observabilidade. A stack ELK (Elasticsearch, Logstash e Kibana) é a base dessa solução, fornecendo capacidades avançadas de busca e armazenamento, processamento e visualização de dados. A Elastic Observability, que se integra com a stack ELK, acrescenta recursos específicos para métricas, logs e traces, oferecendo um pacote completo para monitoramento e análise.

## Cenário e Levantamento de Requisitos
O projeto começa com uma análise do cenário atual, identificando os microsserviços em execução, suas interações e as necessidades de monitoramento. Isso envolve uma avaliação detalhada das métricas críticas, dos tipos de logs gerados e da rastreabilidade de traces ao longo dos serviços. Com base nessas informações, os requisitos específicos para a solução de observabilidade são definidos.

## Instalação do Ambiente de Observabilidade
A etapa de instalação é um dos pilares deste projeto. Ela compreende a criação e configuração do ambiente de observabilidade usando a stack ELK e Elastic Observability bem como a construção e configuração do cluster Elasticsearch.

**Elasticsearch**: Inicialmente, foi implantado o Elasticsearch como parte de um cluster para armazenar os dados de métricas, logs e traces. Para atuar como um mecanismo de busca distribuído, projetado para operar em um ambiente de cluster, permitindo ao Elasticsearch nesta abordagem de clusterização dividir os dados em várias partes e distribuindo essas partes entre os nós do cluster, melhorando a eficiência no armazenamento, indexação e busca dos dados. O Elasticsearch também oferecerá recursos de replicação e fragmentação de dados para garantir alta disponibilidade, escalabilidade e desempenho em ambientes de grande volume de dados. Com sua capacidade de busca em tempo real e recursos avançados de pesquisa, o Elasticsearch foi parte fundamental no projeto para permitir a análise e a visualização dos dados coletados, contribuindo assim para a observabilidade e monitoramento eficaz dos microsserviços.

**Logstash**: Em seguida, foi configurado o Logstash para a coleta, transformação e enriquecimento de logs provenientes dos microsserviços e normalizando os dados para facilitar a análise posterior.

**Kibana**: A camada de visualização foi criada com o Kibana, permitindo que as equipes tenham insights visuais e interativos sobre os dados coletados através dos dashboards personalizados a serem configurados para apresentar informações relevantes sobre o desempenho e os problemas.

> **Elastic Observability**: Ao integrar o Elastic Observability para coleta de métricas e traces. Isso permitiu o monitoramento deem tempo real e a identificação de gargalos ou anomalias nos microsserviços.

## Configurações e Customizações
As configurações são ajustadas conforme as necessidades específicas do projeto, bem como a definição de alertas para notificar a equipe sobre problemas críticos e padrões indesejados.

> A implantação do ambiente de monitoramento e observabilidade é uma etapa crítica, garantindo que todos os componentes estejam configurados corretamente para coletar, armazenar e visualizar os dados de maneira eficaz.

O que faz necessário melhorias e manutenção constante como: instrumentação das aplicações, configuração das visualizações/alertas bem como documentações e versionamento dos códigos.

## Benefícios e Resultados
O projeto resulta em uma plataforma de observabilidade que oferece insights profundos sobre o desempenho dos microsserviços. A capacidade de rastrear métricas, analisar logs e seguir traces proporciona uma compreensão abrangente dos sistemas em execução. Isso permite uma detecção precoce de problemas, uma resolução mais rápida e uma melhoria contínua do desempenho geral.

Este projeto atesta minha capacidade de implementar uma solução de observabilidade em um ambiente de microsserviços, alavancando tecnologias de código aberto e garantindo insights valiosos para uma operação eficiente e eficaz.

## Localização do Projeto
Essa implementação de observabilidade e monitoramento foi realizada na [Universidade da Integração Internacional da Lusofonia Afro-Brasileira](https://unilab.edu.br/) (UNILAB), situada em Redenção, Ceará, Brasil. Com essa solução em funcionamento, a UNILAB possuirá uma visão unificada e prática do desempenho de seus microsserviços, o que contribuirá significativamente para suas operações acadêmicas e administrativas.