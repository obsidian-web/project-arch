```bash
# Архитектура проектов Front-end 
├── client
│   ├── package.json
│   ├── package-lock.json
│   ├── public
│   │   └── `robots, html, favicons`
│   ├── src
│   │   ├── animations
│   │   │   └── animations.ts `анимации`
│   │   ├── App.tsx
│   │   ├── assets
│   │   │   └── `Название страницы (Блока) где лежит изображение`
│   │   │       └── 0.png
│   │   ├── Components
│   │   │   ├── `переиспользуемые компоненты типа Footer, Header и тд`
│   │   ├── custom.d.ts `заголовочный файл (по надобности)`
│   │   ├── hoc
│   │   │   └── `High order Components - Компоненты обертки типа Layout`
│   │   ├── hof
│   │   │   └── `Higher order functions - функциональные обертки`
│   │   ├── hooks
│   │   │   └── `наши хуки`
│   │   ├── index.tsx
│   │   ├── models
│   │   │   └── `Здесь храним все модели, типы и интерфейсы`
│   │   ├── Pages
│   │   │   └── `Название страницы`
│   │   │       └── `Здесь все компоненты на страницы`
│   │   ├── react-app-env.d.ts
│   │   ├── reportWebVitals.ts
│   │   ├── store
│   │   │   ├── ActionCreators
│   │   │   │   └── `наши ActionCreator'ы `
│   │   │   ├── slices
│   │   │   │   └── `наши слайсы `
│   │   │   └── store.ts `стор`
│   │   ├── styles
│   │   │   ├── `название страницы`
│   │   │   │   └── `название блока`
│   │   │   ├── UIKit
│   │   │   │   └── `Название компонента из UIKit`
│   │   │   └── _variables.scss `наши константы`
│   │   └── UIKit
│   │       └── `Название компонента из UIKit`
│   ├── tsconfig.json
```
