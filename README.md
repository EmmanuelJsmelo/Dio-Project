# Dio-Project

App/Site de finanças para o Desafio da Dio

Etapa 1 (Prd):

prompts:
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Prd inicial:
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
bom o PRD ( e não PDR [produto requerimento documento]é sobre organização de finanças e eu vou deixar alguns topicos aqui. fique a vontade para introduzire mais topicos para poder trabalhar em cima se necessario

1-O mais importante, quero criar um aplicativo de organização de finanças pessoais para pessaos com pouco ou nenhum conhecimento sobre organizar as finanças ou saber se situar nesse espaço virtual, ou seja necessito de linguagem simples/natural e poucos preenchimento e planilhas o mais simples e entendiveis possivel

2-foco principal em conversa e analise de dados simples para não fazer o usuario se perder

3- publico alvo: pessoas com pouca esperiencia no meio virtual e pouco conhecimenbto sobre finanças adolescentes a idosos.

4- principais mecaninas:

registrar gastos e montar um resumo/planilha (se pedido)por meio do chat/conversa
classificar automaticamente transações (organizar por setores, como moradia e transporte [exemplo])
linguagem natural e simples para facil entendimento
ser possivel dar dicas financeiraas para conseguir gerir mais facilmente essses gastos (se pedido) como forma de uma agente financeiro.
visualizar documentos,planilhas,resumos,relatorios. para maior entendimento da situação do usuario e poder ser possivel ver os gastos mesmo que não sejam diretamente escritos no caht.

e pra finalizar (essa parte peguei colada do curso por que não entendi muito bem , se possivel me explique):

gerar um plano mvp com as principais telas,recursos necessarios e um esboço de validação inicial

(foco em tom educativo e linguagem simples/acessivel em portugues do brasil)

gostaria que revisassse todo esse meu prd pois quero usar ele no lovable para poder passar na atividade proposta no curso.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Prd revisado não final):
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Documentode Requisitos do Produto PRD
Produto: Aplicativo de organização de finanças pessoais por conversa
Tom: educativo, simples e acessível em Português do Brasil
Público alvo: pessoas com pouca experiência digital e baixo conhecimento financeiro, de adolescentes a idosos

1 Visão geral
Criar um aplicativo que permita organizar finanças pessoais usando conversa em linguagem natural. O foco é reduzir fricção: poucos campos para preencher, interface por chat, explicações simples e visuais claros. O app deve ajudar o usuário a entender sua situação financeira sem exigir planilhas complexas.

2 Objetivos do produto
Facilitar o registro de gastos por meio de conversas simples.

Classificar automaticamente transações em categorias úteis.

Gerar resumos e relatórios em linguagem acessível quando o usuário pedir.

Oferecer dicas práticas e acionáveis para melhorar a gestão financeira.

Ser confiável e seguro, com explicações claras sobre privacidade.

3 Público alvo e necessidades
Perfil: usuários com pouca experiência no meio digital; podem ter dificuldades com formulários e planilhas.

Necessidades principais: linguagem simples; confirmação antes de salvar; visualização clara dos gastos; ajuda passo a passo; suporte para voz e texto (opcional).

Restrições: evitar jargões financeiros; minimizar número de telas e cliques.

4 Requisitos funcionais essenciais
Registro por chat: usuário informa gasto em texto ou voz; sistema confirma e salva.

Extração automática: identificar valor, data e categoria a partir da mensagem.

Classificação automática: agrupar por categorias como moradia, transporte, alimentação, saúde, lazer.

Resumo simples: cartão com saldo mensal, gasto total e categoria principal.

Histórico acessível: lista cronológica com filtro por mês e categoria.

Dicas financeiras: sugestões curtas e práticas quando solicitadas.

Exportar resumo: gerar planilha ou PDF somente se o usuário pedir.

Ajuda contextual: explicações curtas em linguagem natural sobre termos e ações.

Confirmação antes de salvar: sempre confirmar interpretação do gasto.

Modo offline básico: permitir registrar gastos sem conexão e sincronizar depois.

Acessibilidade: texto grande, alto contraste, leitura por voz.

5 Requisitos não funcionais
Segurança: armazenamento local criptografado; backup opcional com senha.

Privacidade: linguagem simples explicando como os dados são usados.

