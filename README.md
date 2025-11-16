# 🤖 Podcast Automatizado com Inteligência Artificial

![Badge de Status](https://img.shields.io/badge/Status-Concluído/Em%20Desenvolvimento-brightgreen)

Este repositório documenta o processo completo de criação e produção de um podcast utilizando **exclusivamente ferramentas de Inteligência Artificial (IA)**. O objetivo é demonstrar um fluxo de trabalho (workflow) moderno, eficiente e de baixo custo, minimizando a necessidade de equipamentos tradicionais de gravação e edição manual.

## 🌟 O Conceito

O projeto visa transformar a ideia de um podcast em um episódio finalizado com a máxima velocidade, provando que a IA pode ser uma co-produtora poderosa. O processo foi dividido em etapas claras, cada uma potencializada por uma tecnologia de IA específica.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

| Etapa da Produção | Ferramenta/Tecnologia de IA | Função no Projeto |
| :--- | :--- | :--- |
| **I. Ideação & Roteiro** | Chat GPT| Geração de ideias, estruturação do episódio e escrita dos scripts iniciais. |
| **II. Geração de Voz** | ElevenLabs | Conversão do roteiro em áudio realista com vozes sintéticas de alta fidelidade (Text-to-Speech). |
| **III. Geração da Capa** | Gemini | Transformação da ideia do Podcast em um estilo visual, moldando o modelo e identidade. |
| **IV. Pós-produção** | CapCut | Nivelamento de volume (masterização) e ajuste de qualidade final. |

## 🚀 Workflow

O fluxo de trabalho principal é executado através de uma sequência de prompts para integrar asrramentas de IA:

1.  **Geração do Script:** O prompt de IA é fornecido ao LLM para criar o texto base (`/src/scripts/script_gerado.txt`).
2.  **Conversão de Áudio:** O script de texto é enviado ao serviço de TTS. O áudio mp3 é retornado e salvo (`/audio/raw_episode.mp3`).
4.  **Geração da Capa:** Foi realizado um prompt para geração de uma capa para o PodCast (`/src/scripts/script_capa.txt`) e o arquivo gerado (`/Images/capa_podcast.jpg`).
5.  **Enhancement:** O arquivo mp3 é submetido à ferramenta de pós-produção para tratamento de ruído e nivelamento. O episódio finalizado (`/audio/episodio_podcast.mp3`) é gerado.

Você pode encontrar os scripts de automação em `/src`.


