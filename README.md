# Apresentação — Defesa do TCC 2

- **Slides:** `tcc2.html` (slides 1–34 + 6 *backups*), estilos extras em `css/tcc2.css`.

Slides em HTML (reveal.js), **100% offline** — não dependem de internet no dia da defesa.

## Como apresentar

Abra o `tcc2.html` em qualquer navegador (duplo clique basta).

| Tecla | Ação |
|---|---|
| `→` / `←` ou `Espaço` | avançar / voltar |
| `F` | tela cheia |
| `Esc` | visão geral de todos os slides |
| `B` ou `.` | tela preta (pausa) |
| `Alt + clique` | zoom em um trecho |

Os *backups* (selo `BACKUP`) ficam depois do encerramento e servem só para responder perguntas da banca.

## PDF de backup

Para gerar uma cópia estática, abra `tcc2.html?print-pdf` no Chrome e imprima
(Ctrl+P → Salvar como PDF).

## Editando

- Conteúdo: `tcc2.html` (um `<section>` por slide, comentários indicam a numeração).
- Visual: `css/tema.css` (paleta de cores nas variáveis `:root` do topo) e `css/tcc2.css`.
  Após mudar o CSS, troque o `?v=` do link em `tcc2.html` para o navegador não usar o cache.
- Fórmulas: KaTeX — inline `\( ... \)`, destaque `$$ ... $$`.
- `vendor/` contém reveal.js 5.2.1 e KaTeX 0.16.22 — não editar.
