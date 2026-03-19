# Aprenda LLM — Notebooks

## Estrutura do Repositório

```
ChapterXX/
└── CHXX_Lesson1.ipynb
```

Onde `XX` é o número do capítulo com zero à esquerda (00, 01, 02...).

## Regras para Notebooks

### Estrutura de Células

- **Imports no topo:** Primeira célula de código contém todos os imports
- **Markdown entre código:** Cada bloco de código deve ser precedido por uma célula Markdown explicando o que será feito e por quê
- **Execução linear:** O notebook deve funcionar de cima para baixo sem pular células

### Regras para Exemplos de Código

1. **Identificar variáveis pelo papel real** — Toda célula de código deve ter comentários explicando o que cada variável representa no contexto do conceito. Exemplo: `w = 0.5  # peso (weight) — quanto esta entrada influencia a saída`. Nunca assumir que o nome da variável é autoexplicativo para o aluno.

2. **Incluir uma demo interativa de "aha"** — Cada notebook deve ter pelo menos um exemplo onde um valor muda visivelmente ao longo de iterações (loss diminuindo, peso convergindo, acurácia subindo), com print ou gráfico mostrando a evolução. O aluno precisa *ver* o conceito funcionando, não apenas ler sobre ele.

3. **Incluir glossário de termos técnicos** — A introdução de cada notebook deve terminar com um glossário definindo termos técnicos e abreviações que aparecem no texto ou código. Formato: termo em negrito seguido de definição curta. Incluir no mínimo: todas as abreviações (PII, BPE, RLHF, etc.), nomes de frameworks (AdamW, GradScaler, etc.) e jargão de domínio não óbvio para iniciantes.

## Materiais Complementares

Cada notebook tem correspondentes em outros repositórios:

- **Roteiro de vídeo:** `/home/dataseek/projects/PD/aprenda-llm-videos/CHXX/Lesson1.txt`
- **Conteúdo do site:** `/home/dataseek/projects/PD/MagesticWeb/src/data/lessonContent.ts` (bloco do capítulo correspondente)

Ao alterar exemplos de código no notebook, verificar se os exemplos nos materiais complementares precisam ser atualizados para manter consistência.
