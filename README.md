# Jogo da Memória: 7 Dias da Criação

Jogo da memória para navegador, criado com HTML, CSS e JavaScript. As sete ilustrações das cartas e o logo do Colégio El Shaday estão na pasta `imagens/`. O logo ocupa o espaço após as 14 cartas, na terceira linha e quinta coluna em telas com cinco colunas. O jogo não usa bibliotecas externas e pode ser aberto sem conexão com a internet, desde que `index.html` e `imagens/` permaneçam juntos.

## Como jogar

Abra `index.html` no navegador. Vire duas cartas por vez e encontre os sete pares. O painel mostra o número de jogadas e o tempo da partida. O botão **Reiniciar jogo** começa uma nova partida.

## Publicar com GitHub Pages

1. Crie um repositório público no GitHub, por exemplo, `jogo-da-memoria`.
2. Coloque `index.html` e a pasta `imagens/` na raiz desse repositório. Você também pode colocar este `README.md`.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Selecione a branch `main`, a pasta `/(root)` e clique em **Save**.
6. Depois que a publicação terminar, o jogo estará em `https://SEU-USUARIO.github.io/jogo-da-memoria/`.

Se der outro nome ao repositório, substitua `jogo-da-memoria` pelo nome escolhido no endereço.

## Acessibilidade

As cartas são botões e podem ser selecionadas com Tab e Enter ou Espaço. O jogo informa os pares encontrados aos leitores de tela e respeita a preferência de reduzir animações.
