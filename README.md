# Meu Treino 💪

App de treino em **um único HTML** — mobilidade, vídeos, cardio (esteira, escada e corrida de rua com GPS), resumo pra print e compartilhamento. Funciona **offline** e salva tudo no celular.

- **Abrir no celular:** https://marquezbertin.github.io/meu-treino/
- **Arquivo principal:** `index.html` (cópia idêntica em `Treino.html`)

## Como usar no celular

1. Abra o link no Chrome (Android) ou Safari (iPhone).
2. Toque em **⬇ App** → *Adicionar à tela inicial* (vira ícone laranja, abre em tela cheia).
3. Se o app parecer desatualizado: atualize a página 2x ou limpe *imagens e arquivos em cache* do site.

## Funcionalidades

### 🏃 Mobilidade (12 exercícios)
- Fotos recortadas da arte original, explicação passo a passo e prescrição (ex: `2x 30s cada lado`).
- Check ✅ por exercício, com barra de progresso.

### 📹 Vídeos (17 fixos + os seus)
- 17 Reels dos professores, com botão que abre no Instagram.
- **➕ Adicionar vídeo:** cole qualquer link do Instagram (normal ou curtinho `instagr.am`) — o app padroniza pro mesmo formato dos fixos, então abre e volta igual. Lista permanente (não apaga no zerar), com botão Remover.

### ⏱️ Cardio: esteira, escada e corrida de rua
- Cronômetro + check independentes pra cada um.
- **Tempo por relógio:** continua certo mesmo com a **tela bloqueada** ou fechando e abrindo o app (retoma sozinho).
- **Wake lock:** tenta manter a tela ligada enquanto algum cronômetro roda.
- **Auto-check:** ao pausar após 1 min ou mais (ou qualquer distância com GPS), o ✅ marca sozinho.
- **📍 GPS na corrida:** distância (km), ritmo atual e ritmo médio. Requer HTTPS + permissão. Com a tela apagada o tempo continua, mas o GPS pausa os pontos até acender.

### ➕ Extras com foto
- Adicione exercício/aparelho com nome e foto da câmera ou galeria (a foto é comprimida pra não estourar o armazenamento).

### 🏁 Encerrar treino + resumo
- Só entra no resumo o que foi marcado (não precisa fazer tudo).
- Resumo estilo Strava pra corrida (km gigante + ritmo médio) e tela pronta pra **print**.
- **Compartilhar em imagem:** gera PNG no tamanho certo — Feed 4:5 (1080x1350), Story 9:16 (1080x1920) ou Quadrado — pra enviar ao WhatsApp/Instagram pelo menu do celular.

### 📜 Histórico + 🏆 metas semanais
- Cada treino encerrado é guardado (data, feitos, tempo, cardio, km) — últimos 60.
- Metas editáveis de treinos/semana e km de corrida (semana = segunda a domingo), com barras de progresso.

### 🎨 Extras
- **Tema claro/escuro** (☀️/🌙) com preferência salva.
- **Nome + data** salvos a cada tecla, com indicador `✓ salvo`.
- **Zerar dia** (checks e tempos) e **Novo treino** (mantém nome, vídeo adicionados e histórico).

## Privacidade e dados

Tudo fica em `localStorage` **no seu aparelho** — nada sai do celular. Se trocar de aparelho, os dados não vão junto (vale pedir exportar/importar se precisar).

## Arquivos

| Arquivo | O quê |
|---|---|
| `index.html` / `Treino.html` | O app (idênticos) |
| `manifest.webmanifest` | Instalação como app (PWA) |
| `sw.js` | Cache offline |
| `icon-192.png` / `icon-512.png` | Ícones |

Publicado com **GitHub Pages** a partir deste repositório (`main` → `/`).
