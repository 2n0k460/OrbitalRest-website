# OrbitalRest Support Page

このリポジトリは、**OrbitalRest** のサポートページを GitHub Pages で公開するためのファイルを管理します。  
深い夜空をイメージしたインタラクティブな星空アニメーションと、アプリの世界観を反映したスタイルを備えています。

---

## リポジトリ構成
```
/
├─ index.html # サポートページ
├─ privacy_policy.html # プライバシーポリシー
├─ CNAME # カスタムドメイン（orbitalrest.app）
└─ README.md # このファイル
```

---

## 公開手順
1. **リポジトリをクローン**  
   git clone https://github.com/yourusername/Orbitalrest-website.git
   cd Orbitalrest-website
2. CNAME 設定
   docs/CNAME ファイルに以下を記述して、orbitalrest.app を設定します。
3. GitHub Pages の設定
   GitHub リポジトリの Settings → Pages → Source を main branch / docs folder に設定
   ドメインが https://orbitalrest.app で公開されます
4. コミット & プッシュ
   git add .
   git commit -m "Deploy support and privacy pages"
   git push origin main