Performance: resposta do chat em menos de 2 segundos para ações básicas.

Simplicidade: máximo 3 passos para registrar um gasto comum.

Compatibilidade: Android e iOS inicialmente; versão web leve como opção futura.

6 Fluxo de usuário simplificado
Onboarding curto com 2 telas: objetivo do app e exemplo de uso por conversa.

Chat principal: usuário escreve ou fala o gasto.

Confirmação: app mostra interpretação e pergunta “Salvar?” com botões Sim / Corrigir.

Resumo rápido: cartão com principais indicadores.

Acesso ao histórico e à tela de dicas quando o usuário quiser.

7 O que é MVP e por que usar
MVP significa Produto Mínimo Viável. É a versão mais simples do app que permite testar se o público realmente usa a conversa para registrar gastos e se as classificações automáticas são úteis. O objetivo é validar hipóteses com pouco custo antes de desenvolver funcionalidades complexas.

8 Plano MVP detalhado
Telas principais do MVP
Tela de boas-vindas e onboarding com 2–3 passos e exemplo prático.

Chat principal com campo de texto e botão de voz; mensagens do sistema em linguagem simples.

Cartão Resumo mostrando saldo mensal, gasto total e categoria mais cara.

Histórico simplificado: lista com data, descrição curta, valor e categoria.

Tela de Dicas com 5 sugestões acionáveis.

Configurações e Ajuda: alterar linguagem, acessibilidade e exportar resumo.

Funcionalidades mínimas para o MVP
NLP básico para extrair valor, data e categoria.

Regras de classificação com fallback para confirmação manual.

Banco de dados local com sincronização opcional.

Gerador de resumo em linguagem natural (frases curtas).

Interface acessível com botões grandes e textos claros.

Mecanismo de confirmação antes de salvar transações.

Recursos técnicos necessários
Motor de NLP leve (pode usar regras + modelo pequeno).

Backend simples para armazenamento e sincronização (pode começar com armazenamento local).

Camada de segurança para criptografia local.

UI/UX com foco em acessibilidade.

Módulo de dicas baseado em regras (ex.: se gasto com assinatura > X, sugerir cancelar).

9 Esboço de validação inicial
Hipóteses a validar

Usuários conseguem registrar gastos via chat sem ajuda.

Classificação automática é aceitável com confirmação.

Dicas simples são compreendidas e aplicadas.

Métricas

Taxa de registro: número médio de registros por usuário por semana.

Taxa de confirmação: % de transações confirmadas sem correção.

Precisão de classificação: % de categorias corretas após confirmação.

Satisfação: NPS simples 1–5 após 2 semanas.

Retenção: % de usuários que retornam após 7 dias.

Método de teste

Lançamento para 50–100 usuários do público alvo em teste controlado.

Coleta de feedback qualitativo via entrevistas curtas e formulário simples.

Observação de onde o usuário trava no fluxo e ajustes rápidos.

Critérios de sucesso

Pelo menos 60% dos usuários conseguem registrar gastos sem ajuda após onboarding.

Precisão de classificação acima de 70% com confirmação.

NPS médio ≥ 4 em escala 1–5.

10 Riscos e mitigações
NLP falha e frustração

Mitigação: confirmação simples antes de salvar; opção de correção rápida.

Usuário não confia em privacidade

Mitigação: linguagem clara sobre uso de dados; opção de armazenamento local sem nuvem.

Complexidade excessiva

Mitigação: priorizar chat e resumo; adiar funcionalidades avançadas.

Acessibilidade negligenciada

Mitigação: testes com usuários reais de diferentes idades; ajustar fontes e contraste.

11 Entregáveis para submissão Lovable
PRD completo (este documento) em formato texto.

Fluxo de telas em texto com descrições de cada tela.

Protótipo de baixa fidelidade (wireframes simples) — opcional, mas recomendado.

Plano de validação com roteiro de testes e métricas.

Script de onboarding e exemplos de mensagens do chat para usar em testes.

12 Sugestões de conteúdo educativo dentro do app
Explicações curtas sobre termos como saldo, categoria, orçamento.

Mini-aulas de 1–2 frases sobre economia doméstica.

Exemplos práticos: “Se você gasta R$ 10 por dia com café, isso dá R$ 300 por mês.”

Checklist simples para reduzir gastos recorrentes.

