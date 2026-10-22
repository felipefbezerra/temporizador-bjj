# Temporizador BJJ

Temporizador de combate, circuito e cronômetro para treinos e lutas de jiu-jitsu. Funciona offline e pode ser instalado no celular como app.

## Funções

- **Combate** com predefinições de BJJ (tempos de luta IBJJF por faixa, rola 6×6).
- **Voz em português:** anuncia cada fase, a posição ou estação, "trinta segundos", "dez segundos" e "última ronda", usando a voz do próprio celular. Dá para trocar por só bipes ou mudo na aba Treinos.
- **Segundo plano:** o timer continua contando fora do app, toca junto com Spotify ou YouTube, volta de onde parou se o celular fechar o app e pode avisar cada troca de fase.
- **Janela flutuante:** o botão Janela abre o timer numa janelinha por cima dos outros apps, onde o navegador permite.
- **Circuito:** monte estações com nome e tempo próprios (sprawl, fuga de quadril, drills), descanso entre estações, número de voltas e descanso entre voltas.
- **Temas de posição:** escolha posições (passagem, costas, meia-guarda ou as suas) e o app mostra uma por ronda, em ordem ou sorteada.
- **Tema claro e escuro:** segue o celular ou fica fixo, na aba Treinos.
- **Treinos:** cada sessão com pelo menos 30 s de trabalho fica salva, com calendário do mês, rondas, tempo de tatame, semanas seguidas e posições treinadas.
- **Sua faixa:** escolha a faixa (adulto ou infantil: cinza, amarela, laranja e verde) e os graus. A cor dela vira o destaque do app e aparece na tela de luta.
- **Cronômetro** com voltas.

## Publicar no GitHub Pages

1. Entre em github.com e clique em **New repository**. Dê um nome (por exemplo `temporizador-bjj`), marque **Public** e crie.
2. Na página do repositório, clique em **uploading an existing file** (ou **Add file > Upload files**).
3. Arraste **todo o conteúdo** desta pasta (`index.html`, `manifest.webmanifest`, `sw.js`, `README.md` e a pasta `icons`). O `index.html` precisa ficar na raiz, não dentro de outra pasta.
4. Clique em **Commit changes**.
5. Vá em **Settings > Pages**. Em **Branch**, escolha `main` e a pasta `/ (root)`, e clique em **Save**.
6. Depois de um ou dois minutos o site fica no ar em `https://SEU-USUARIO.github.io/temporizador-bjj/`.

## Instalar no celular

- **iPhone (Safari):** abra o endereço, toque em Compartilhar e depois em **Adicionar à Tela de Início**.
- **Android (Chrome):** abra o endereço e toque em **Instalar app** (ou menu ⋮ > **Adicionar à tela inicial**).
- **Computador (Chrome ou Edge):** clique no ícone de instalar na barra de endereço.

Abra o app uma vez com internet. Depois disso ele funciona sem conexão.

## Atualizar

Ao trocar qualquer arquivo, abra `sw.js` e mude `bjj-timer-v1` para `bjj-timer-v2` (e assim por diante). Sem isso, quem já instalou continua vendo a versão antiga.

## Observações

- Os tempos salvos ficam no aparelho de cada pessoa.
- No iPhone, o som só toca com o modo silencioso desligado.
- A tela fica acesa durante o treino nos navegadores que permitem isso.
