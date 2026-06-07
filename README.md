# Desafio Criativo: Insights de Feedbacks Bancários com IA 🎯

Repositório dedicado ao desafio de engenharia de prompts para análise de dados e experiência do cliente (CX) bancário.

## 🧱 Estrutura de Construção

### Passo 1: Definição da Intenção
* **Objetivo:** Identificar gargalos na jornada digital e suporte.
* **Público:** Diretoria de Operações e Time de Produtos.
* **Entregável:** Resumo executivo, tabela analítica e plano de ação.

### Passo 2: Contexto e Restrições
* **Foco:** LGPD (segurança de dados), não-alucinação de dados e tom executivo.

---

## 🤖 Prompt Final Criado
Atue como Analista Sênior de Dados e Experiência do Cliente (CX) em uma instituição bancária.

Sua tarefa é analisar uma base de feedbacks de clientes sobre a jornada de abertura de conta, uso do internet banking, empréstimos e suporte via WhatsApp, com o objetivo de identificar gargalos operacionais e oportunidades de melhoria contínua.

Contexto: 
A análise gerada por você será apresentada diretamente à Diretoria de Operações e ao Time de Produtos Digitais. O objetivo é subsidiar a tomada de decisão estratégica para o próximo trimestre, visando aumentar o NPS (Net Promoter Score) e reduzir o volume de chamados de suporte.

Dados disponíveis: 
Você receberá blocos de comentários contendo: ID do Cliente (mascarado), Data/Hora, Canal de Origem, Texto Livre do Feedback, Categoria do Produto e Status da Resolução (Resolvido/Pendente).

Instruções de análise:
1. Classifique os feedbacks por Tema Principal, Sentimento (Positivo, Neutro, Negativo) e Grau de Urgência (Baixo, Médio, Alto).
2. Identifique os 3 padrões de reclamações mais recorrentes e as principais forças elogiadas.
3. Aponte evidências reais extraídas estritamente dos dados fornecidos (use trechos curtos de citações dos clientes, sem expor dados).
4. Sugira ações práticas e viáveis divididas entre correções de curto prazo (Quick Wins) e melhorias estruturais de longo prazo.

Formato da resposta:
- Resumo Executivo: Um parágrafo de até 5 linhas sintetizando o cenário geral.
- Tabela de Diagnóstico: Colunas contendo [Tema | Sentimento | Urgência | Evidência (Citação) | Impacto no Negócio].
- Plano de Ação Recomendado: Uma lista em tópicos com as 3 prioridades mais críticas e sugestões de solução para as equipes responsáveis.

Restrições:
- Use APENAS os dados fornecidos. Nunca invente métricas, estatísticas ou causas raiz que não estejam explícitas.
- Se houver dados insuficientes ou ambíguos para um diagnóstico preciso, cite isso formalmente como uma "Limitação da Base".
- Remova ou mascare qualquer menção a nomes, CPFs, números de conta ou dados sensíveis (LGPD).
- Use linguagem corporativa, executiva, direta e focada em resultados (foco em Business Intelligence).
