# Next.js × shadcn/ui × CI

[![DELOGs 記事へ](https://img.shields.io/badge/DELOGs-記事はこちら-1e90ff?logo=githubpages)](https://delogs.jp/next-js/supplement/github-ci)

Next.js 15 に **shadcn/ui** を導入し、`<Button>` を 1 つ表示するだけのミニマム構成で、GitHub Actions でビルドまでのチェックができるようにしています。  
**記事本編** では各工程を詳しく解説しています。

---

## クイックスタート

```bash
# クローンコマンドでソースをもってきます
git clone https://github.com/delogs-jp/github-ci.git

cd github-ci

npm install       # 依存を取得
npm run dev       # http://localhost:3000 で確認
```

## フォルダ構成（抜粋）

```bash
src/
  app/page.tsx        # トップページ – Button を配置
  components/ui/…     # shadcn/ui 生成コンポーネント
  .github/workflows/ci.yml # ワークフローファイル
```

## ライセンス

MIT © 2025 delogs-jp
