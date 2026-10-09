# Desenvolvimento

[← voltar ao README](../README.md)

Painel em Python puro (só a biblioteca padrão) com HTML/JS sem dependências.
O motor, o servidor e as telas comuns vêm do modelo;
os detalhes deles e as armadilhas conhecidas estão no `LEIAME.md` de lá.

## Receitas

| id | nome | afetada por |
|---|---|---|
| 00 | backup (cópia de segurança do que existe hoje) | |
| 10 | pacotes do repositório Debian | |
| 20 | fontes de interface e monospace |  |
| 30 | tema WhiteSur das janelas | `destaque` |
| 31 | ícones WhiteSur | |
| 32 | cursores WhiteSur | |
| 33 | papéis de parede Big Sur | |
| 34 | tema WhiteSur nos programas Qt | `tema` |
| 38 | barra do topo, estilo macOS | `tema`, `logo`, `menu_global`, `titulo_no_painel` |
| 40 | tema, fontes, botões e papel de parede | `tema`, `destaque`, `papel_de_parede` |
| 42 | cores e transparência do terminal |  |
| 43 | atalhos de teclado | |
| 44 | encaixe, bordas e atalhos de janela | `janelas`, `tema`, `destaque` |
| 50 | barra de menus do programa ativo | `menu_global` |
| 60 | dock inferior | `dock` |
| 61 | novo terminal no clique direito | `dock` |
| 70 | lançador de programas, estilo Spotlight | |
| 80 | widget de relógio e status na área de trabalho | `widget`, `destaque` |
| 90 | sombras, cantos arredondados e transparência | `efeitos` |
| 95 | tema WhiteSur no Firefox | |
| 97 | tela de login e de bloqueio | `destaque`, `papel_de_parede`, `login_fundo`, `login_desfoque`, `login_usuarios` |
| 98 | bloqueio de tela | `bloqueio` |

As opções e os valores aceitos ficam no `config.py`; o contexto que as receitas
usam é montado no `motor.py`.

## Imagens

As imagens de `docs/imagens` saem de um teste num Debian 13 e são refeitas, não
editadas à mão (o trecho entre `<!-- imagens -->` e `<!-- fim imagens -->` do
README também). As prévias da página (`recursos/web/capturas` e
`recursos/web/exemplos`) são exemplos genéricos; `capturar` troca pelas fotos da
sua própria tela.

As miniaturas dos papéis de parede em `recursos/web/papeis` aparecem antes do
download. Para refazer depois de baixar uma versão nova do repositório:

```sh
for f in ~/.local/share/backgrounds/WhiteSur/*; do
  convert "$f" -resize 320x -strip -quality 78 \
    "recursos/web/papeis/$(basename "${f%.*}").jpg"
done
```
