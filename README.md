# blog app

# front directories
```
apps/front
├── eslint.config.js
├── index.d.ts
├── jest.config.ts
├── next-env.d.ts
├── next.config.js
├── postcss.config.js
├── project.json
├── public
│   └── favicon.ico
├── specs ... テスト
│   └── index.spec.tsx
├── src
│   ├── app
│   │   ├── global.css
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   │   └── posts
│   │       ├── [id]
│   │       │   └── page.tsx
│   │       └── page.tsx
│   ├── components ... 汎用コンポーネント
│   │
│   ├── config ... アプリケーション全体で利用する設定ファイル
│   │
│   ├── features ... 汎用機能ベースモジュール
│   │
│   ├── hooks ... 汎用フック
│   │
│   ├── libs ... アプリケーション全体で利用する設定ファイル
│   │   └── env.ts
│   ├── styles ... 共有スタイル
│   │
│   ├── types ... 共有型
│   │
│   └── utils ... 汎用ユーティリティ関数
│
├── tailwind.config.js
├── tsconfig.json
└── tsconfig.spec.json
```
