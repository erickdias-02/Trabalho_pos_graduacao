Alunos: Erick Dias, Alexansder Prates, Werbert Wilson Severiano Chaves Conceição, Luciano Otavio Deschamps Lopes.

Projeto: Estratégias de Acompanhamento Acadêmico para Redução de Evasão dos alunos nos cursos de graduação



Problema central
Como otimizar estratégias de acompanhamento acadêmico para reduzir desistências em cursos de graduação, considerando os padrões de matrícula e os índices de aprovação e reprovação dos alunos?

Justificativa
A evasão no ensino superior é um dos principais desafios enfrentados pelas instituições de ensino. Além de impactar a formação dos estudantes, ela gera prejuízos financeiros e compromete indicadores institucionais de qualidade.
 O acompanhamento acadêmico eficiente, baseado em dados, é uma estratégia promissora para identificar alunos em risco de abandono e oferecer intervenções direcionadas.
 O dataset de matrículas, com informações sobre status de matrícula e desempenho (aprovação/reprovação), permite identificar padrões associados à desistência e pode subsidiar ações preventivas.



Objetivo geral
Analisar os dados de matrícula e desempenho acadêmico dos alunos de graduação para identificar fatores associados à evasão, propondo estratégias de acompanhamento que possam reduzir as desistências.

Objetivos específicos
Mapear os padrões de status de matrícula (ativos, trancados, cancelados) e suas variações ao longo do curso.


Identificar taxas de aprovação e reprovação por período, curso ou disciplina.


Analisar a relação entre reprovações e o risco de desistência.


Detectar perfis de alunos mais propensos a trancar ou cancelar a matrícula.


Propor estratégias de acompanhamento acadêmico baseadas nos resultados (ex.: programas de tutoria, monitorias, alertas de risco).

Possíveis análises no dataset
Taxa de evasão por semestre/ano.


Correlação entre reprovação em disciplinas-chave e abandono.


Comparação de permanência entre alunos regulares e aqueles que já trancaram matrícula.


Construção de indicadores de risco (ex.: reprovação em mais de X disciplinas → maior probabilidade de desistência).
1. Entendimento do negócio

1.1 Contexto institucional e problema a ser abordado
A evasão acadêmica representa um desafio crítico que impacta:
A formação dos estudantes
Os indicadores institucionais do SENAI
Os resultados financeiros da FIESC
Como otimizar estratégias de acompanhamento acadêmico para reduzir desistências, utilizando análise de padrões de matrícula e desempenho dos estudantes?


1.2 Objetivos do Projeto
Reduzir taxas de evasão e trancamento
Melhorar o acompanhamento de estudantes em situação de risco
Apoiar decisões institucionais baseadas em dados


3. ESTRUTURA DOS DADOS E ANÁLISE EXPLORATÓRIA

2.1 Fonte de Dados
Relatórios institucionais de matrículas de alunos de graduação

2.2 Variáveis Principais
Status da Matrícula: ativo, trancado, cancelado, concluído
Situação Acadêmica: aprovado, reprovado, em curso
Histórico de Reprovações: registro de disciplinas não aprovadas
Tempo de Integralização: quantidade de semestres cursados

2.3 Perguntas Exploratórias
Qual a taxa de reprovação média por semestre e por curso?
Alunos que trancam matrícula apresentam histórico prévio de reprovação?
Em quais períodos do curso ocorrem mais desistências?



4. PREPARAÇÃO E TRATAMENTO DOS DADOS

3.1 Processo de Limpeza
Remoção de inconsistências (valores nulos, registros duplicados)


3.2 Transformação de Dados
Criação de variáveis derivadas:
Número total de reprovações por aluno
Índice de evasão por semestre
Histórico de trancamentos


3.3 Integração de Dados
Enriquecimento com variáveis adicionais (quando disponíveis):
Curso de origem
Turno de estudo
Forma de ingresso na instituição

5. ESTRATÉGIAS DE MODELAGEM
4.1 Técnicas de Machine Learning Supervisionadas

4.1.2 Árvore de Decisão
Objetivo: Identificar regras de decisão para segmentar alunos com maior risco de evasão

6. VALIDAÇÃO E AVALIAÇÃO DOS RESULTADOS

5.1 Métricas de Performance
Métricas de desempenho para classificação
Métricas de qualidade para clusterização

5.2 Validação Contextual
Verificação se os fatores preditores identificados fazem sentido no contexto institucional
Comparação entre diferentes algoritmos para escolha da solução mais robusta


7. IMPLEMENTAÇÃO E ENTREGA
6.1 Formato de Entrega


6.1.1 Notebook Interativo
Plataforma: Google Colab
Conteúdo: Pipeline completo de análise e modelagem


6.1.2 Documentação Técnica
Repositório: GitHub
Conteúdo:
Descrição detalhada dos dados
Metodologia CRISP-DM aplicada
Resultados dos modelos desenvolvidos
Recomendações práticas para acompanhamento acadêmico


6.2 Impacto Esperado
Disponibilizar ferramenta prática para análise contínua de risco de evasão
Facilitar replicação e atualização do estudo pela instituição
Fornecer evidências científicas para apoiar políticas de acompanhamento estudantil

