# Imagens

| Arquivo | Onde aparece | Origem | Estado |
|---|---|---|---|
| `escritorio.jpg` | Hero da home | Foto do interior, perfil do Google | 715×866, 80 KB — **baixa resolução** |
| `janaina.jpg` | Seção "Quem faz" | Foto de perfil do Instagram | 158×158, 7 KB — exibida em 132px |

Convertidas de `../../../Fotos e Imagens/`.

`escritorio.jpg` entra no hero via `background-image` — se o arquivo faltar, o
bloco mostra um fundo dourado em vez de ícone de imagem quebrada.
`janaina.jpg` é `<img>` com `width`/`height` declarados, recortada da foto de
perfil dela — a única foto sem texto sobreposto que existe hoje, e a que ela
mesma escolheu para se representar.

## Por que não tem foto da entrada

Existia e foi retirada. A foto da porta é um corredor de parede salmão com
placa de extintor ao lado — visualmente fraca, e o ganho de "reconhecer a
porta" não pagava o custo de fechar o site com aquela imagem.

## Depois de fechar

1. **Retrato dela em alta** — o atual tem 158px de origem. Funciona em 132px,
   não escala.
2. **O interior em alta resolução** — serve para a demo, fica apertado em tela
   grande.
3. **Arquivo vetorial da logo dourada** — a da parede do escritório, não a
   azul-marinho que aparece nos monitores. **Não recriar a logo.**
