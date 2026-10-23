# 🧠 Segundo Cérebro: Automações WhatsApp N8N
 
> Desafio DIO: montar um especialista em IA no Gemini Notebook (antigo NotebookLM), alimentado apenas por fontes que eu mesmo selecionei.
 
🔗 **Notebook compartilhado:** https://notebook.google.com/notebook/52ed26e5-4907-46ab-aca6-6d2be26ed4fa
 
---
 
## 1. Tema e objetivo
 
> **Objetivo em uma frase:** Entender os fundamentos de Automações com N8N para conseguir criar agentes de IA, usando apenas fontes confiáveis.
 
**O que meu segundo cérebro precisa saber:**
- como estruturar **sistemas multiatendimento**
- integrando canais de comunicação populares como **WhatsApp, Instagram e Telegram**
- os materiais abordam os fundamentos técnicos essenciais para operar a plataforma **N8N**
---
 
## 2. Fontes selecionadas
 
| # | Tipo | Fonte | Link | Por que confio |
|---|------|-------|------|----------------|
| 1 | Vídeo (YouTube) | NoCode StartUp | https://youtu.be/3Pjp6eCvtgE | especialista reconhecido, conteúdo atualizado |
| 2 | Artigo | n8n Docs | https://docs.n8n.io/ | publicação oficial |
| 3 | PDF | Arquitetura e Engenharia de Automação Empresarial com n8n: Um Guia Completo | documentação oficial |
| 4 | GitHub | GitHub - n8n-io/n8n: Fair-code workflow automation platform with native AI capabilities. | GitHub - n8n-io/n8n: Fair-code workflow automation platform with native AI capabilities. |
 
**Critérios que usei para aceitar uma fonte:**
- autor ou instituição identificável
- conteúdo recente ou ainda válido
- conteúdo que posso compartilhar, sem dados pessoais
 
---
 
## 3. Diretriz de comportamento
 
Instrução que dei ao notebook:
 
```text
Comporte-se como um especialista em automações no N8N, com foco na implementação de agentes de atendimento de pequenas e medias empresas . Responda sempre com base nas fontes, em português, de forma didática, e avise quando a informação não estiver nas fontes.
```
 
---
 
## 4. Perguntas e respostas (com citações)
 
### Pergunta 1
**Pergunta:** Como posso criar um agente de IA no N8N para automatizar minhas tarefas?
 
**Resposta (resumo):** Para criar um **agente de IA no n8n** e automatizar tarefas no seu negócio ou rotina, você estrutura um fluxo visual onde o nó principal de IA funciona como o orquestrador de raciocínio, conectado a um modelo de linguagem (LLM), memória e ferramentas de ação
 
**Fontes citadas:** Arquitetura e Engenharia de Automação Empresarial com n8n: Um Guia Completo
 
<img width="1920" height="1080" alt="chat-01" src="https://github.com/user-attachments/assets/6a929f93-d11c-4bfa-a494-5b8d4ee68c3b" />

 
---
 
### Pergunta 2
**Pergunta:** Como configurar o n8n no modo queue?
 
**Resposta (resumo):** Configurar o **n8n em Modo Queue (Queue Mode)** é a melhor abordagem para garantir escalabilidade horizontal e alta disponibilidade em cenários de alta carga de trabalho. Nesse modo, a aplicação é dividida em papéis especializados: uma **Instância Principal (Main)** que gerencia a interface e os agendamentos, um cluster **Redis** que atua como fila de mensagens (*message broker*), e instâncias autônomas de **Workers** que executam os fluxos de trabalho.
 
**Fontes citadas:** Arquitetura e Engenharia de Automação Empresarial com n8n: Um Guia Completo, Enable queue mode | Deploy - n8n Docs
 
<img width="1920" height="1020" alt="chat-02" src="https://github.com/user-attachments/assets/67247318-b659-43fb-a88c-46528ccff72f" />

 
---
 
### Pergunta 3
**Pergunta:** Como integrar o n8n com o WhatsApp?
 
**Resposta (resumo):** Para integrar o **n8n com o WhatsApp** e criar uma automação ou agente de atendimento para pequenas e médias empresas, é necessário primeiro definir qual tipo de infraestrutura/API de WhatsApp você utilizará. Em seguida, estrutura-se um fluxo no n8n para receber as mensagens, tratá-las e responder de forma automatizada
 
**Fontes citadas:** Agentes de IA no WhatsApp, Instagram e Telegram DE GRAÇA!, Curso N8N + Whatsapp: Crie seu Agente de IA do ZERO! Tutorial Completo, Agentes de IA no WhatsApp, Instagram e Telegram DE GRAÇA!
 
<img width="1920" height="1020" alt="chat-03" src="https://github.com/user-attachments/assets/5de0d4c1-cb1c-4733-806e-3a8fba0cca89" />
 
---
 
## 5. Materiais gerados no Estúdio
 
| Material | Arquivo |
|----------|---------|
| Mapa mental | <img width="3382" height="3537" alt="NotebookLM Mind Map" src="https://github.com/user-attachments/assets/655fecfa-5a51-4978-b990-3e7827cda97b" />|
| Slides | [n8n_Enterprise_Architecture.pdf](https://github.com/user-attachments/files/33849941/n8n_Enterprise_Architecture.pdf)|
| Infográfico | <img width="2752" height="1536" alt="Arquitetura_de_Agentes_de_IA" src="https://github.com/user-attachments/assets/71941cf1-ef25-47dc-9398-f30bf736ef70" /> |
 
---
 
## 6. O que aprendi
 
- Aprendi sobre os Nós no N8N e seu funcionamento, como se integra com outros serviços e como estruturar um fluxo.
- Boas fontes garantem um aprendizado mais eficiente e uma melhor interpretação da IA sobre o conteúdo. 
- Buscaria aprender mais sobre engenharia de prompt para refinar as pesquisas sobre os temas.
---
 
## 📁 Estrutura do repositório
 
```text
.
├── README.md
├── prints/
│   ├── chat-01.png
│   ├── chat-02.png
│   └── chat-03.png
└── materiais/
    ├── mapa-mental.png
    ├── slides.pdf
    └── guia-de-estudos.pdf
```
 
