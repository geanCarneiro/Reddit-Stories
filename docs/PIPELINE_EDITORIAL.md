# Pipeline editorial — da fonte aos roteiros

**Escopo:** planejamento e escrita. Não prescreve síntese de voz, edição, renderização ou publicação automatizada.

## Portões de decisão

### 0. Seleção da fonte
Registrar URL, autor conforme exibido na fonte, data de consulta, texto de referência e atualizações pertinentes. Identificar questões de direitos, privacidade e conteúdo sensível. Não presumir veracidade factual.

**Saída:** `fonte/referencias.yaml`, `fonte/resumo.md`.

### 1. Extração do relato
Separar o que o autor diz que ocorreu, interpretações, desfecho informado, lacunas e personagens diretamente envolvidos. Não tratar alegações subjetivas como cânone objetivo.

**Saída:** primeira versão de `historia.yaml` e notas de fonte.

### 2. Construção do cânone
Definir o evento âncora detalhadamente; registrar eventos compartilhados que precisam permanecer consistentes; ordenar os eventos na cronologia. Indicar fatos canônicos, alegações e pontos indeterminados. Não estabelecer detalhes desnecessários.

**Saída:** `canon/eventos.yaml`, `canon/cronologia.yaml`.

### 3. Fichas de personagens
Definir relação com o evento, objetivos, traços, maneira de falar, o que presenciou, o que sabe por terceiros, o que acredita e o que oculta. Descrever identidade vocal de forma agnóstica a tecnologia.

**Saída:** `personagens/<id>.yaml`.

### 4. Planejamento das perspectivas
Selecionar apenas narradores diretamente envolvidos. Definir o valor narrativo específico de cada versão, recorte temporal, cenas comuns, revelações e omissões. O primeiro episódio preserva a essência do relato original. Todos devem ser autossuficientes.

**Saída:** `perspectivas/<slug>/plano.yaml`.

### 5. Roteirização
Escrever `roteiro.md` em primeira pessoa, alternando depoimento e cenas dramatizadas quando adequado. Usar marcadores de cena, personagem e efeitos de forma legível. Flashbacks e início pelo clímax são opcionais. Não alongar artificialmente para atingir duração.

**Saída:** `perspectivas/<slug>/roteiro.md`.

### 6. Revisão cruzada
Verificar fatos do evento âncora, gestos compartilhados, limites de conhecimento, referências a outros episódios, coerência das vozes/linguagem e ausência de dependência visual. Marcar divergências deliberadas; registrar problemas e propostas de correção sem mudar o cânone silenciosamente.

**Saída:** `revisao.md` com pendências e estado de aprovação.

### 7. Aprovação editorial
Revisar fidelidade à fonte, qualidade narrativa, autonomia, direitos, adequação etária por perspectiva e consistência. Só então declarar os roteiros prontos para produção. Todas as perspectivas completas da série serão lançadas simultaneamente, mas o planejamento de distribuição ocorre em etapa posterior.

## Regras transversais

- Trabalhar por etapas; cada etapa pode voltar à anterior mediante revisão explícita.
- Propostas de agentes não equivalem a decisões aprovadas.
- Referenciar eventos por ID, evitando repetir a definição do mesmo fato em múltiplos arquivos.
- A matriz de continuidade pode ser derivada das referências dos eventos e perspectivas; não manter outra fonte de verdade concorrente.
- A duração de 15–20 minutos é meta, não exigência de preenchimento.
