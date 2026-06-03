# Estufa Inteligente para Agricultura Espacial

## Global Solution 2026

### Integrantes

* Eduado Mazelli - RM:553236 

* Lucas Masaki - RM:553084 

* Pedro Henrique Lima - RM:552746 

* Carolina Cavalli - RM:552925 

* Joseh Gabriel Trimboli Agra - RM: 553094 
---

## Descrição do Projeto

Este projeto apresenta uma solução para agricultura espacial baseada em uma estufa inteligente autônoma.

A proposta utiliza sensores, câmeras, inteligência artificial e agentes automatizados para realizar atividades de:

* Plantio;
* Irrigação;
* Adubação;
* Colheita;
* Monitoramento remoto.

O sistema permite que operadores acompanhem o estado das plantações por meio de um aplicativo móvel conectado à infraestrutura espacial.

---

## Objetivo da Segurança

Como a solução depende de comunicação remota e processamento de dados críticos, foram incorporadas práticas de DevSecOps para aumentar a proteção durante todo o ciclo de desenvolvimento.

---

## Controles Implementados

### Gestão de Segredos

Utilização de GitHub Secrets para armazenamento seguro de:

* Chaves de API;
* Tokens;
* Credenciais de banco de dados.

### Scan Automatizado

Utilização do Gitleaks para identificação de:

* Senhas expostas;
* Tokens;
* Chaves privadas;
* Credenciais sensíveis.

---

## Pipeline DevSecOps

```text
Desenvolvedor
      ↓
GitHub
      ↓
GitHub Actions
      ↓
Gitleaks
      ↓
Build
      ↓
Deploy
      ↓
Aplicação
```

### Simulação Realizada

Foi realizado um teste de exposição de credenciais dentro do código-fonte.

O Gitleaks detectou automaticamente o segredo e interrompeu o pipeline, impedindo o deploy da aplicação.

---

## ODS Atendidos

ODS 2 – Fome Zero

ODS 9 – Indústria, Inovação e Infraestrutura

ODS 12 – Consumo e Produção Responsáveis

---

## Tecnologias Utilizadas

* GitHub
* GitHub Actions
* Gitleaks
* Docker
* Inteligência Artificial
* Sensores IoT
* Aplicação Mobile

---

## Conclusão

A integração de DevSecOps permitiu garantir maior segurança para uma solução crítica voltada ao ecossistema espacial, demonstrando a importância da segurança desde as primeiras etapas do desenvolvimento.

