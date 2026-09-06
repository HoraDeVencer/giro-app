# Como publicar o GIRO no GitHub (grátis)

Isso deixa o app com um link fixo, funcionando fora do Claude, com os dados
salvando de verdade no seu celular. A leitura automática de foto não vem
nessa versão (só funciona dentro do Claude).

## Passo 1 — Criar a conta e o repositório

1. Crie uma conta em https://github.com (se ainda não tiver)
2. Clique no `+` no canto superior direito → **New repository**
3. Dê um nome, por exemplo `giro-app`
4. Marque como **Public**
5. Clique em **Create repository**

## Passo 2 — Subir os arquivos

1. Na página do repositório recém-criado, clique em **uploading an existing file**
   (ou "Add file" → "Upload files")
2. Arraste estes 5 arquivos desta pasta:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
   - `icon-512-maskable.png`
3. Clique em **Commit changes**

## Passo 3 — Ativar o GitHub Pages

1. No repositório, vá em **Settings** (aba no topo)
2. No menu da esquerda, clique em **Pages**
3. Em "Branch", escolha `main` e a pasta `/ (root)`
4. Clique em **Save**
5. Espere 1–2 minutos e recarregue a página — vai aparecer um link tipo:
   `https://SEU-USUARIO.github.io/giro-app/`

## Passo 4 — Instalar no celular

1. Abra esse link no **Chrome do Android**
2. Toque nos três pontinhos (⋮) → **Adicionar à tela inicial** (ou "Instalar app")
3. Confirme

Pronto — vai aparecer um ícone do GIRO na tela do seu celular, abre em tela
cheia como um app de verdade, e os dados ficam salvos ali permanentemente
(mesmo fechando e abrindo de novo).

## Se quiser um arquivo .apk de verdade

1. Vá em https://www.pwabuilder.com
2. Cole o link do seu GitHub Pages (`https://SEU-USUARIO.github.io/giro-app/`)
3. Clique em **Start**
4. Escolha a opção **Android** e siga as instruções pra gerar o `.apk`

## Atualizando o app depois

Se no futuro você quiser mudar alguma coisa no código, é só editar o
`index.html` direto no site do GitHub (botão de lápis ✏️ no arquivo) e
salvar — o link atualiza sozinho em 1–2 minutos.
