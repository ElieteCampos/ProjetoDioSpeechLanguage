# Azure Speech Studio e Language — Análise de Fala e Linguagem Natural

Este projeto foi desenvolvido como parte da formação **Microsoft Azure AI Fundamentals (AI-900)** da DIO.

O objetivo deste laboratório foi praticar conceitos relacionados a **Inteligência Artificial aplicada à fala e à linguagem natural**, utilizando serviços do Microsoft Azure.

Durante o projeto foram explorados recursos relacionados a:

- Azure Speech;
- Speech Studio;
- Microsoft Foundry;
- Azure AI Language;
- Análise de sentimentos;
- Mineração de opiniões;
- Processamento de Linguagem Natural (NLP).

Durante a realização do laboratório também utilizei o **ChatGPT, da OpenAI, como ferramenta de apoio e orientação técnica**, principalmente para compreender as diferenças entre as interfaces apresentadas nas aulas e as versões atuais dos serviços Microsoft Azure.

---

## Objetivos do projeto

O laboratório teve como principais objetivos:

- praticar o uso de serviços de Inteligência Artificial do Microsoft Azure;
- compreender aplicações de IA relacionadas à fala;
- compreender conceitos de Processamento de Linguagem Natural;
- realizar análise de sentimentos em textos;
- explorar ferramentas visuais disponibilizadas pela Microsoft;
- documentar o processo de aprendizagem;
- utilizar o GitHub como portfólio técnico.

---

# 1. Preparação do ambiente no Azure

Inicialmente foi utilizada uma conta do Microsoft Azure para criação dos recursos necessários para o laboratório.

Foi criado um grupo de recursos para organizar os serviços utilizados no projeto.

A organização dos recursos facilita o gerenciamento da infraestrutura e também permite remover os recursos posteriormente, evitando cobranças desnecessárias.

A estrutura utilizada ficou semelhante a:

```text
Microsoft Azure
│
├── Resource Group
│
├── Azure Speech
│   └── fala1
│
└── Microsoft Foundry
    └── ProjetoDioSpeechLanguage
