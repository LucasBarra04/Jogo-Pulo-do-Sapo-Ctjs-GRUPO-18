# Pulo do Sapo

Jogo de plataforma 2D feito com ct.js 5.3.1. O Sapo Ninja precisa recuperar as moedas de ouro da Lagoa Esmeralda, roubadas pelo bando do Rei Porco, atravessando cinco fases.

Jogue online: [link]

## Como jogar

Chegue à saída de cada fase e colete moedas. Você começa com 3 vidas. Espinhos, água e porcos (tocados pelo lado) tiram uma vida; pule em cima dos porcos para derrotá-los. Checkpoints guardam o progresso e corações devolvem vidas.

| Ação | Teclado | Controle Xbox |
|---|---|---|
| Andar | A / D ou setas | Analógico esquerdo ou direcional |
| Pular | Espaço | Botão A |
| Pausar | Esc | Start |

## Como executar

1. Instale o ct.js 5.3.1 (https://ctjs.rocks/).
2. Clone o repositório: `git clone [url]`
3. No ct.js, abra o arquivo `JogoTeste2.ict` e clique em Iniciar.

Windows: baixe `Pulo_do_Sapo_Windows.zip` em Releases, extraia e execute `Pulo do Sapo.exe`. Se a tela ficar branca, execute como administrador o script `Run as admin to fix white screen.ps1`, da mesma pasta.

Build web: precisa de um servidor web (abrir o index.html com duplo clique não funciona). Use o link online acima ou, em Releases, baixe `Pulo_do_Sapo.zip`, extraia e rode dentro da pasta `python -m http.server 8000` (no Windows, `py -m http.server 8000`). Acesse http://localhost:8000.

## Estrutura

```
JogoTeste2.ict    projeto do ct.js
JogoTeste2/       texturas e músicas
docs/             planejamento das fases e capturas de tela
```

## Equipe

[Nome], [Nome], [Nome]

## Créditos

- Tiles: Simplified Platformer Pack, Kenney (CC0).
- Sapo, porco e moeda: [autor e licença].
- Logo, fundos e imagem da história: geradas por IA [ferramenta].
- Músicas (Menu_music, Fase_music, Fim_music): geradas por IA (Gemini, Google).
- Base do jogo: tutorial Making Games: Platformer, da documentação do ct.js.

## Licença

[licença]
