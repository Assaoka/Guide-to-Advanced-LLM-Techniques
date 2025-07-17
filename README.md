<h1 align="center"> 🤖 Guia Prático de Técnicas Avançadas com LLMs para Classificação de Texto 🤖 <br>
  <img src="https://img.shields.io/badge/UNIFESP-Universidade%20Federal%20de%20S%C3%A3o%20Paulo-215a36" alt="UNIFESP">
  <img src="https://img.shields.io/badge/Jo%C3%A3o%20Assaoka,%20Lilian%20Berton-2025.1-215a36" alt="João Victor Assaoka">
</h1>

&emsp;&emsp; Este repositório é um tutorial completo e prático que explora metodologias avançadas para a classificação de sentimentos e emoções em textos, utilizando Modelos de Linguagem de Grande Porte (LLMs). O projeto foi desenvolvido para ser acessível, com todos os exemplos executáveis em ambientes gratuitos como o Google Colab.

# 🎯 Objetivo
&emsp;&emsp; O objetivo deste guia é desmistificar e centralizar o conhecimento sobre técnicas de LLMs, oferecendo um caminho claro e progressivo para estudantes, pesquisadores e desenvolvedores. Através de uma tarefa prática de análise de sentimentos em notícias financeiras brasileiras, demonstramos e comparamos abordagens como:
- Engenharia de Prompt: Zero-Shot, Few-Shot e Chain-of-Thought (CoT).
- Ensembles de LLMs: Votação Majoritária e Negociação entre modelos.
- Fine-Tuning Eficiente: Ajuste fino com QLoRA (Quantized Low-Rank Adaptation).
- Destilação de Conhecimento: Treinamento de um modelo menor a partir de um modelo "professor" maior.

# 🚀 Como Começar
Todos os notebooks foram projetados para serem executados de forma independente no Google Colab. Não é necessário configurar um ambiente local. Basta clicar nos links abaixo para abrir e executar cada módulo diretamente no seu navegador.

# 📚 Módulos do Tutorial
O guia é dividido em quatro módulos progressivos.

#### [Módulo 1: A Base - LangChain e Saídas Estruturadas](Módulo_1_LangChain_e_Saídas_Estruturadas.ipynb)
Neste módulo, construímos a fundação para interagir com LLMs de forma programática. Abordamos a configuração de APIs (Groq e Sabiá), a orquestração com LangChain e a importância de gerar saídas estruturadas (JSON) para integrar os modelos em aplicações reais.

#### [Módulo 2: A Arte e a Ciência da Engenharia de Prompt](Módulo_2_Arte_e_Ciência_da_Engenharia_de_Prompt.ipynb)
Aqui, aprofundamos as estratégias para guiar o comportamento dos LLMs. Comparamos as abordagens Zero-Shot, Few-Shot e a poderosa técnica de Chain-of-Thought (CoT), que incentiva o modelo a "pensar passo a passo" para melhorar a precisão em tarefas complexas.

#### [Módulo 3: Ensembles de LLMs - A Sabedoria das Multidões](Módulo_3_Ensembles_de_LLMs_A_Sabedoria_das_Multidões.ipynb)
Este módulo explora como combinar as predições de múltiplos modelos para obter resultados mais robustos. Implementamos duas estratégias de ensemble: a Votação Majoritária (incluindo a técnica de Self-Consistency) e a Negociação, que simula um debate estruturado entre modelos para alcançar um consenso.

#### [Módulo 4: Fine-Tuning Eficiente - Especializando seu Próprio LLM](Módulo_4_Fine_Tuning_Eficiente_Especializando_seu_Proprio_LLM.ipynb)
No módulo final, adaptamos o próprio modelo à nossa tarefa específica. Demonstramos como realizar o fine-tuning de um LLM de forma eficiente em uma GPU gratuita, utilizando a técnica QLoRA. Além disso, introduzimos a destilação de conhecimento como uma forma de criar modelos menores e mais rápidos, treinados para imitar o comportamento de um "professor" maior.

# 💡 [Guia de Decisão](Guia_de_Decisão.md)
&emsp;&emsp; Para ajudar na escolha da metodologia mais adequada para o seu projeto, o artigo associado a este guia oferece um guia de decisão prático, com base em prioridades como precisão, interpretabilidade e latência.

Sinta-se à vontade para explorar, executar e adaptar os notebooks para seus próprios projetos!