# ⚖️ Guia de Ética e IA Responsável com NotebookLM

> **Projeto de portfólio desenvolvido para o Bootcamp Riachuelo | DIO** 🚀

Este repositório contém um **Caderno Temático** focado nos pilares da **IA Responsável**. O projeto utiliza a ferramenta **NotebookLM** para realizar uma curadoria inteligente de fontes sobre ética, mitigação de vieses algorítmicos e transparência em modelos de linguagem (LLMs).

O objetivo final é fornecer um guia prático para que desenvolvedores e tomadores de decisão compreendam os riscos éticos e as novas regulamentações globais.

---

## 🎯 Contexto e Objetivos
Este caderno temático explora a interseção entre tecnologia, direito e filosofia. O foco principal é entender como mitigar vieses algorítmicos e garantir a transparência. O objetivo é criar um material de referência sobre os riscos éticos e as regulamentações que moldam a democracia digital em 2026.

---

## 📚 Curadoria de Fontes
As fontes selecionadas e carregadas no NotebookLM para este estudo incluem artigos acadêmicos, documentos oficiais e análises de especialistas:

### 🏛️ Institucionais e Jurídicas
* **UNESCO:** *Recomendação sobre a Ética da Inteligência Artificial (2021).*
* **IBM / União Europeia:** *O que é a Lei de Inteligência Artificial da União Europeia (AI Act).*
* **Migalhas:** *A responsabilidade civil no uso de IA (Silva & Pereira).*
* **ESG (Escola Superior de Guerra):** *IA em Armas Autônomas e Direito Internacional (Siqueira).*

### 🎓 Acadêmicas e Filosóficas
* **USP (Cadernos de Ética):** *IA como agente moral na democracia digital (Rios).*
* **USP Talks #48:** *Implicações éticas e sociais (Dora Kaufman e Marcelo Finger).*
* **UNESP:** *Viés algorítmico – um balanço provisório (Simões-Gomes et al.).*
* **UFMG:** *Ética e IA: desafios e melhores práticas (Lopes & Mendes).*
* **CIDP (Lisboa):** *IA, Ética e Real-World Evidence (Leite).*

### 🎥 Divulgação Científica e Pensamento Crítico
* **Ciência Todo Dia:** *O Problema do Alinhamento em IAs.*
* **Ex libris dHB:** *Comentários sobre a obra de Luciano Floridi.*
* **Forbes Brasil:** *Tendências Éticas para 2026.*

### Vídeos
* **(https://www.youtube.com/watch?v=KZGYOl5mAzs)*
* **(https://www.youtube.com/watch?v=CjiOJDdahl4)*
* **(https://www.youtube.com/watch?v=IH-wBijX53M)*
* **(https://www.youtube.com/watch?v=Iv-Bl1yqppw)*


---

## 🛠️ Engenharia de Prompts e "Cicatrizes"

Nesta seção, documento as perguntas estratégicas elaboradas e as respostas detalhadas extraídas das fontes através da IA.

### 🔍 Prompt 1: Visão Geral de Riscos
> **Pergunta:** "Com base nas fontes, quais são os 5 maiores riscos éticos identificados para IAs Generativas hoje?"

**Resposta obtida:**
1. **Vieses Algorítmicos e Discriminação:** Reprodução e amplificação de preconceitos históricos (gênero, raça e classe) contidos nos dados de treino.
2. **Desinformação e Deepfakes:** Facilidade na criação de conteúdos sintéticos para manipular a opinião pública e processos eleitorais.
3. **Imprecisão Epistêmica e "Alucinações":** Geração de conteúdos factualmente falsos devido à natureza probabilística dos modelos.
4. **Ameaça à Privacidade:** Coleta massiva de dados pessoais para treinamento sem consentimento pleno ou consciência do usuário.
5. **Erosão da Autonomia Humana:** Influência invisível de algoritmos nas decisões e redução da capacidade de julgamento independente.

---

### 🏗️ Prompt 2: Aplicação Prática (Checklist de Desenvolvimento)
> **Pergunta:** "Crie um checklist de 3 perguntas que um desenvolvedor deve se fazer antes de colocar um modelo de IA em produção, visando evitar discriminação."

* **[ ] Representatividade:** Os dados de treino refletem a diversidade real ou contêm vieses herdados de práticas passadas?
* **[ ] Identificação de Proxies:** Existem variáveis (como código postal) atuando como substitutos ocultos para características sensíveis?
* **[ ] Auditoria Multidisciplinar:** O sistema passou por testes de impacto realizados por equipes de Ética, Direito e Sociologia?

---

### 🇪🇺 Prompt 3: Regulamentação (EU AI Act)
> **Pergunta:** "Explique a diferença entre modelos de 'Risco Inaceitável' e 'Alto Risco' de acordo com o AI Act da União Europeia."

* **Risco Inaceitável:** Práticas proibidas por serem ameaças claras à segurança (ex: pontuação social, manipulação comportamental).
* **Alto Risco:** Permitidos sob regras rigorosas (ex: infraestrutura crítica, RH, educação). Exigem supervisão humana e governança de dados.

---

## 📖 Miniguia de Estudo (Entrega Final)

### Glossário de Conceitos Chave
* **Problema do Alinhamento:** O desafio de garantir que os objetivos da IA estejam em harmonia com os valores e interesses humanos.
* **Responsabilidade Civil:** O debate jurídico sobre quem responde por danos causados por sistemas autônomos.
* **XAI (IA Explicável):** Práticas que permitem que humanos compreendam e rastreiem o processo de decisão de uma IA.

### Prompts Reutilizáveis para Revisão
* `Explique o conceito de ética de Luciano Floridi aplicado às IAs atuais.`
* `Quais as principais implicações do uso de IA em conflitos armados segundo o ensaio da ESG?`

---
✨ *Projeto desenvolvido como parte do desafio de portfólio no Bootcamp da DIO.*
