# LinkedIn Top Voice — Skill para o Claude

Skill que ajuda a criar, revisar e otimizar posts de LinkedIn com base nas estratégias de Top Voice 2026: ganchos, formatos (carrossel, vídeo, texto), regras do algoritmo, calendário editorial e templates prontos.

## Como instalar

### Opção 1 — Claude (app ou site)

1. Baixe o ZIP deste repositório (Code → Download ZIP).
2. Confirme que o ZIP contém a pasta `linkedin-top-voice/` com o arquivo `SKILL.md` dentro.
3. No Claude, vá em Configurações → Capacidades → Skills e faça o upload do ZIP.
4. Ative a skill.

### Opção 2 — Claude Code

```bash
git clone https://github.com/rodrigosilvafernandessantos-a11y/linkedin-top-voice-skill.git
cp -r linkedin-top-voice-skill/linkedin-top-voice ~/.claude/skills/
```

## Como usar

Peça normalmente, por exemplo:

- "Me ajuda com um post sobre [tema]"
- "Cria um carrossel sobre [tema]"
- "Monta meu calendário editorial da semana"

Na primeira vez, a skill pergunta seu nome, cargo, objetivo e pilares de conteúdo. Se preferir, edite a seção "Contexto do usuário" no `SKILL.md` e deixe tudo preenchido de uma vez.

## Estrutura

```
linkedin-top-voice/
├── SKILL.md
└── references/
    └── estrategia-completa.md
```
