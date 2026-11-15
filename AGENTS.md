# Instruções para agentes — Reddit Stories

## Hierarquia de referência

1. `IDENTIDADE_EDITORIAL.md` é a norma editorial principal.
2. `docs/PIPELINE_EDITORIAL.md` descreve o fluxo de elaboração e validação.
3. `templates/` fornece convenções e modelos adaptáveis.
4. Arquivos específicos da história registram suas decisões e seu cânone.

Se houver conflito, sinalize-o; não altere silenciosamente fatos, documentos normativos ou decisões já aprovadas. Distinguir sempre **confirmado**, **proposto**, **indeterminado** e **pendente de aprovação**.

## Trabalho editorial

- O primeiro episódio segue o autor do relato original, preservando o conflito, acontecimentos essenciais e desfecho que ele efetivamente relatou. Não converter automaticamente suas alegações em fatos objetivos.
- Outras perspectivas só pertencem a personagens diretamente envolvidos no evento central. Não criar narradores periféricos para aumentar a série.
- Cada perspectiva deve ser compreensível isoladamente, em primeira pessoa, e pode alternar depoimento e cenas dramatizadas.
- Expansões ficcionais podem desenvolver antecedentes, diálogos, motivações e consequências não descritas, sem contradizer o cânone.
- Manter evento âncora detalhado; registrar eventos compartilhados quando sua consistência entre versões importar. Não burocratizar eventos individuais sem necessidade.
- Separar fato canônico, alegação, interpretação, conhecimento, omissão e indeterminação. Contradições entre relatos só podem ser intencionais e rastreáveis.
- Não explicar didaticamente ao público que narradores podem mentir.
- Preservar desfechos não felizes, ambíguos ou inconclusivos quando coerentes; não fabricar polêmica ou reviravolta.
- O áudio precisa carregar toda informação essencial, sem depender de imagens.
- A identidade vocal e linguística do personagem é independente de fornecedor, modelo ou configuração de TTS.

## Processo e edição de arquivos

1. Antes de escrever, ler a fonte e os arquivos existentes da história.
2. Propor estrutura e apontar lacunas relevantes antes de fixar fatos novos importantes.
3. Não modificar `canon/` para acomodar um roteiro sem explicar a divergência e solicitar aprovação.
4. Usar IDs estáveis para eventos (`EVT-...`), personagens (`CHR-...`) e perspectivas (`POV-...`); referências cruzadas devem apontar para IDs existentes.
5. Não duplicar fontes de verdade: `cronologia.yaml` ordena eventos; `eventos.yaml` descreve fatos; perspectivas referenciam IDs.
6. Manter o roteiro legível em Markdown, com marcações simples de cena, narrador, diálogo e som; não fixar esquema dependente de TTS.
7. Ao revisar, produzir relatório de inconsistências e pendências; não 'corrigir' ambiguidades deliberadas.
8. Evitar gerar áudios, vídeos, assets ou código de produção sem pedido explícito.

## Fontes, direitos e publicação

- Registrar URL, data de consulta, atualizações relevantes e o que foi alegado pelo autor; não afirmar que o Reddit prova a veracidade dos fatos.
- Não copiar ou traduzir longamente o texto original. Crédito/link não substitui direitos autorais ou permissão.
- Identificar perspectivas adicionais como ficção; preservar privacidade e avaliar riscos de identificação.
- Classificação etária é individual por vídeo. Conteúdo geral, conteúdo feito para crianças e restrição 18+ são categorias distintas.
- Todas as perspectivas completas de uma série devem ser disponibilizadas simultaneamente; se uma atrasar, adiar o conjunto.
- Não inventar links, status de publicação, autorizações ou aprovações.

## Ferramentas e armazenamento

O repositório guarda textos e configurações. Não versionar áudios/vídeos gerados, caches, credenciais, tokens, modelos ou pesos. A seleção de TTS, ComfyUI, serviços cloud e renderização permanece em aberto.

## Conclusão de tarefa

Relatar arquivos criados/alterados, decisões assumidas, validações realizadas e pendências. Não declarar uma história 'aprovada' sem revisão editorial explícita.
