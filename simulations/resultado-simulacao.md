# Simulação de Pipeline DevSecOps

## Problema

Uma chave de API foi inserida diretamente no código-fonte.

## Controle que detectou

Gitleaks.

## Resultado

O pipeline foi interrompido automaticamente.

## Ação Tomada

- Remoção da chave do código.
- Armazenamento em GitHub Secrets.
- Novo commit realizado com sucesso.