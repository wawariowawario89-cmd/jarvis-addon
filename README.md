# J.A.R.V.I.S. — Interface Web

Interface experimental em português para o projeto de armaduras de Minecraft Bedrock.

## Conteúdo

- `index.html` — estrutura da página.
- `style.css` — visual futurista responsivo.
- `script.js` — seleção de armadura, modos, registro de eventos, síntese e reconhecimento de voz quando suportados pelo navegador.
- `.nojekyll` — evita processamento desnecessário do Jekyll no GitHub Pages.

## Publicar no GitHub Pages

1. Extraia o ZIP no seu dispositivo ou computador.
2. Abra o repositório `jarvis-site` no GitHub.
3. Envie os arquivos desta pasta para a raiz do repositório. O `index.html` precisa ficar na raiz, não dentro de uma segunda pasta.
4. No GitHub, abra **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**.
6. Selecione a branch `main` e a pasta `/ (root)`, depois salve.
7. Aguarde a publicação. O endereço costuma ser `https://SEU-USUARIO.github.io/jarvis-site/`.

## Como usar

Abra o site em um navegador compatível. Permita o uso do microfone para testar reconhecimento de voz. Também é possível digitar os comandos na caixa de texto.

Comandos de demonstração:
- `Voar ativado`
- `Voo desativado`
- `Ativar repulsores`
- `Abrir máscara`
- `Fechar máscara`

## Limitação importante

Esta versão é somente a interface web inicial. Ela reconhece comandos e mostra respostas demonstrativas, mas **ainda não envia comandos ao Minecraft**. Para executar ações no mundo Bedrock, será necessário instalar e configurar uma ponte compatível (por exemplo, a solução Bedrock WebSocket escolhida para o projeto), além do addon correspondente. Não insira senhas ou tokens privados no código público do site.

O reconhecimento de voz depende do navegador, do sistema operacional e de permissões; alguns navegadores exigem HTTPS. A síntese de voz usa as vozes disponíveis no dispositivo.

## Licença

Este pacote não inclui modelos, texturas ou recursos de terceiros. Os arquivos da interface podem ser modificados para o projeto.
