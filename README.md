# Docência com IA

Skills, agentes e modelos para professores usarem o Claude Code (ou o Codex) no preparo de aulas, na avaliação e na pesquisa (Medicina, CEUNSP).

## O que é cada coisa

- **Skill:** um arquivo de instruções que ensina o Claude a fazer uma tarefa do jeito certo (por exemplo, um plano de aula). Ele carrega a skill sozinho quando a tarefa aparece.
- **Agente:** um assistente com um papel fixo (planejador, elaborador de questões, corretor) que segue as skills e trabalha por etapas.
- **Conector:** a ligação do Claude com um serviço seu (Gmail, Agenda, Drive, NotebookLM); você autoriza cada um na sua conta.
- **CLAUDE.md:** as regras da pasta; valem para todo trabalho feito nela.

## Como instalar

Com o Claude Code aberto na pasta de docência, cole:

    Instale as skills e os agentes do repositório github.com/ricamesq/docencia-com-ia no meu Claude Code e copie o modelos/CLAUDE.md para esta pasta.

No Codex, peça o mesmo e troque CLAUDE.md por AGENTS.md.

## O que tem aqui

| Pasta | Para quê |
|---|---|
| skills/regras-docentes | regras para todo material (ABNT, sem dado de paciente, sem identificar aluno) |
| skills/plano-de-aula | plano com objetivos, organizador prévio, atividades e avaliação |
| skills/banco-de-questoes | questões com gabarito comentado, objetivo e nível |
| skills/rubrica-de-avaliacao | rubrica analítica com critérios e níveis observáveis |
| skills/apresentacao-de-aula | slides no padrão: título que descreve, marcadores curtos, ilustração |
| skills/bibliometria | busca na literatura sem erro de contagem |
| skills/vosviewer | mapas de coautoria e de palavras-chave no VOSviewer |
| agents/planejador-de-aula | planeja aula ou sequência a partir do tema e da ementa |
| agents/elaborador-de-questoes | elabora questões de prova |
| agents/corretor-com-rubrica | sugere a avaliação pela rubrica; a nota é do professor |
| agents/leitor-de-artigo | leitura crítica de artigo científico |
| agents/conferidor-de-referencias | confere DOI e PMID e formata pela NBR 6023 |
| agents/caso-ficticio | caso clínico fictício para aula ou prova prática |
| modelos/CLAUDE.md | regras da pasta de docência |

Para os alunos: https://github.com/ricamesq/estudar-com-ia

## Ferramentas de terceiros (instalar pela origem)

- graphify, mapa dos materiais: https://github.com/Graphify-Labs/graphify (pacote graphifyy)
- watch, resumo de vídeos: https://github.com/bradautomates/claude-video
- anatomy, figuras explicativas em SVG: https://github.com/wheresryan22/anatomy
- Zotero no Claude: https://github.com/54yyyu/zotero-mcp
- NotebookLM no Claude (não oficial, uso pessoal): https://github.com/jacob-bd/notebooklm-mcp-cli

## Cuidado

Nada de dado de paciente nem dado que identifique aluno em pedido ou arquivo: o que a IA lê vai para o modelo.
