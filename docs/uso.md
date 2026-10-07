# Usando o d3bian-init-bigsur-xfce

[← voltar ao README](../README.md)

## Rodar

Clone com o nome da pasta igual ao do pacote Python (com `_`) e rode como módulo,
a partir da pasta que contém `d3bian_init_bigsur_xfce`:

```sh
git clone https://git.saberdl.dev.br/d3bian-temas/bigsur-xfce.git d3bian_init_bigsur_xfce
python3 -m d3bian_init_bigsur_xfce          # abre o painel no navegador
python3 -m d3bian_init_bigsur_xfce --help   # subcomandos para o terminal
```

O painel abre em `http://127.0.0.1:8730`.

## Instalação pelo painel

![A instalação pela página, do começo ao resultado](imagens/instalacao.gif)

1. `python3 -m d3bian_init_bigsur_xfce` abre a página no navegador (pede a senha de administrador uma vez, no terminal).
2. Em **Aparência**, escolha as opções e clique em **Instalar tudo**; o progresso de cada etapa aparece na hora.
3. Depois, mudar uma opção e **Aplicar** roda de novo só as etapas afetadas.
4. **Voltar ao que era antes** desfaz tudo; com **Remover também o que foi instalado**, tira também os pacotes.

## Voltar ao que era antes

Em Aparência, **Voltar ao que era antes**, ou `restaurar --sim` na linha de comando.
Cada passo anota no diário (`~/.local/state/<projeto>/diario.jsonl`) o que mudou,
e o desfazer percorre o diário de trás para frente: arquivo criado sai, arquivo
que já existia volta da cópia de segurança, bloco sai do arquivo, xfconf,
gsettings e dconf voltam ao valor de antes, extensões voltam à lista de antes.
Scripts anotam antes de mexer com `d3_antes`, `d3_xfconf`, `d3_gsettings`,
`d3_dconf`, `d3_criado` e `d3_pacotes`; o que nem isso cobre (a barra inteira do
XFCE, a tela de login do GDM) fica em `[[desfazer]]` na própria receita.

Com **Remover também o que foi instalado** (`restaurar --sim --apagar`), sai
também o que o projeto instalou pelo apt e as pastas do projeto; a página mostra
a lista antes. Instalações anteriores ao diário: só as cópias de segurança voltam.
Detalhes no `LEIAME.md` do [modelo](https://git.saberdl.dev.br/d3bian-temas/modelo).
