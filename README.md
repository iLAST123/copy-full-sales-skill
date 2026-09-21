# Copy Full Sales

Skill portatil para escrever e revisar copy assinada pela Full Sales. O pacote ja contem
as regras de marca, modos por canal e checklist; nao depende do brain ou dos arquivos da
maquina em que foi criado.

## Conteudo do pacote

```text
copy-full-sales/
├── README.md
├── SKILL.md
└── references/
    ├── anuncios-criativos.md
    ├── checklist-final.md
    ├── escrita-e-revisao.md
    ├── regras-da-marca.md
    └── whatsapp.md
```

Copie sempre a pasta inteira. Nao distribua apenas o `SKILL.md`.

## Instalar no Codex

Copie `copy-full-sales/` para:

```text
${CODEX_HOME:-$HOME/.codex}/skills/copy-full-sales/
```

Depois, inicie uma nova tarefa para atualizar a descoberta de skills e invoque:

```text
$copy-full-sales Escreva um disparo de WhatsApp para [oferta], usando somente as provas anexadas.
```

## Instalar no Claude Code

Para uso pessoal, copie a pasta para:

```text
~/.claude/skills/copy-full-sales/
```

Para compartilhar dentro de um projeto, copie para:

```text
<projeto>/.claude/skills/copy-full-sales/
```

Invoque com:

```text
/copy-full-sales Revise esta copy e preserve literalmente os blocos marcados como aprovados.
```

## Briefing recomendado

Inclua, quando existirem:

- oferta e pagina ou documento vigente;
- canal e formato;
- publico e estagio do funil;
- acao esperada;
- provas com suas fontes;
- blocos ja aprovados;
- disparos recentes para a mesma base.

A skill nao publica, envia ou programa pecas. Essas acoes continuam exigindo autorizacao
separada.
