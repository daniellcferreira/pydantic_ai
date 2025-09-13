# AI Presentations & RAG Pipelines

![Python](https://img.shields.io/badge/Python-Linguagem-blue?style=flat-square&logo=python)
![FastEmbed](https://img.shields.io/badge/FastEmbed-Embeddings-orange?style=flat-square&logo=vectorworks)
![Qdrant](https://img.shields.io/badge/Qdrant-Vector%20Database-purple?style=flat-square&logo=qdrant)
![Pydantic AI](https://img.shields.io/badge/PydanticAI-Agent%20Framework-green?style=flat-square&logo=pydantic)
![Gemini](https://img.shields.io/badge/Google%20Gemini-LLM-lightblue?style=flat-square&logo=google)
![Docling](https://img.shields.io/badge/Docling-Document%20Parsing-brown?style=flat-square&logo=bookstack)
![PIL](https://img.shields.io/badge/PIL-Image%20Processing-yellow?style=flat-square&logo=python)
![Tavily](https://img.shields.io/badge/Tavily-Web%20Search-red?style=flat-square&logo=googlechrome)

## Descrição

Este projeto reúne um conjunto de notebooks que exploram a integração de agentes inteligentes, bancos de vetores, geração de embeddings e automação de apresentações empresariais.  
O objetivo é criar pipelines que permitam transformar documentos brutos em relatórios inteligentes, roteiros de slides bem estruturados e até imagens criativas geradas por IA.  

A base do projeto combina diferentes tecnologias modernas como **Pydantic AI**, **Google Gemini**, **Qdrant** e **FastEmbed**, possibilitando não apenas consultas rápidas a relatórios armazenados, mas também a criação de apresentações automáticas baseadas em perguntas estratégicas.  
Além disso, há integração com **Docling** para converter documentos em Markdown estruturado e com **Tavily** para enriquecer os resultados com informações externas buscadas na internet.  

O projeto demonstra como unir **busca semântica**, **validação de agentes**, **roteirização de apresentações** e **geração multimodal** (texto e imagem) em um único fluxo de trabalho.  
Assim, ele pode ser aplicado em contextos como relatórios corporativos, dashboards interativos, apresentações executivas e até mesmo em treinamentos internos.  

Em resumo, trata-se de uma arquitetura de **RAG (Retrieval-Augmented Generation)** expandida, que vai além de apenas responder perguntas, pois também organiza e apresenta os resultados em formatos práticos e visuais.  

## Funcionalidades

- Conversão de documentos em **Markdown estruturado** usando a biblioteca Docling.  
- Divisão do conteúdo em **chunks** para melhor indexação e recuperação posterior.  
- Geração de **embeddings vetoriais** de alta performance com FastEmbed.  
- Armazenamento persistente de dados em **Qdrant**, permitindo consultas semânticas rápidas.  
- Criação de agentes inteligentes com **Pydantic AI**, capazes de:  
  - Validar resultados de maneira dinâmica com o uso de `ModelRetry`.  
  - Elaborar roteiros de slides completos, com título e notas explicativas.  
  - Responder perguntas complexas sempre baseadas em dados indexados.  
- Integração com a **API Gemini**, usada tanto para respostas textuais quanto para geração de imagens.  
- Geração de imagens criativas e personalizadas a partir de prompts descritivos.  
- Criação de um agente roteirista, especializado em produzir apresentações estruturadas.  
- Uso de tags especiais `::: {.notes}` para separar o roteiro de fala dos conteúdos exibidos.  
- Integração com o **Tavily Search Tool** para buscar informações adicionais na internet.  
- Capacidade de enriquecer relatórios com dados atualizados de fontes externas.  
- Estrutura modular de notebooks para organizar cada parte do processo.  
- Persistência local dos bancos de vetores em diretórios dedicados.  
- Execução controlada com **delays** para evitar sobrecarga nas consultas.  
- Pipeline de busca com embeddings otimizados para recuperação de informações.  
- Automatização de relatórios empresariais a partir de múltiplas fontes.  
- Transformação de dados corporativos em **apresentações executivas**.  
- Ferramentas de **pré-processamento** para limpeza e organização de conteúdo.  
- Uso de agentes buscadores especializados para queries externas.  
- Compatibilidade com fluxos interativos de perguntas e respostas.  
- Aplicabilidade em cenários de **business intelligence** e **análise estratégica**.  
- Criação de uma camada de **IA explicável**, com roteiros claros e detalhados.  
- Demonstração prática de como combinar RAG, agentes e multimodalidade em um único projeto.  
