# PARTE 1 - COLETA DE INFORMAÇÕES EMPÍRICAS
_A primeira parte do encontro serve para mapear o que é conhecido pelo grupo e que precisa ser documentado como "boa prática"._

## 1. Abertura e inspiração (10 min)

Apresentação rápida do conteúdo (não substitui a necessidade de realizar os autoestudos):
- A função de um Design Playbook;
- Os tipos de conteúdo que costumam conter (valores, fluxos, práticas, ferramentas);
- O papel do playbook na redução da complexidade e comunicação interna.

## 2. O que sabemos pela prática (20 min)

Cada grupo responde à pergunta:  
_"O que já estamos fazendo que vale a pena registrar como boa prática?"_

**Ações:**  
- Cada integrante escreve em post-its (1 ideia por post-it): práticas, ferramentas, decisões de design ou fluxos que funcionaram bem no projeto até aqui.  
- O grupo agrupa os post-its em categorias aproximadas: processo, ferramenta, decisão recorrente, padrão de design, princípio, desafio vencido, etc.


# PARTE 2 - COMPONTO O DESIGN PLAYBOOK
_Com base no template e na discussão em sala, os alunos poderem compor o Playbook de boas práticas do projeto.
Vide template a seguir:_

# UX Product/Service Design Playbook – [Nome do Projeto]

Documento de referência única do time de Design/UX, consolidando decisões, processos, padrões e boas práticas adotadas no desenvolvimento da solução para a esteira CI/CD de IA.

---

## 1. Quem somos (Time e papéis)

Apresente os integrantes da equipe e suas funções no projeto:

| Nome    | Função        | Responsabilidades                       |
|---------|---------------|---------------------------------------|
| Fulano  | UX Designer   | Pesquisa, protótipos, testes           |
| Ciclana | DesignOps     | Orquestração de processos, documentação|
| Beltrano| Dev           | Integração CI/CD, implementação        |

---

## 2. Entendimento do problema e descoberta

**a. Contexto e problema**  
- Qual problema enfrentado no fluxo CI/CD com IA?  
- Quem são os afetados? Qual a motivação da solução?

**b. Personas e stakeholders**  
- Quem são os usuários e suas expectativas?  
- Principais stakeholders envolvidos

**c. Jornada e pontos críticos**  
- Mapeamento do fluxo atual (ex: jornada do dado, gargalos, fricções)

**d. Hipóteses e descobertas iniciais**  
- Hipóteses levantadas e validações realizadas  
- Ferramentas e métodos usados (ex: entrevistas, benchmark)

---

## 3. Design system

**a. Design system aplicado**  
- Arquitetura de Conversação
  - Padrões para diálogos, turnos de fala, contexto e gestão de estado
  - Scripts e templates de respostas
  - Guia de tom e estilo da comunicação (ex: formal, amigável)

- Modelos de Linguagem e Intenções
  - Definição clara das intenções (intents) e entidades
  - Estrutura para treinamento e atualização dos modelos de NLP

- APIs e Endpoints
  - Padrões para comunicação entre serviços (ex: input/output de dados)
  - Contratos e documentação técnica unificada

- Regras de Negócio e Lógica de Decisão
  - Estrutura de regras para respostas e ações automáticas
  - Definição de fluxos de decisão

- Testes e Validação
  - Scripts e cenários padrão para testes automatizados e de usabilidade
  - Critérios para avaliação de precisão, recall e satisfação do usuário

- Monitoramento e Métricas
  - Definição dos KPIs a serem monitorados (ex: taxa de erro, tempo de resposta, engajamento)
  - Dashboards e alertas

- Documentação Técnica e Guias de Uso
  - Manual de integração
  - Glossário de termos
  - Exemplos de uso

- Padrões de Segurança e Privacidade
  - Regras para tratamento de dados sensíveis
  - Políticas de consentimento e compliance

- Fluxos de Feedback e Iteração
  - Processos para coleta e incorporação de feedback dos usuários e stakeholders
  - Ciclos de atualização do modelo

- Governança de Dados
  - Diretrizes para coleta, armazenamento e uso dos dados para treino da IA

**b. Fluxos e protótipos** 
_Traga para um contexto que faça sentido para o projeto._
- Caminhos principais e alternativos  
- Nível de fidelidade, justificativas e escolhas

**c. Critérios de usabilidade aplicados**  
- Heurísticas, princípios, acessibilidade, consistência

**d. Integração com devs e CI/CD**  
- Processos de handoff  
- Padronizações adotadas na interface da esteira

---

## 4. Processo de Design (Plays)

Etapas e atividades aplicadas ao longo do projeto — adaptadas do modelo de Arturo Leal.

**a. Entender**  
- Alinhamento inicial com os representantes da parceira  
- Entrevistas com usuários (aconteceram? quem são? contexto?)  
- Mapeamento do problema (ex: jornada do dado, pain points)

**b. Descobrir**  
- Ideação (métodos como brainstorming, Crazy 8s, etc. O que vocês usaram?)  
- Benchmarking de soluções similares (esteiras CI/CD, IA aplicável)  
- Documentação inicial: TAPI, escopo, hipóteses

**c. Design**  
- Criação de protótipos (no contexto do projeto, como e o que vocês prototiparam?)  
- Aplicação de padrões (o que foi padronizado?)  
- Aplicação de critérios de usabilidade e acessibilidade

**d. Testar e aprender**  
- Métodos de validação adotados (ex: walkthrough com devs, testagem rápida)  
- Incorporação de feedbacks ao design  
- Aprendizados documentados e próximos passos

---

## 5. Testes e validação

**a. Estratégia de testes adotada**  
- Usuários envolvidos, ferramentas utilizadas  
- Tipo de teste (exploratórios, A/B, walkthrough)

**b. Métricas e critérios de sucesso**  
- Ex: taxa de erro, tempo de tarefa, clareza

**c. Aprendizados e ajustes**  
- O que foi alterado com base nos testes?  
- Impactos esperados na solução final

---

## 6. Boas práticas (Core Practices)

Documente práticas que se consolidaram ao longo do projeto:

| Situação                  | Prática adotada                         | Impacto                          |
|---------------------------|---------------------------------------|---------------------------------|
| Complexidade na jornada   | Divisão em etapas visuais claras       | Reduziu sobrecarga cognitiva     |
| Erros recorrentes no input| Máscaras de entrada e mensagens preditivas | Reduziu retrabalho           |

---

## 8. Recursos e anexos
_Aqui são colocados links para materiais de apoio pesquisados ou produzidos pelo grupo_
- Protótipos, entrevistas, documentação técnica  
- Glossário de termos  
- Linha do tempo  
- Links úteis e referências
