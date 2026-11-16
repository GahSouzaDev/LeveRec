# LeveRec

**Gravador de tela ultraleve para gameplays, em um único arquivo HTML.**

Baixe o `gravador-de-tela.html`, abra no Chrome ou Edge e grave. Sem instalar nada, sem internet, sem conta e sem servidor. Tudo roda no seu navegador e nenhum vídeo sai do seu computador.

O LeveRec nasceu para gravar jogos sem travar: não tem prévia ao vivo, não desenha nada na tela durante a gravação e usa o codificador do próprio navegador (H.264, geralmente acelerado pela placa de vídeo).

## Recursos

- **Janela flutuante** que fica sempre por cima do jogo, com cronômetro, Gravar, Pausar e Parar. Ela se recolhe sozinha durante a gravação para não atrapalhar.
- **Escolha antes de gravar:** janela, tela inteira ou uma **região** marcada com o mouse.
- **Contagem regressiva** de 3, 5 ou 10 segundos, com bipe, dentro da própria janelinha.
- **Qualidades prontas:** Ultra leve (720p 30 fps), Otimizado (720p 60 fps), Leve (1080p 30 fps), Equilibrado (1080p 60 fps) e Máximo (resolução original, 60 fps).
- **Saída em MP4** (WebM como alternativa), com player para rever e botão de baixar.
- **Cortar vídeo:** marque início e fim, pré-veja e gere só o trecho que quer baixar.
- **Áudio** do jogo/sistema e do microfone, juntos ou separados, e opção de mostrar ou esconder o cursor.
- **Um arquivo só:** logo, ícones e favicon já vêm embutidos, então é fácil de compartilhar.

## Como usar

1. Baixe o `gravador-de-tela.html` e abra no **Chrome** ou **Edge**.
2. Em **O que gravar**, escolha Janela, Tela inteira ou Região e clique em **Escolher o que gravar**.
3. Clique em **Abrir janela flutuante**.
4. Vá para o jogo e clique em **Gravar** na janelinha.
5. Ao parar, o vídeo abre num player. Use **Cortar vídeo** se quiser e depois **Baixar**.

### Dicas

- Em **Janela**, a janelinha nunca aparece no vídeo, mas o Chrome não captura o áudio de janelas.
- Em **Tela inteira**, o áudio do jogo funciona e marque "Compartilhar áudio" no seletor do navegador. A janelinha fecha ao começar a gravar, e você para pelo botão "Parar compartilhamento" do Chrome.
- Em **Região**, deixe a janelinha fora da área marcada.
- Jogos em tela cheia exclusiva escondem a janelinha: use o modo janela sem bordas.
- As gravações ficam na memória do navegador. **Baixe antes de fechar a aba.**

## Requisitos

| Recurso | Navegador |
| --- | --- |
| Gravação de tela | Chrome, Edge ou outro navegador baseado em Chromium |
| Janela flutuante | Chrome ou Edge 116+ |
| MP4 direto | Chrome ou Edge com suporte a MP4 no gravador (em outros casos o app grava WebM e avisa) |
| Gravar região | Chrome ou Edge atualizado |

## Limitações

- O **corte** regrava o trecho em tempo real: um trecho de 30 s leva cerca de 30 s, e a aba precisa ficar aberta e visível. Há uma pequena perda de qualidade por causa da nova codificação.
- Os vídeos ficam na memória do navegador até você baixá-los, então gravações muito longas e pesadas podem consumir bastante RAM.
- Atalhos globais de teclado não existem em páginas web, por isso o controle é feito pela janelinha.

## Estrutura do projeto

```
gravador-de-tela.html   # o app inteiro (HTML, CSS, JS, logo e ícones embutidos)
README.md
```

## Privacidade

O LeveRec não envia nada para a internet. A captura, a gravação, o corte e o download acontecem localmente no navegador. As únicas configurações guardadas são as suas escolhas de qualidade, formato e áudio, no armazenamento local do navegador.

## Licença

Defina a licença do seu repositório aqui (por exemplo, MIT).
