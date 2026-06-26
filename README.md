# tela-visualiza-o-trilha

Tela estática de visualização de trilha (Lector) com sidebar de etapas, lista de conteúdos, leitor de PDF/vídeo, gráfico de desempenho e fluxo de certificado.

## Versões Vanilla (sem dependências)

O objetivo principal deste repositório agora inclui versões **100% puras** (HTML + CSS + JS), sem nenhuma biblioteca externa, fontes externas ou dependências. Elas podem ser usadas em qualquer lugar:

- **`trilha-vanilla.html`** — Recriação completa e fiel da tela principal de visualização da trilha.
  - Sidebar com etapas (accordion)
  - Conteúdos clicáveis (PDF, vídeo, avaliações, etc.)
  - Leitor overlay com visualizador de documento puro + player de vídeo customizado (funciona mesmo sem os arquivos de mídia)
  - Tabs: Descrição / Desempenho / Relatórios
  - Gráfico de barras animado + filtro por etapa
  - Marcadores de visualização + donuts P/A dinâmicos
  - Fluxo de certificado
  - Totalmente responsivo + mobile
  - **Zero dependências** — pode ser copiado para qualquer projeto

- **`certificado-vanilla.html`** — Certificado de conclusão (A4 landscape) pronto para impressão/PDF, também 100% standalone.

Esses arquivos foram criados para que os componentes possam ser reutilizados em qualquer contexto sem precisar de nada externo.

## Arquivos originais (com dependências)

- `index.html` / `Trilha Conteudo (Dir A).html`
- `Trilha Desempenho.html`
- `Trilha Wireframes.html`
- `certificado.html`

Estes usam fontes do Google e ícones personalizados (pasta `assets/lector-icons`).

## Como usar as versões Vanilla

1. Copie `trilha-vanilla.html` (e opcionalmente `certificado-vanilla.html`) para o local desejado.
2. Abra diretamente no navegador.
3. (Opcional) Coloque arquivos de mídia na pasta `uploads/` para usar os vídeos/PDFs reais (o player customizado funciona independente disso).

Tudo é autossuficiente — sem Node, sem build, sem CDNs.

## Estrutura

```
trilha-vanilla.html          → Versão principal sem dependências
certificado-vanilla.html     → Certificado puro
uploads/                     → Mídias de exemplo (opcional)
assets/                      → Ícones e logo originais
```

## Tecnologias

- HTML5 + CSS3 + JavaScript vanilla (sem frameworks)
- SVG inline para todos os ícones
- Conic gradients, custom properties e animações nativas
- Player de vídeo customizado em JS puro (além do `<video>` nativo quando disponível)

## Contribuição

Sinta-se à vontade para usar os componentes em seus projetos.
