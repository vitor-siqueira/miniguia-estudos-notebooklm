# 🧠 Miniguia de Estudos: Fundamentos de Quality Assurance (QA) com NotebookLM

Este repositório contém o projeto prático desenvolvido para o desafio da DIO, focado em transformar documentações técnicas densas em conhecimento estruturado utilizando a Inteligência Artificial (NotebookLM).

## 🎯 Contexto e Objetivos

O objetivo deste caderno temático é consolidar a base teórica necessária para a transição de carreira para a área de **Qualidade de Software (QA)**. O foco está no domínio de normas internacionais e metodologias ágeis.

**Objetivos de Estudo:**
* **Padronização:** Alinhar o vocabulário técnico com o Syllabus ISTQB (CTFL).
* **Agilidade:** Compreender o papel do QA em ciclos de desenvolvimento modernos.
* **Segurança:** Identificar vulnerabilidades críticas baseadas no OWASP Top 10.
* **Eficiência:** Utilizar Engenharia de Prompts para organizar informações complexas de forma visual e rápida.

---

## 📚 Curadoria de Fontes

Para garantir que as respostas da IA fossem fundamentadas em padrões reais da indústria de tecnologia, foram selecionadas e carregadas no NotebookLM as seguintes fontes de autoridade global:

| Fonte / Instituição | Documento Referência | Finalidade no Estudo | Link de Acesso |
| :--- | :--- | :--- | :--- |
| **BSTQB / ISTQB** | Syllabus CTFL 4.0br | Padronização de processos e terminologia oficial de testes. | [Aceder PDF](https://bstqb.online/files/syllabus_ctfl_4.0br.pdf) |
| **Agile Alliance** | Manifesto e Princípios Ágeis | Compreensão do papel do QA em metodologias ágeis (Scrum/Kanban). | [Manifesto](https://agilemanifesto.org/iso/ptbr/manifesto.html) / [Princípios](https://agilemanifesto.org/iso/ptbr/principles.html) |
| **OWASP** | Top 10:2017 Project | Identificação das vulnerabilidades de segurança mais críticas em aplicações. | [Guia OWASP](https://owasp.org/www-project-top-ten/2017/) |
| **Cypress.io** | Core Concepts | Fundamentação técnica para automação de testes modernos e E2E. | [Docs Cypress](https://docs.cypress.io/app/core-concepts/introduction-to-cypress) |

> **Nota de Implementação:** As fontes de texto (Manifesto e Princípios Ágeis) foram consolidadas via "copy-paste" diretamente no NotebookLM para criação da base de conhecimento personalizada, enquanto as demais foram processadas via upload de arquivo PDF ou URL.

---

## 🛠️ Engenharia de Prompts e "Cicatrizes"

Nesta secção, documento o processo de "conversa" com a IA para extrair o melhor resultado.

### Exemplo 1: Definição de Processos
* **Prompt:** *"Explica as fases do processo de teste segundo o ISTQB."*
* **Cicatriz (Problema):** A resposta foi um texto corrido difícil de memorizar.
* **Ajuste Estratégico:** Solicitei que a IA decidisse o melhor formato. O prompt final foi: *"Analise as fases do processo de teste no Syllabus. Se for sequencial, use uma lista numerada; se houver comparação, use uma tabela."*
* **Resultado:** A IA gerou uma lista numerada clara, do planeamento ao fecho.

### Exemplo 2: Diferenciação Técnica
* **Prompt:** *"Qual a diferença entre Re-teste e Teste de Regressão?"*
* **Cicatriz:** A IA confundiu inicialmente os conceitos.
* **Ajuste:** Forneci o contexto do glossário ISTQB e pedi uma tabela comparativa direta.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados: Conceitos Chave de QA

#### A. O Processo de Teste (Segundo ISTQB 4.0)
Com base no processamento do Syllabus pela IA, o fluxo ideal segue:
1. **Planejamento:** Definição de objetivos e abordagem.
2. **Análise e Modelagem:** O que testar e criação dos casos de teste.
3. **Implementação e Execução:** Preparação do ambiente e rodagem dos testes.
4. **Avaliação e Relatório:** Verificação dos critérios de saída e comunicação dos resultados.
5. **Atividades de Fechamento:** Lições aprendidas e arquivamento de dados.

#### B. Matriz Comparativa: Técnicas de Teste
| Conceito | Definição (ISTQB) | Aplicação Prática |
| :--- | :--- | :--- |
| **Teste de Caixa-Preta** | Baseado em requisitos e especificações. | Validar se o botão de login funciona como esperado sem olhar o código. |
| **Teste de Caixa-Branca** | Baseado na estrutura interna do código. | Verificar a cobertura de caminhos e lógica de funções no backend. |
| **Teste de Regressão** | Testar novamente após alterações para garantir que nada quebrou. | Executar a suite de testes após uma nova funcionalidade ser adicionada. |

### 2. Glossário de Termos Críticos

* **Defeito (Bug):** Uma imperfeição técnica em um componente ou sistema que pode causar falhas.
* **Falha:** Manifestação física ou funcional de um defeito durante a execução.
* **Caso de Teste:** Conjunto de pré-condições, entradas e resultados esperados para um cenário específico.
* **Qualidade de Software (QA):** Conjunto de atividades que garantem que o processo de desenvolvimento resulte em um produto que atenda aos requisitos.
* **Alucinação de IA:** Quando a ferramenta gera uma resposta que parece correta, mas não possui fundamento nas fontes fornecidas.

### 3. Biblioteca de Prompts Reutilizáveis

Utilize estes prompts para revisões futuras no NotebookLM:

> **Prompt de Comparação:**
> *"Com base nas fontes, crie uma tabela comparando [Termo A] e [Termo B], focando em objetivo, momento de execução e quem executa."*

> **Prompt de Decisão de Formato (Mestre):**
> *"Resuma o capítulo [X]. Analise a natureza da informação: se for um processo, use lista; se for uma hierarquia, descreva um mapa mental; se for comparação, use tabela."*

---

## 🛠️ Tecnologias Utilizadas

* [NotebookLM](https://notebooklm.google.com/)
* [GitHub](https://github.com/)
* [Gemini](https://gemini.google.com/) (para suporte na estruturação)
