# CLAUDE.md

## Propósito do repositório

Este é o **repositório de README de perfil do GitHub** do usuário `bastelliWill`
(o nome do repositório é igual ao do usuário, então o GitHub renderiza o
`README.md` na página de perfil em github.com/bastelliWill).

Não há código de aplicação, sistema de build, dependências ou suíte de
testes — o repositório inteiro é um único arquivo Markdown.

## Estrutura

- `README.md` — conteúdo da página de perfil (em português). Contém:
  - Uma seção de cabeçalho/introdução com badges de tecnologia (Oracle,
    PL/SQL, SQL, WMS) usando URLs do `img.shields.io`.
  - Uma seção "Sobre mim" descrevendo a experiência do autor como
    desenvolvedor Oracle/PL/SQL focado em back-end de sistemas WMS
    (Warehouse Management System).
  - Uma lista de "Áreas de atuação".
  - Um card de estatísticas do GitHub via `github-readme-stats.vercel.app`.

## Convenções de trabalho

- Manter o conteúdo em português (pt-BR), seguindo o tom já existente, a
  menos que o usuário peça explicitamente outro idioma.
- Preservar o layout centralizado em HTML (`<p align="center">`,
  `<h1 align="center">`) e o estilo de badges shields.io / github-readme-stats
  ao adicionar novas seções.
- As alterações são puramente edições de conteúdo/formatação no
  `README.md` — não há nada para buildar, lintar ou testar.
- Ao adicionar badges, seguir o padrão existente:
  `https://img.shields.io/badge/<label>-<color>?style=for-the-badge&logo=<logo>&logoColor=white`.

## Fluxo de trabalho com Git

- Desenvolver na branch indicada para a tarefa, commitar com mensagens
  claras e fazer push ao finalizar.
- Não abrir pull request a menos que seja solicitado explicitamente.
