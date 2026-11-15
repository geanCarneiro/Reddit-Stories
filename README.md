# Reddit Stories — projeto editorial

Antologia de audiobooks dramatizados de ficção inspirada em relatos do Reddit, predominantemente dramática, narrada em primeira pessoa e, quando a trama justificar, por perspectivas independentes dos envolvidos.

> **Estado:** estrutura editorial inicial. Nome comercial, identidade visual e ferramentas de produção ainda não foram definidos.

## Princípios

A fonte normativa é [IDENTIDADE_EDITORIAL.md](IDENTIDADE_EDITORIAL.md). A primeira perspectiva preserva a essência, os acontecimentos essenciais e o desfecho relatados na publicação original; as demais são expansões ficcionais, não depoimentos autênticos. Os episódios são completos por si só, acessíveis apenas pelo áudio e publicados simultaneamente dentro de cada série.

## Organização

- `historias/`: uma pasta por história, contendo fonte, cânone, personagens, perspectivas e planejamento de publicação.
- `templates/`: modelos para iniciar histórias e manter nomenclatura consistente.
- `vozes/`: catálogo de identidades vocais independente do fornecedor de TTS.
- `docs/PIPELINE_EDITORIAL.md`: processo de seleção, planejamento, escrita e revisão.
- `AGENTS.md`: regras de atuação de agentes de IA no repositório.

## Fluxo inicial

1. Ler `IDENTIDADE_EDITORIAL.md` e `AGENTS.md`.
2. Criar `historias/<slug>/` a partir de `templates/historia-base/`.
3. Registrar a fonte e distinguir alegações de fatos estabelecidos.
4. Elaborar evento âncora, eventos compartilhados e cronologia.
5. Criar fichas dos personagens e planejar perspectivas relevantes.
6. Redigir a perspectiva original primeiro e as demais com revisão cruzada.
7. Registrar pendências e validar antes de aprovar qualquer série.

O repositório armazena **texto, metadados e configurações**. Áudio, vídeo, caches e material pesado permanecem fora do Git, inicialmente no computador local.

## Estado e limites

Este repositório não define TTS, ComfyUI, renderização, calendário ou identidade visual. Templates são pontos de partida, não obrigação de preencher campos irrelevantes. Não iniciar produção ou publicação sem decisão explícita.