13 Próximos passos recomendados
Validar o fluxo de chat com protótipos de conversa em papel ou Figma.

Construir um protótipo funcional do chat com NLP de regras para testes iniciais.

Recrutar 50 usuários do público alvo para teste de 2 semanas.

Ajustar categorias e mensagens com base no feedback.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
prd final:
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Documento de Requisitos do Produto PRD
Produto
Aplicativo de organização de finanças pessoais por conversa  
Tom: educativo, simples e acessível em Português do Brasil

Visão geral
Criar um aplicativo que permita organizar finanças pessoais usando conversa em linguagem natural. O foco é reduzir fricção: poucos campos para preencher, interface por chat, explicações simples e visuais claros. O app deve ajudar o usuário a entender sua situação financeira sem exigir planilhas complexas.

Objetivos do produto
Facilitar o registro de gastos por meio de conversas simples.

Classificar automaticamente transações em categorias úteis.

Gerar resumos e relatórios em linguagem acessível quando o usuário pedir.

Oferecer dicas práticas e acionáveis para melhorar a gestão financeira.

Garantir privacidade e segurança com explicações claras sobre uso de dados.

Público alvo e necessidades
Perfil: pessoas com pouca experiência digital e baixo conhecimento financeiro, de adolescentes a idosos.

Necessidades: linguagem simples; confirmação antes de salvar; visualização clara dos gastos; ajuda passo a passo; suporte texto e voz opcional.

Restrições: evitar jargões; minimizar telas e cliques; priorizar acessibilidade (tamanho de fonte, contraste, leitura por voz).

Requisitos do produto
Requisitos funcionais essenciais
Registro por chat: usuário informa gasto em texto ou voz; sistema confirma e salva.

Extração automática: identificar valor, data e categoria a partir da mensagem.

Classificação automática: categorias padrão como moradia, transporte, alimentação, saúde, lazer.

Resumo simples: cartão com saldo mensal, gasto total e categoria principal.

Histórico simplificado: lista cronológica com filtros por mês e categoria.

Dicas financeiras: sugestões curtas e acionáveis quando solicitadas.

Exportar resumo: gerar planilha ou PDF somente se o usuário pedir.

Ajuda contextual: explicações curtas sobre termos e ações.

Confirmação antes de salvar: sempre confirmar interpretação do gasto.

Modo offline básico: registrar gastos sem conexão e sincronizar depois.

Acessibilidade: texto grande, alto contraste, leitura por voz.

Requisitos não funcionais
Segurança: armazenamento local criptografado; backup opcional com senha.

Privacidade: linguagem simples explicando como os dados são usados.

Performance: resposta do chat em menos de 2 segundos para ações básicas.

Simplicidade: máximo 3 passos para registrar um gasto comum.

Compatibilidade: Android e iOS inicialmente; versão web leve futura.

Plano MVP
Telas principais do MVP
Boas-vindas e onboarding com 2–3 passos e exemplo prático.

Chat principal com campo de texto e botão de voz; mensagens do sistema em linguagem simples.

Cartão Resumo mostrando saldo mensal, gasto total e categoria mais cara.

Histórico simplificado: data, descrição curta, valor e categoria.

Tela de Dicas com 5 sugestões acionáveis.

Configurações e Ajuda: linguagem, acessibilidade e exportar resumo.

Funcionalidades mínimas para o MVP
NLP básico para extrair valor, data e categoria (regras + modelo leve).

Regras de classificação com fallback para confirmação manual.

Banco de dados local com sincronização opcional.

Gerador de resumo em linguagem natural com frases curtas.

Interface acessível com botões grandes e textos claros.

Mecanismo de confirmação antes de salvar transações.

Recursos técnicos necessários
Motor de NLP leve e configurável.

Backend simples para armazenamento e sincronização.

Criptografia local e opção de backup seguro.

UI/UX com foco em usabilidade e acessibilidade.

Módulo de dicas baseado em regras financeiras simples.

Validação inicial e métricas
Hipóteses a validar
Usuários conseguem registrar gastos via chat sem ajuda.

Classificação automática é aceitável com confirmação.

Dicas simples são compreendidas e aplicadas.

Métricas principais
Taxa de registro: registros por usuário por semana.

Taxa de confirmação: % de transações confirmadas sem correção.

