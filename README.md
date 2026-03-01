
### Criando projeto Next Typescript
 ```
 npx create-next-app@latest next-game
 ```

### Rodar o projeto
 ```
 npm run dev
 ```


### Preview

> #### Level 1
<img src="./preview/level-1.png" alt="" /> <br />

> #### Level 2
<img src="./preview/level-2.png" alt="" /> <br />

> #### Level 3
<img src="./preview/level-3.png" alt="" /> <br />

### Estrutura inicial
meu-jogo/
├─ public/
│  ├─ icons/
│  ├─ sounds/
│  └─ images/
│
├─ src/
│  ├─ app/
│  │  ├─ layout.tsx
│  │  ├─ globals.css
│  │  ├─ page.tsx                # Tela inicial com as 3 opções
│  │  │
│  │  ├─ play/
│  │  │  └─ page.tsx             # Jogar como anônimo
│  │  │
│  │  ├─ login/
│  │  │  └─ page.tsx             # Tela de login
│  │  │
│  │  ├─ cadastro/
│  │  │  └─ page.tsx             # Tela de cadastro
│  │  │
│  │  ├─ hack/
│  │  │  └─ page.tsx             # Área/evento do hacking com premiação
│  │  │
│  │  └─ ranking/
│  │     └─ page.tsx             # Ranking / pontuação
│  │
│  ├─ components/
│  │  ├─ home/
│  │  │  ├─ StartMenu.tsx
│  │  │  ├─ StartCard.tsx
│  │  │  └─ HeroBanner.tsx
│  │  │
│  │  ├─ auth/
│  │  │  ├─ LoginForm.tsx
│  │  │  └─ RegisterForm.tsx
│  │  │
│  │  ├─ game/
│  │  │  ├─ GameCanvas.tsx
│  │  │  ├─ MobileControls.tsx
│  │  │  ├─ Hud.tsx
│  │  │  └─ Overlay.tsx
│  │  │
│  │  └─ ui/
│  │     ├─ Button.tsx
│  │     ├─ Card.tsx
│  │     └─ Modal.tsx
│  │
│  ├─ modules/
│  │  └─ pacman/
│  │     ├─ core/
│  │     │  ├─ GameEngine.ts
│  │     │  ├─ GameLoop.ts
│  │     │  ├─ collision.ts
│  │     │  ├─ movement.ts
│  │     │  └─ level-loader.ts
│  │     │
│  │     ├─ entities/
│  │     │  ├─ Player.ts
│  │     │  ├─ Ghost.ts
│  │     │  └─ Pellet.ts
│  │     │
│  │     ├─ data/
│  │     │  └─ levels.ts
│  │     │
│  │     ├─ render/
│  │     │  ├─ draw-board.ts
│  │     │  ├─ draw-player.ts
│  │     │  ├─ draw-ghost.ts
│  │     │  └─ draw-ui.ts
│  │     │
│  │     ├─ input/
│  │     │  ├─ keyboard.ts
│  │     │  ├─ touch.ts
│  │     │  └─ swipe.ts
│  │     │
│  │     ├─ hooks/
│  │     │  ├─ useGameEngine.ts
│  │     │  ├─ useResponsiveCanvas.ts
│  │     │  └─ useGameControls.ts
│  │     │
│  │     ├─ types/
│  │     │  ├─ game.types.ts
│  │     │  ├─ entity.types.ts
│  │     │  └─ input.types.ts
│  │     │
│  │     └─ constants/
│  │        └─ index.ts
│  │
│  ├─ services/
│  │  ├─ auth.service.ts         # Login/cadastro
│  │  ├─ ranking.service.ts      # Pontuação
│  │  └─ hack.service.ts         # Regras/inscrição do evento
│  │
│  ├─ store/
│  │  ├─ authStore.ts
│  │  └─ gameStore.ts
│  │
│  ├─ lib/
│  │  ├─ utils.ts
│  │  └─ validators.ts
│  │
│  └─ styles/
│     └─ game.css
│
├─ package.json
├─ tsconfig.json
├─ next.config.ts
└─ tailwind.config.ts

### Salvar no git
> * adicionar na area de stage
 ```
 git add .
 ```

> * adicionar de commit rotuvo do save
```
git commit -m updated
```
 
> * adicionar guarda na nuvem do git
```
git push
```
 