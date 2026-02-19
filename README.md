# Pizzaria das Frações 🍕

Jogo educativo em **PT-BR** para praticar frações com gameplay visual, rápido e divertido.

## Novidades desta versão
- ✅ **Modo A · Descobrir**: veja a pizza e responda a fração (sem texto entregando a resposta).
- 🧩 **Modo B · Construção**: o jogo mostra uma fração (ex.: `3/4`) e você monta na pizza selecionando fatias.
- 🔁 **Modo C · Equivalentes**: escolha uma fração equivalente à pizza exibida.
- 📱 **Mobile sem scroll durante a partida**: tela compacta, sem rolagem e com painel secundário em modo recolhível.
- 🎁 **Progressão com XP e cosméticos**: acertos geram XP e desbloqueiam temas visuais da pizza.

## Como jogar
1. Abra `index.html` no navegador (ou sirva localmente com `npx serve .`).
2. Escolha um modo: **A, B ou C**.
3. Clique em **Começar partida**.
4. Complete 8 rodadas antes do tempo acabar.

## Regras rápidas
- 60 segundos totais (tempo só corre durante cada rodada ativa).
- Acerto: aumenta combo, pontuação e XP.
- Erro: zera combo e aplica penalidade leve.
- Novos cosméticos são desbloqueados automaticamente por XP.

## Acessibilidade e UX
- Botões grandes para toque.
- Feedback textual imediato (acerto/erro + recompensa).
- Painel compacto no mobile para manter foco na área de jogo.

## Stack
- HTML + CSS + JavaScript (vanilla, sem dependências)

## Estrutura
- `index.html`: jogo completo (UI + lógica)
