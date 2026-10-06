<div align="center">

<img src="docs/logo.svg" alt="d3bian-init bigsur-xfce" width="420">

**Cara de macOS Big Sur no Xfce do Debian: tema, ícones, barra no topo, dock e tela de login.**

[![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)](docs/desenvolvimento.md)
[![Sem dependências](https://img.shields.io/badge/depend%C3%AAncias-nenhuma-brightgreen)](docs/desenvolvimento.md)
[![Debian 13](https://img.shields.io/badge/Debian-13-A81D33?logo=debian&logoColor=white)](docs/uso.md)
[![Xfce](https://img.shields.io/badge/desktop-Xfce-2284F2?logo=xfce&logoColor=white)](docs/uso.md)
[![Licença MIT](https://img.shields.io/badge/licen%C3%A7a-MIT-blue)](LICENSE)

</div>

> Um painel local, aberto no navegador, para preparar e ajustar um Debian com
> Xfce, com visual inspirado no macOS Big Sur: escolha vendo, aplique, e volte
> ao que era antes quando quiser. Só Python da biblioteca padrão — nada de pip.

```sh
git clone https://git.saberdl.dev.br/d3bian/bigsur-xfce.git d3bian_init_bigsur_xfce
python3 -m d3bian_init_bigsur_xfce        # pede a senha uma vez e abre o painel
```

<div align="center">
  <img src="docs/imagens/resultado-instalado.jpg" alt="Logo depois de instalar, com as opções padrão" width="820">
  <br><sub>Logo depois de instalar, com as opções padrão.</sub>
</div>

---

## O que ele faz

- **Tema WhiteSur** claro ou escuro nas janelas (GTK e Qt/Kvantum), com cor de destaque à escolha
- **Ícones, cursores e papéis de parede** WhiteSur, com galeria para escolher o papel
- **Barra no topo** estilo macOS, com logo no canto e **menu global** do programa ativo
- **Dock** inferior com zoom (Plank Reloaded) e **lançador** estilo Spotlight (rofi)
- **Widget** na área de trabalho: relógio e barras, ou anéis
- **Janelas**: sombras e cantos arredondados, bordas mais largas, encaixe e layouts no Super+Z
- **Tela de login e de bloqueio** combinando, com fundo desfocado; tema também no Firefox
- **Programas úteis** do repositório oficial, marcados e instalados de uma vez
- **Voltar ao que era antes** com um clique, inclusive removendo o que foi instalado

<!-- imagens: gerado a partir do teste num Debian 13; refazer, nao editar a mao -->
## Telas

| Com outras opções da página | Mais uma combinação de opções |
|---|---|
| ![Com outras opções da página](docs/imagens/resultado-opcao.jpg) | ![Mais uma combinação de opções](docs/imagens/resultado-opcao2.jpg) |

| Início | Opções | Programas úteis |
|---|---|---|
| ![Início](docs/imagens/painel-inicio.jpg) | ![Opções](docs/imagens/painel-opcoes.jpg) | ![Programas úteis](docs/imagens/painel-programas.jpg) |

<details>
<summary><b>A instalação pela página, do começo ao resultado</b></summary>

![A instalação pela página, do começo ao resultado](docs/imagens/instalacao.gif)

</details>
<!-- fim imagens -->

## Documentação

| | |
|---|---|
| 🚀 [Usando](docs/uso.md) | rodar, instalação pelo painel, voltar ao que era antes |
| 🛠️ [Desenvolvimento](docs/desenvolvimento.md) | receitas, como as imagens e as miniaturas são geradas |
| ⚙️ [Núcleo](https://git.saberdl.dev.br/d3bian/modelo) | o motor, o servidor e as telas comuns a toda a família |

## Família d3bian-init

Todos com o mesmo motor e o mesmo jeito de usar: um painel local, só Python da biblioteca padrão, e "voltar ao que era antes".

| | Projeto | O que faz |
|---|---|---|
| 💻 | [terminal](https://git.saberdl.dev.br/d3bian/terminal) · [terminal-kde](https://git.saberdl.dev.br/d3bian/terminal-kde) | Fish, Oh My Posh, Nerd Font e cores (xfce4-terminal/GNOME Terminal ou Konsole) |
| 💻 | [zsh](https://git.saberdl.dev.br/d3bian/zsh) · [zsh-kde](https://git.saberdl.dev.br/d3bian/zsh-kde) | Zsh com sugestões e realce, Oh My Posh, Nerd Font e cores |
| 💻 | [bash](https://git.saberdl.dev.br/d3bian/bash) · [bash-kde](https://git.saberdl.dev.br/d3bian/bash-kde) | O bash de sempre, com sugestões e realce, Oh My Posh e Nerd Font |
| 🎨 | [bigsur-kde](https://git.saberdl.dev.br/d3bian/bigsur-kde) · [mactahoe-kde](https://git.saberdl.dev.br/d3bian/mactahoe-kde) | Cara de macOS (Big Sur ou Tahoe) no KDE Plasma 6 |
| 🎨 | [fluent-kde](https://git.saberdl.dev.br/d3bian/fluent-kde) · [chromeos-kde](https://git.saberdl.dev.br/d3bian/chromeos-kde) | Cara de Windows 11 ou de ChromeOS no KDE Plasma 6 |
| 🎨 | [catppuccin-kde](https://git.saberdl.dev.br/d3bian/catppuccin-kde) · [graphite-kde](https://git.saberdl.dev.br/d3bian/graphite-kde) · [layan-kde](https://git.saberdl.dev.br/d3bian/layan-kde) · [orchis-kde](https://git.saberdl.dev.br/d3bian/orchis-kde) | Temas Catppuccin, Graphite, Layan e Orchis no KDE Plasma 6 |
| 🪟 | **bigsur-xfce** · [bigsur-minimalista-xfce](https://git.saberdl.dev.br/d3bian/bigsur-minimalista-xfce) | Cara de macOS Big Sur no Xfce, completo ou minimalista |
| 🪟 | [minimal-xfce](https://git.saberdl.dev.br/d3bian/minimal-xfce) · [paleta-xfce](https://git.saberdl.dev.br/d3bian/paleta-xfce) | Xfce enxuto, ou numa paleta só (Nord, Gruvbox, Everforest) |
| 🍎 | [tahoe-gnome](https://git.saberdl.dev.br/d3bian/tahoe-gnome) | Cara de macOS Tahoe no GNOME 48 |
| 🧩 | [modelo](https://git.saberdl.dev.br/d3bian/modelo) | O modelo de onde todos saem: crie o seu próprio d3bian-init |

## Créditos

O d3bian-init-bigsur-xfce não cria temas: baixa, instala e ajusta trabalho de outras
pessoas. Todo o mérito visual é delas.

| O quê | Projeto | Autor | Licença |
|---|---|---|---|
| Tema GTK | [WhiteSur-gtk-theme](https://github.com/vinceliuice/WhiteSur-gtk-theme) | vinceliuice | MIT |
| Ícones | [WhiteSur-icon-theme](https://github.com/vinceliuice/WhiteSur-icon-theme) | vinceliuice | GPL-3.0 |
| Cursores | [WhiteSur-cursors](https://github.com/vinceliuice/WhiteSur-cursors) | vinceliuice | GPL-3.0 |
| Papéis de parede | [WhiteSur-wallpapers](https://github.com/vinceliuice/WhiteSur-wallpapers) | vinceliuice | MIT |
| Tema Qt (Kvantum) | [WhiteSur-kde](https://github.com/vinceliuice/WhiteSur-kde) | vinceliuice | GPL-3.0 |
| Tema do Firefox | [WhiteSur-firefox-theme](https://github.com/vinceliuice/WhiteSur-firefox-theme) | vinceliuice | MIT |
| Temas do lançador | [rofi](https://github.com/adi1090x/rofi) | adi1090x | GPL-3.0 |
| Dock | [plank-reloaded](https://github.com/zquestz/plank-reloaded) | zquestz | GPL-3.0 |
| Fonte Inter | pacote `fonts-inter` do Debian | Rasmus Andersson | OFL-1.1 |
| Widget de anéis | [MX-CoreBlue](https://github.com/MX-Linux/mx-conky-data/tree/master/MX-CoreBlue), a partir do Clock Rings | MX Linux; londonali1010, despot77 e Altin | ver o repositório |
| Ideia do widget de anéis | [Xfce Big Sur setup](https://www.opencode.net/lsteam/xfce-big-sur-setup-file) | lsteam | |

As miniaturas em `recursos/web/papeis` e as prévias da página mostram os papéis
de parede do WhiteSur-wallpapers.

XFCE, LightDM, light-locker, picom, Conky, Kvantum, o menu global e os demais
pacotes vêm do repositório oficial do Debian.

A opção de fonte SF Pro baixa um espelho público
([San-Francisco-Pro-Fonts](https://github.com/sahibjotsaggu/San-Francisco-Pro-Fonts));
a fonte pertence à Apple e tem licença própria.

## Aviso

Projeto independente, sem relação com a Apple, o Debian ou a NBCUniversal.
macOS, Big Sur e a logo da maçã são marcas da Apple Inc. Debian é marca da
Software in the Public Interest, Inc. Mr. Robot e fsociety são marcas da
NBCUniversal.

---

<div align="center">
<sub>Código sob a <a href="LICENSE">licença MIT</a> · feito para o Debian 13</sub>
</div>
