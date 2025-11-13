🚗 Assistente de Inteligência Artificial para Diagnóstico Automotivo

Este projeto tem como objetivo desenvolver uma IA especializada em manutenção automotiva, capaz de auxiliar motoristas e mecânicos na identificação preliminar de falhas e anomalias em veículos.

A aplicação foi construída em Java com Spring Boot e integrada ao modelo de linguagem Llama 3 via Ollama, permitindo que o sistema ofereça respostas contextualizadas sobre problemas mecânicos, manutenção preventiva e boas práticas de reparo automotivo.

Todo o ambiente é containerizado com Docker, garantindo fácil implantação e portabilidade — basta executar docker compose up para ter o sistema rodando, sem necessidade de instalar dependências adicionais.

💡 Principais características:

Diagnóstico prévio e recomendações automotivas via IA

Execução local com Ollama e modelo Llama3

Backend em Spring Boot com API REST (/api/chat?message=)

Deploy rápido e portátil com Docker Compose

Ideal para oficinas, estudantes e entusiastas de mecânica automotiva

🔧 Tecnologias: Java 21 • Spring Boot • Maven • Ollama (Llama3) • Docker • Docker Compose
📦 Modelo IA: llama3:8b
🧠 Foco: Diagnóstico Automotivo Inteligente

Desenvolvido como parte do Trabalho de Conclusão de Curso (TCC) do SENAI, demonstrando a aplicação prática da IA generativa no setor automotivo.

💻 Repositório:
https://github.com/aleeSenai/Projeto-TCC---Assistente-de-IA-Automotiva

🐋 Docker Hub:
https://hub.docker.com/repositories/aleesenai
docker pull aleesenai/ollama:latest
docker pull aleesenai/tcc-springboot:latest
docker compose up

🔌 Endpoints da API: 
Enviar uma pergunta para a IA
GET http://localhost:8080/api/chat?message= sua pergunta

