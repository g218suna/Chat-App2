This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

# Chat-App

## 環境

- Ubuntu 20.04
- Node Version Manager (nvm) v0.39.3
- Node.js v16.19.1
- Node Package Manager (npm) v8.19.3
- yarn v1.22.19

## Ubuntu

~# `apt update`

## Node.js

### Node.js バージョン管理 nvm インストール

~# `git clone https://github.com/nvm-sh/nvm.git ~/.nvm`

~# `source ~/.nvm/nvm.sh`

~# `touch /etc/profile.d/nvm.sh`

/etc/profile.d/nvm.sh
```
source ~/.nvm/nvm.sh

nvm use 0.39.3 > /dev/null
```
~# `nvm help`

~# `nvm ls-remote`

~# `nvm install v16.19.1`

## yarn

### yarn インストール

リポジトリのGPGキーをインポート

~# `curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -`

arnAPTリポジトリをシステムのソフトウェアリポジトリリストに追加

~# `echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list`

~# `apt install yarn`

## Next.js

~# `yarn create next-app --typescript`

~# `cd chat-app`

~/chat-app# `yarn dev`

## GitHub

~/chat-app# `git init`

~/chat-app# `git config --global user.name <Username>`

~/chat-app# `git config --global user.email <EmailAddress>`

~/chat-app# `git add .`

~/chat-app# `git commit -m 'first commit'`

~/chat-app# `git remote add origin <RemoteRipositoryURL>`

~/chat-app# `git push origin main`
