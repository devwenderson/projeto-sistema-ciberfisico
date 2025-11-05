---
marp: true
title: Introdução a CPS, AADL e ROS
author: Ana Barbosa, Wenderson Nascimento
keywords: ciberfisico, ros, aadl
theme: barbosa
class: style_a
paginate: true
_paginate: false
footer: 2025 © IFRN CNAT
---
<!-- _class: title -->

<!-- Técnicas e Ferramentas para Modelagem e Análise de Comunicação em Sistemas Ciberfísicos -->

# Introdução a CPS, AADL e ROS

Ana Barbosa, Wenderson Nascimento

---

## Cyber-physical Systems (CPS)

O termo *Sistemas Ciberfísicos* se refere aos sistemas com integração computacional e capacidades físicas que conseguem interagir com humanos de diferentes formas.

Pesquisas voltadas para sistemas ciberfísicos tem como objetivo integrar principios e conhecimento entre computação e engenharia para desenvolver uma ciência de sistemas ciberfísicos e tecnologias de suporte relacionadas.

---
<!-- _class: style_b -->
### Indústria e Acadêmia

Atualmente, governos e inodustrias vêem investindo em tecnologias de sistemas ciberfísicos de longo prazo. Por exemplo, a União Europeia lançou um iniciativa tecnologica conjunta de nações europeias chamada *Advanced Research and Technology for Embedded Intelligence Systems* (ARTEMIS).

---
<!-- _class: style_b -->

Iniciativas semelhantes vêem sendo implementadas em outros países, como EUA, Japão, China, Coreia do Sul e Alemanha.

Existem diversas oportunidades de pesquisa e desenvovimento como:

* Biomedicia e Saúde
* Transporte Aéreo *NextGen*
* Energia Renovável e Redes Elétricas Inteligentes
* Internet Industrial das Coisas (IIoT)

---

## Architecture Analysis & Design Languange (AADL)

A AADL é uma linguagem de modelagem, utilizada para modelar e analisar arquiteturas de sistemas ciberfísicos e embarcados.

Ela é eficiente para analises baseadas em modelos e especificações de sistemas embarcados complexos em tempo real. Também suporta análise e previsão antecipada de qualidades criticas de sistemas, como desempenho, escalonabilidade e confiabilidade.

---
<!-- _class: style_b -->

### Abstração de Componente

Na AADL, um componente é caracterizado por seu nome único, interfaces, propiedades, subcomponentes e interações. As abstrações de componentes são separados em três categorias:

* Software de Aplicação
* Plataforma de Execução (Hardware)
* Composto

---

### Análise de Arquitetura

A AADL pode ser usada para modelar e analisar sistemas em uso, prototipar e integrar novos sistemas. Com a linguagem principal, um conjunto de propriedades pode ser declaradas, que pode incluir novas propriedades para outros componenetes ou elementos, como portas e conexões.

---
<style scoped>section { font-size: 20px; }</style>

<!-- _class: style_c -->
## Referências
*The Architecture Analysis & Design Language (AADL): An Introduction.* Disponível em: https://apps.dtic.mil/sti/html/tr/ADA455842/

*Presentation of the AADL: Architecture Analysis and Design Language.* Disponível em: https://beru.univ-brest.fr/~singhoff/ENS/UE_VFS/CM/part1_introducing_aadl.pdf

*Cyber-physical Systems.* Disponível em: https://ieeecss.org/sites/ieeecss/files/2019-07/IoCT-Part3-02CyberphysicalSystems.pdf