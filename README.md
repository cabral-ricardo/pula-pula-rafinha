# Pula Pula Rafinha

Jogo de corrida infinita feito para crianças, em que a Rafinha corre por um campo colorido, pula obstáculos e pega estrelas. Tudo roda num único arquivo `index.html`, sem dependências nem etapa de build.

## Como jogar

| Ação | Teclado | Toque |
| --- | --- | --- |
| Pular | `Espaço`, `↑` ou `W` | Tocar na tela |
| Pular mais alto | Segurar a tecla de pulo | Segurar o toque |
| Abaixar / cair mais rápido | `↓` ou `S` | Botão **⬇ Abaixar** |

- Pule cogumelos, flores, arbustos e presentes que aparecem no chão.
- A partir de 120 pontos surgem passarinhos voando: pule ou abaixe para desviar.
- Cada estrela ⭐ coletada vale 25 pontos.
- A velocidade aumenta com o tempo, e a cada 200 pontos você passa de nível.
- O recorde fica salvo no navegador.

## Foto da personagem

O rosto da Rafinha é uma foto. Por padrão o jogo usa `foto.jpg`, que fica na raiz do projeto. Para trocar, clique em **📷 Escolher foto** e escolha qualquer imagem: ela é recortada em quadrado e salva no navegador.

## Rodando localmente

Abra o `index.html` no navegador ou sirva a pasta com um servidor estático, por exemplo:

```bash
npx serve .
```

## Arquivos

- `index.html`: o jogo completo (HTML, CSS e JavaScript com Canvas e Web Audio)
- `foto.jpg`: foto padrão da personagem
