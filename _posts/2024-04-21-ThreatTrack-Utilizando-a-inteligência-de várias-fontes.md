---
layout: post
title:  "ThreatTrack - Utilizando a inteligência de várias fontes"
date:   2024-04-21 14:00:00
cover: /blog/assets/images/posts/ThreatTrack_Flow.gif
categories: tool
---

#### ThreatTrack
     
ThreatTrack é um projeto em Python que tem como objetivo ser uma ferramenta de consulta e análise de segurança em IPs públicos e domínios, utilizando a API do Shodan (shodan.io) como base.
O script é projetado para coletar informações detalhadas sobre IPs e domínios, destacando potenciais vulnerabilidades relacionadas às versões de tecnologias mapeadas pelo Shodan.
Além disso, ele se integra aos bancos de dados do NVD (National Vulnerability Database) ao ExploitDB e GitHub, permitindo a consulta das CVEs mapeadas em busca de possíveis exploits e provas de conceitos (PoC) associados.
 
#### Características
     
+ Coleta de informações sobre IPs e Domínios utilizando a API Shodan.io.
+ Identificação de CVE's com base nas versões de tecnologias mapeadas pelo Shodan.
+ Consulta de CVE's nas fontes de dados: NVD, ExploitDB e GitHub.

#### Fluxo de consulta de dados da ferramenta

![alt text](https://raw.githubusercontent.com/Ls4ss/blog/main/assets/images/posts/ThreatTrack_Flow.gif)

# Building Payload

![alt text](https://raw.githubusercontent.com/Ls4ss/ThreatTrack/main/example/tt_help.png)
