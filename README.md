# ディレクトリ構成

```bash

├── public // 静的ファイル
│   ├── next.svg
│   └── vercel.svg
├── app // ルーティング
│   ├── about
│   │   └── page.tsx
│   ├── blog
│   │   ├── [blogid]
│   │   │   └── page.tsx
│   │   └── page.tsx
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components
│   ├── elements // ページ間で使い回すコンポーネント（ボタンなど）
│   │   ├── button
│   │   │   └── Button.tsx
│   │   └── input
│   │       └── Input.tsx
│   └── layouts // 画面が切り替わっての常に表示していたいもの
│       ├── footer
│       │   └── Footer.tsx
│       └── header
│           └── Header.tsx
├── features // 一つのページにしかないコンポーネントを管理する
│   ├── blog // 特定の機能のコンポーネント
│   │   ├── api
│   │   │   └── getBlog.ts
│   │   ├── components
│   │   │   ├── BlogImage
│   │   │   │   ├── BlogImage.moduke.css
│   │   │   │   └── BlogImage.tsx
│   │   │   └── BlogList
│   │   │       ├── BlogList.module.css
│   │   │       └── BlogList.tsx
│   │   ├── constants
│   │   │   └── index.ts
│   │   ├── hooks
│   │   │   └── useBlog.ts
│   │   ├── store
│   │   │   └── index.ts
│   │   └── types
│   │       └── index.ts
│   └── user // 特定の機能のコンポーネント
│       ├── api
│       ├── components
│       └── types
└── tree.txt
```
