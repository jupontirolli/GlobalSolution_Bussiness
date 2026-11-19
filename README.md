ZelaCidade — CitizenTech · Global Solution 2026.2

Registro e triagem de problemas urbanos por prioridade de risco: app mobile para o cidadão e painel web para a prefeitura.

FIAP · 2SI · Business Systems Planning, Analysis & Design Professor: Prof. Me. Junior F. de Amaral

Integrante	RM	Papel Scrum
Amanda Silveira Benezato	566756	Product Owner + Time de Desenvolvimento
Júlia Santino Pontirolli de Araujo	567736	Scrum Master + Time de Desenvolvimento
O problema

Buracos, postes apagados e lixo descartado na calçada fazem parte do dia a dia de muitos bairros. Hoje o morador precisa ligar para a central 156 ou ir à subprefeitura, descrever o local por pontos de referência e, quase sempre, fica sem notícias. Do lado da prefeitura, os pedidos chegam incompletos ou duplicados e entram numa fila sem critério de urgência.

Nas entrevistas com 4 moradores, 3 não reclamaram por não saber como fazer, e nenhum foi avisado quando o problema foi resolvido.

A solução

O ZelaCidade permite que o morador registre buracos, postes apagados e descarte irregular de lixo com foto e GPS, receba um protocolo e acompanhe o atendimento. A prefeitura recebe os pedidos já ordenados por prioridade de risco (1 a 10), e não por ordem de chegada. Chamados duplicados no mesmo local viram "apoios" ao chamado existente, e o cidadão confirma se o problema foi mesmo resolvido (ou reabre a ocorrência).

ODS da ONU: ODS 11 — Cidades e Comunidades Sustentáveis (metas 11.3 e 11.6), com contribuição complementar ao ODS 16 (meta 16.6).

Entregas
Entrega	Conteúdo	Arquivo
Documento completo	Capa, D1 a D4, referências e Anexo A	GS_2026.2_ZelaCidade.pdf
D1 — Processo de Produção de SI	Ciclo de vida incremental, processo ágil (Scrum), Product Backlog com 13 requisitos priorizados (MoSCoW), 2 Sprints, tripla restrição e ODS	No PDF
D2 — BPMN (Bizagi)	AS-IS e TO-BE com raias, gateways rotulados, data objects e tarefas de usuário/serviço	D2_BPMN/
D3 — Protótipo (Pencil)	6 telas: login, cadastro LGPD, minhas ocorrências, registro, protocolo e painel de triagem	D3_Prototipo_Pencil/
D4 — Storyboard	8 quadros da jornada da Dona Marta: problema → solução → impacto	D4_Storyboard/
Entrevistas	Respostas completas dos 4 moradores (roteiro de 11 perguntas)	entrevistas_gs.txt
Estrutura do repositório
├── README.md
├── GS_2026.2_ZelaCidade.pdf
├── entrevistas_gs.txt
├── D2_BPMN/
│   ├── ZelaCidade_BPMN_AS-IS_TO-BE.bpm   # arquivo nativo do Bizagi (uma aba por diagrama)
│   ├── ZelaCidade_AS-IS.png
│   └── ZelaCidade_TO-BE.png
├── D3_Prototipo_Pencil/
│   ├── ZelaCidade_Prototipo_Pencil.epgz  # arquivo nativo do Pencil (uma página por tela)
│   └── ZelaCidade_Tela1.png … ZelaCidade_Tela6.png
└── D4_Storyboard/
    └── Quadro1.png … Quadro8.png
Prévia
Processo TO-BE (com o ZelaCidade)

TO-BE

Protótipo
Registrar ocorrência	Protocolo e acompanhamento
Tela 4	Tela 5

Painel de triagem

Como abrir os arquivos nativos
.bpm — Bizagi Modeler (gratuito), versão 4.3 ou superior.
.epgz — Pencil Project (gratuito), versão 3.1 ou superior.
Organização da Sprint (Scrum)
Sprint	Meta	Itens do Backlog
Sprint 1	O cidadão consegue registrar um problema, de forma simples, e receber um protocolo	RF01, RF02, RF03, RNF01, RNF02
Sprint 2	A prefeitura atende primeiro o que é mais urgente, e o cidadão acompanha	RF04, RF05, RF06, RF07

Definition of Done: requisito testado, ligado ao processo TO-BE e publicado neste repositório.

Privacidade (LGPD)

Todos os dados que aparecem no protótipo e no storyboard são fictícios (persona Dona Marta, protocolo ZC-2026-004817, CPF mascarado). Os entrevistados estão identificados apenas pelo primeiro nome, sem CPF ou outros dados pessoais.

Referências principais
PRESSMAN, R. S.; MAXIM, B. R. Engenharia de Software: uma abordagem profissional. 9. ed. AMGH, 2021.
SOMMERVILLE, I. Engenharia de Software. 10. ed. Pearson, 2019.
SCHWABER, K.; SUTHERLAND, J. The Scrum Guide. 2020.
OMG. BPMN 2.0 Specification.
PMI. Guia PMBOK. 7. ed. 2021.
BRASIL. Lei nº 13.709/2018 (LGPD).

A lista completa, com o benchmarking (SP156, Colab, FixMyStreet) e as fontes do ODS 11, está no PDF.
