<p align="center">
  <img src="https://raw.githubusercontent.com/Simulacao-ROV-BlueVecHub/.github/main/profile/assets/hero.svg" alt="ROV descendo por um tether ate um manifold no leito marinho" width="100%">
</p>

# Simulação ROV — BlueVecHub

Organização do setor de simulação da BlueVecHub.

## O que fazemos

Construímos cenários de simulação de operações ROV e subsea na plataforma VMAX:
ambientes onde um piloto treina a operação inteira — descida, aproximação,
conexão, intertravamento, recolhimento — antes que ela aconteça no mar.

Um cenário não é um modelo bonito. É física que precisa bater com a
engenharia: massa e empuxo calibrados com dados reais, colisões que respeitam
geometria de equipamento, cabos com raio mínimo de curvatura, lógica de
travamento que só fecha quando as condições da operação real seriam atendidas.
Quando o número está errado, o piloto aprende o gesto errado — e é por isso que
o trabalho aqui é mais parecido com engenharia de simulação do que com
produção de conteúdo 3D.

Esta organização guarda o que sustenta esse trabalho: as ferramentas, os
scripts, a configuração da equipe e a base de conhecimento técnico acumulada.

<p align="center">
  <img src="https://raw.githubusercontent.com/Simulacao-ROV-BlueVecHub/.github/main/profile/assets/fases.svg" alt="Fases de uma operacao: descida, aproximacao, conexao, intertravamento e recolhimento" width="100%">
</p>

## O que vive aqui

**Ferramentas e conhecimento** — servidor MCP próprio que liga assistentes de
IA à documentação da plataforma e ao editor de cenários, com uma base de
memória técnica curada. Cada aprendizado entra por revisão e carrega a origem
da evidência: confirmado pelo fornecedor, validado localmente, ou pendência
declarada. O que custou horas de depuração vira uma linha que a próxima pessoa
encontra em segundos.

**Workspace de cenários** — fonte versionada dos scripts, do contexto de cada
cenário e da configuração compartilhada entre as máquinas da equipe.

Os repositórios são privados. Esta página existe para dar contexto a quem
chega.

## Como o trabalho se organiza

Três canais, um papel cada:

- **Git** conta o que mudou — decisão técnica, o que foi tentado e falhou, o
  que ficou pendente.
- **Gestão de tarefas** conta onde estamos — status, responsável, o que trava.
- **Armazenamento compartilhado** entrega o arquivo final ao instrutor.

Dois princípios que valem para tudo aqui dentro:

**Regra sem mecanismo não pega.** Convenção que depende de alguém lembrar volta
a ser violada. Sempre que possível a regra vira verificação automática — e
falha alto, na hora, em vez de silenciosamente meses depois.

**Conhecimento curado tem portão.** Aprendizado técnico local é rascunho; vira
canônico por revisão explícita, nunca por promoção automática. O valor de uma
base curada é exatamente ser curada.

## Equipe

| | Atuação |
|---|---|
| **Renan Gonçalves** | Arquitetura do setor, ferramental de IA e integração com o editor, física e calibração |
| **Linda Vogt** | Modelagem e preparação de ativos, cenários de acessibilidade e lançamento |
| **Bernardo Arouca** | Programação de cenários, lógica de intertravamento, cabos e restrições |

## Autoria

Organização, arquitetura técnica e ferramental **criados e desenvolvidos por
Renan Gonçalves**.

---

<sub>BlueVecHub · Simulação de operações submarinas</sub>
