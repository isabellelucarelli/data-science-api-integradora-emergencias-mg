# 📊 Minas Emergência | Inteligência de Dados & API Integradora

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Pronto_para_Produção-009688)](https://fastapi.tiangolo.com/)

> **Módulo de Ciência de Dados e API de Integração para o Ecossistema de Ajuda Humanitária Minas Emergência.**

### ⚠️ Aviso: Projeto em Construção
Este repositório está em **fase de desenvolvimento ativo**. As estruturas de pastas e os scripts estão sendo implementados gradualmente para atender às demandas emergenciais da Zona da Mata Mineira (2026).

Este repositório contém a inteligência analítica e a camada de serviços (API) desenvolvida para o projeto **Minas Emergência**. O objetivo central é transformar dados brutos em ações estratégicas para mitigar os impactos das enchentes na Zona da Mata Mineira (2026).

## 📌 Visão Geral do Projeto
O Minas Emergência é uma articulação Open Source que une desenvolvedores voluntários e o poder público (**Prefeitura de Juiz de Fora**). 

## 🔗 Ecossistema Minas Emergência
Para compreender a arquitetura completa da plataforma e as outras frentes de desenvolvimento (Frontend e Core), acesse o repositório principal do projeto:

* **Repositório Central (Core):** [Minas Emergência - Idealizado por Guilherme Bartmann](https://github.com/GuilhermeBartmann/MinasEmergencia)

Este módulo específico funciona como o "cérebro" do ecossistema, sendo a **Fonte Única de Verdade (SSOT)** para logística de abrigos, pontos de coleta e prevenção de fraudes.

## 🏗️ Pilares de Atuação (Ciência de Dados)
Como responsável pela área de dados neste módulo, meu trabalho foca em quatro pilares:

* **Tratamento de Dados & Geoprocessamento:** Tratamento de dados heterogêneos e enriquecimento de conjuntos de dados via geocodificação para viabilizar análises espaciais e mapeamento de risco em alta precisão.
* **Modelagem Preditiva & Detecção de Anomalias:** Desenvolvimento de algoritmos de Machine Learning para identificação de padrões de fraude em fluxos de doações (PIX) e automação da validação de cadastros de ajuda.
* **Engenharia de Analytics & Otimização:** Aplicação de inferência estatística para otimização logística, identificando gargalos críticos entre a oferta de suprimentos e a demanda real dos abrigos.
* **Entrega de Produto Final (Inteligência como Serviço):** Desenvolvimento de um **Motor de Inferência Analítica** via FastAPI. Este produto atua como uma camada de inteligência desacoplada que processa dados brutos do ecossistema e devolve **Pontuações de Risco** e **Matrizes de Priorização**, permitindo decisões automatizadas e baseadas em dados em tempo real.

## 📁 Estrutura do Repositório
* `api/`: Implementação da API e definição das rotas de dados.
* `data/`: Governança de dados (armazenamento de arquivos `brutos` e `processados`).
* `notebooks/`: Laboratório de pesquisa, Análise Exploratória de Dados (EDA) e prototipagem de modelos.
* `src/`: Scripts de produção, pipelines de ETL e algoritmos de automação.
* `dashboard/`: **[Entrega Final]** Interface visual e painéis de indicadores (KPIs) para suporte à decisão.
* `product/`: 🚀 **[Produto Principal]** Camada de entrega do produto de dados integrado (Dados como Serviço).

## 🤝 Governança e Autoria Técnica
Este é um projeto colaborativo e transparente. A estrutura e o código presentes neste repositório de Ciência de Dados são de minha autoria, desenvolvidos sob um modelo de mentoria e liderança técnica.

* **Idealização:** [Guilherme Bartmann](https://github.com/GuilhermeBartmann)
* **Liderança Estratégica e Orientação Técnica:** [Ricardo da Rocha](https://github.com/ricardodarocha)
* **Orientações Técnicas:** [Carlos Alexandre](https://github.com/carlosalexandre94)
* **Desenvolvedora de Ciência de Dados:** [Isabelle Lucarelli](https://github.com/isabellelucarelli)
  
* **Colaboradores API Integradora:**
  - [Guilherme Bartmann](https://github.com/GuilhermeBartmann)
  - [Ricardo da Rocha](https://github.com/ricardodarocha)
  - [Carlos Alexandre](https://github.com/carlosalexandre94)
  - [Isabelle Lucarelli](https://github.com/isabellelucarelli)
  - [Ana Luiza Bicalho] 
  - [Pedro H. Diniz] 
  - [Izabela Ribas](https://github.com/IzabellaRibas)
  - [Renato Lobo] 
  - [Eduardo Batista] 

O fluxo de trabalho baseia-se na execução de tarefas (Issues) e metas definidas pela liderança do projeto, garantindo que as soluções de dados estejam alinhadas às necessidades reais da Defesa Civil e da comunidade.

---
**Status do Projeto:** 🛠️ Em desenvolvimento ativo.  
**Licença:** Este trabalho é distribuído sob a licença [MIT](LICENSE).
