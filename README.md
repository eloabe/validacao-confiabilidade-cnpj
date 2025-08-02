# Pipeline de Validação e Confianbilidade de Dados CNPJ

## 🚀 Visão Geral

Este projeto tem como objetivo construir um pipeline de engenharia de dados para a **validação e garantia da confiabilidade de dados cadastrais de empresas brasileiras (CNPJ)**. 

Utilizando múltiplas APIs públicas, o pipeline extrai, transforma e cruza informações sobre o cadastro empresarial para assegurar que os dados estejam corretos, atualizados e consistentes — uma base essencial para fintechs que precisam confiar nesses dados antes de realizar análises de risco, concessão de crédito ou outras operações financeiras.

---

## 🎯 Objetivos Técnicos

- Extrair dados de APIs públicas de cadastro empresarial, como Receitaws e BrasilAPI  
- Realizar tratamento e unificação dos dados utilizando PySpark no Databricks  
- Implementar regras de validação cruzada para detectar inconsistências cadastrais (exemplo: divergência de CNAE, situação cadastral ou endereço)  
- Gerar métricas que indicam o nível de confiança nos dados de cada empresa  
- Armazenar os dados organizados em camadas (bronze, silver, gold) usando Delta Lake para escalabilidade e performance  
- Documentar todo o processo para facilitar manutenção e escalabilidade

---

## 💡 Diferenciais do Projeto

- Uso de múltiplas fontes de dados reais e gratuitas para enriquecer o cadastro de empresas  
- Foco em garantir qualidade e confiabilidade dos dados, requisito crítico para fintechs  
- Aplicação de arquitetura moderna de dados com Delta Lake  
- Pipeline modular, reutilizável e pronto para ser ampliado com etapas futuras, como avaliação de risco ou machine learning

---

## 🛠 Tecnologias Utilizadas

- Databricks 
- Apache Spark (PySpark)  
- Delta Lake  
- Python (bibliotecas requests, json)  
- APIs públicas (Receitaws, BrasilAPI, entre outras)

---

## 📁 Estrutura do Projeto

