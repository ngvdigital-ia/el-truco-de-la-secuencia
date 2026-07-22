# Design — El Truco de La Secuencia

## Direção

Clone fiel e deliberadamente mínimo da página oficial: uma aula desbloqueada, com foco total no título e no vídeo vertical. A página não adiciona promessa, botão, seção, card ou elemento que não exista na referência.

## Sistema visual

- Base: `#FFFFFF`.
- Texto: `#000000`.
- Tipografia: Roboto, peso 600 no título; Arial/sans-serif como fallback.
- Título desktop: `32px`, largura máxima de `980px`, centralizado, entrelinha `1.18`.
- Título mobile: `24px`, alinhado à esquerda, entrelinha `1.2`.
- Player: largura máxima de `400px`, proporção vertical `9:16`, centralizado.
- Espaçamento: escala `8, 16, 24, 32, 40, 48px`.
- Bordas, sombras e movimento: nenhum.

## Exceção de fidelidade

O título não usa escala hero de 48px ou mais porque a referência oficial usa uma hierarquia menor. A fidelidade ao clone prevalece sobre o padrão genérico de landing page.

## Estados pendentes

- Até a entrega do VTurb próprio, o espaço do player permanece como placeholder neutro, sem carregar o vídeo do concorrente.
- UTMify Pixel próprio instalado (pixelId `6a61400b91a343f941af13de`), via loader ofuscado no `<head>` para dificultar cópia por concorrentes.
- Meta Pixel só entra quando o ID próprio for entregue.
- Nenhum conteúdo é exibido depois do vídeo até a configuração final do player.

