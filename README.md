# Temporizador BJJ

Temporizador de rondas, tabata e cronômetro para treinos e lutas de jiu-jitsu. Funciona offline e pode ser instalado no celular como app.

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