Precisão de classificação: % de categorias corretas após confirmação.

Satisfação: NPS simples 1–5 após 2 semanas.

Retenção: % de usuários que retornam após 7 dias.

Método de teste
Lançamento para 50–100 usuários do público alvo em teste controlado.

Coleta de feedback qualitativo via entrevistas curtas e formulário simples.

Observação de pontos de fricção no fluxo e iteração rápida.

Critérios de sucesso iniciais
≥ 60% dos usuários conseguem registrar gastos sem ajuda após onboarding.

Precisão de classificação ≥ 70% com confirmação.

NPS médio ≥ 4 em escala 1–5.

Riscos e mitigações
NLP impreciso → Mitigação: confirmação simples antes de salvar; correção rápida.

Desconfiança sobre privacidade → Mitigação: explicações claras e opção de armazenamento local.

Complexidade excessiva → Mitigação: priorizar chat e resumo; adiar funcionalidades avançadas.

Acessibilidade insuficiente → Mitigação: testes com usuários reais e ajustes de UI.

Entregáveis para submissão Lovable
PRD completo (texto formatado).

Fluxo de telas em texto com descrições.

Protótipo de baixa fidelidade (wireframes simples) recomendado.

Plano de validação com roteiro de testes e métricas.

Script de onboarding e exemplos de mensagens do chat para testes.

Próximos passos recomendados
Validar o fluxo de chat com protótipos de conversa em papel ou Figma.

Construir um protótipo funcional do chat com NLP de regras para testes iniciais.

Recrutar 50 usuários do público alvo para teste de 2 semanas.

Ajustar categorias e mensagens com base no feedback.

(Prd Polido e Finalizado pelo Copilot)

Etapa 2 (prints):

<img width="1431" height="1012" alt="Captura de tela 2026-01-03 161334" src="https://github.com/user-attachments/assets/c2e00c78-e138-441c-b9a0-68bcbae97dd3" />

<img width="1432" height="739" alt="Captura de tela 2026-01-03 161325" src="https://github.com/user-attachments/assets/c20496ed-fcd1-48e1-982d-ad15edb7f5aa" />

<img width="1428" height="1012" alt="Captura de tela 2026-01-03 161321" src="https://github.com/user-attachments/assets/bb19909a-b1ef-4309-9f89-ca0dcb274ccf" />

<img width="1435" height="1006" alt="Captura de tela 2026-01-03 161248" src="https://github.com/user-attachments/assets/4ce1cbe2-fc09-4d97-bc7f-505532ff51c1" />

Etapa 3 (Resumo):

O PRD descreve um aplicativo de organização de finanças pessoais voltado para pessoas com pouca experiência digital ou conhecimento financeiro, abrangendo adolescentes até idosos. O diferencial é o uso de conversa em linguagem natural para registrar gastos, evitando planilhas complexas e interfaces confusas. O sistema interpreta mensagens simples como “gastei R$20 no mercado”, classifica automaticamente em categorias (moradia, transporte, alimentação etc.), gera resumos claros com saldo mensal e principais despesas, e oferece dicas práticas para melhorar a gestão financeira. O MVP inclui telas básicas de boas-vindas, chat principal, resumo rápido, histórico simplificado e sugestões financeiras. A validação inicial prevê testes com usuários reais, medindo taxa de registros, precisão de classificação e satisfação. O foco é ser educativo, acessível e seguro, com interface simples, explicações claras sobre privacidade e recursos de acessibilidade como texto grande e contraste.

Etapa 4 (Refexão)

Ao elaborar este PRD, percebi que consegui traduzir uma necessidade real em um projeto concreto. No início, havia apenas a intenção de criar um aplicativo acessível para pessoas com pouca familiaridade digital. Com o processo, fui organizando ideias, detalhando funcionalidades e pensando em como simplificar a experiência do usuário. O maior desafio foi manter a linguagem simples e acessível, sem cair em termos técnicos que poderiam afastar o público. Também foi importante entender o conceito de MVP: aprendi que não é preciso construir tudo de uma vez, mas sim validar hipóteses com o mínimo necessário. No fim, sinto que me saí bem porque consegui alinhar visão, requisitos e plano de ação em um documento claro, que pode ser usado tanto para guiar o desenvolvimento quanto para apresentar a proposta em um curso.




