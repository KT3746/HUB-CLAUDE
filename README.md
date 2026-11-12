# HUB-CLAUDE

Página única que reúne os jogos do [KT3746](https://github.com/KT3746) feitos
em sessões com o Claude Code — cada um no seu próprio repositório, sem build
e sem dependências. Abra `index.html` num navegador ou publique este
repositório com GitHub Pages.

## Jogos

| Jogo | Descrição | Repositório | Jogar |
| --- | --- | --- | --- |
| 🏰 Muralha | Tower defense medieval | [Claude-Tower-Defense](https://github.com/KT3746/Claude-Tower-Defense) | [kt3746.github.io/Claude-Tower-Defense](https://kt3746.github.io/Claude-Tower-Defense/) |
| 🏹 Arqueiro | Arco e flecha, mire e acerte o X | [Claude-Arqueiro](https://github.com/KT3746/Claude-Arqueiro) | [kt3746.github.io/Claude-Arqueiro](https://kt3746.github.io/Claude-Arqueiro/) |
| 🏟️ Arqueiro — Primeira Pessoa | Refeito em Godot 4.3, mira em 3D | [Claude-Arqueiro-2](https://github.com/KT3746/Claude-Arqueiro-2) | requer Godot instalado, sem versão web |
| 🪱 Minhocas | Artilharia por turnos estilo Worms | [Claude-Worms](https://github.com/KT3746/Claude-Worms) | [kt3746.github.io/Claude-Worms](https://kt3746.github.io/Claude-Worms/) |
| 💣 Campo Minado | O clássico, sem dependências | [Claude-Campo-Minado](https://github.com/KT3746/Claude-Campo-Minado) | [kt3746.github.io/Claude-Campo-Minado](https://kt3746.github.io/Claude-Campo-Minado/) |
| 🤠 Poeira Vermelha | Faroeste 3D estilo Red Dead | [Claude---RedDead](https://github.com/KT3746/Claude---RedDead) | [kt3746.github.io/Claude---RedDead/3d](https://kt3746.github.io/Claude---RedDead/3d/) |
| 🪂 Fenda Boreal | Planador 3D num fiorde | [Claude---para-Testes](https://github.com/KT3746/Claude---para-Testes) | [kt3746.github.io/Claude---para-Testes](https://kt3746.github.io/Claude---para-Testes/) |

Critério de inclusão: repositórios do KT3746 cujos commits carregam o rodapé
`Co-Authored-By: Claude`, ou seja, jogos construídos com o Claude Code — os
repositórios com prefixo `Grok-`/`grokbot-` e `Chatgpt-` (feitos com outra IA),
o rascunho privado duplicado `Claude-Campo-Minaso` e `Claude-Tower-Defense-2`
(repo vazio, só o "Initial commit" automático do GitHub) ficaram de fora.

## Como rodar localmente

```bash
python3 -m http.server 8000   # depois: http://localhost:8000
```
