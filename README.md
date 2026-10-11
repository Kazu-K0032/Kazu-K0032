# Kazu-K0032 Profile

## 👋 自己紹介

インターン期間を含めて約 4 年、Web アプリの開発からインフラ構築まで、フルスタックに経験してきた Web エンジニアです。

- **得意分野**: Next.js / TypeScript でのフロントエンド開発、WordPress でのサイト構築、Python や GAS による自動化
- **最近の取り組み**: Claude Code を業務に取り入れ、Issue 作成から実装・PR 作成・レビューまでの開発フローに AI を組み込んでいます。検証結果はガイドラインにまとめ、チームに展開しています
- **今後の方向性**: 特定の領域にとらわれないフルスタックエンジニアとして、プロダクトの成長に関わっていきたいと考えています

## 🛠 代表作

### claude-plugins

Claude Code の個人用プラグインマーケットプレイスです。ADR の作成、Issue の着手から実装・コミット・PR 準備まで、リポジトリの初期設定などの定型作業を Skill にまとめ、複数のプロジェクト・PC で同じ手順を使い回せるようにしています。

- **リポジトリ**: [Kazu-K0032/claude-plugins](https://github.com/Kazu-K0032/claude-plugins)
- **技術**: Claude Code（Skill・Agent・Hook）、Python、TypeScript、Shell
- **工夫した点**: コミットや外部への書き込みは行わずに提案までにとどめるなど、AI に任せる範囲を設計の方針として明文化しています。また、版を付けてリリースし、変更点を追えるようにしています

### anime-board-to-video（非公開）

掲示板のトピックから YouTube 動画を自動生成するシステムです。トピックの取得から、台本の生成、動画編集ソフトへのボイス・字幕・画像の配置、サムネイル案やタイトルなどの投稿用情報の生成、YouTube へのアップロードまでを自動化しています。

- **成果**: 1 本あたりの制作時間を、最低 2 時間から最短 30 分〜1 時間半に短縮
- **規模**: 2025 年 12 月から個人で開発し、コミット数は 500 件以上
- **技術**: Python、Claude Code（Skills）、MCP（Claude Desktop 連携）、OpenAI API、Grok API、YouTube Data API、pytest
- **開発の進め方**: ADR とドキュメントを先に整え、Claude Code で実装する AI 駆動開発

### その他の公開作品

| 作品 | 内容 | 技術 |
| --- | --- | --- |
| [population-trend-graph-app](https://github.com/Kazu-K0032/population-trend-graph-app)（[デモ](https://population-trend-graph-app.vercel.app)） | 都道府県別の人口推移グラフ。RESAS API の提供終了に合わせて e-Stat API へ移行 | React、TypeScript、Vite、Chart.js |
| [profile](https://github.com/Kazu-K0032/profile)（[サイト](https://kuji-server.com/)） | 個人プロフィールサイト。レスポンシブ・ダークモード対応 | Next.js、TypeScript、Tailwind CSS v4 |
| [tiktok-api-features](https://github.com/Kazu-K0032/tiktok-api-features)（[デモ](https://tiktok-api-features.vercel.app)） | TikTok API でプロフィール・投稿動画を取得・表示し、動画の投稿まで行えるアプリ | Python（Flask）、JavaScript、TikTok API |
| [go-chat-app](https://github.com/Kazu-K0032/go-chat-app)（[デモ](https://go-chat-app-240878580464.asia-northeast1.run.app/)） | 認証・プロフィール編集・ユーザー検索付きのチャットアプリ | Go、Firebase、Docker、Cloud Run |

## 💻 技術スタック

| 分野 | 技術 | 使った場面 |
| --- | --- | --- |
| 言語 | TypeScript、JavaScript、Python、Go、PHP | 業務・個人開発 |
| フロントエンド | Next.js、React、Vue.js、Tailwind CSS、SCSS | 業務（Next.js）、profile、population-trend-graph-app |
| バックエンド・CMS | Prisma（PostgreSQL）、WordPress、Strapi、Flask、Firebase | 業務（Prisma・WordPress）、tiktok-api-features、go-chat-app |
| インフラ・運用 | AWS、GCP、Terraform、Docker、GitHub Actions、Vercel、Cloud Run | 業務（AWS・Terraform）、go-chat-app、このリポジトリ |
| テスト | pytest、Jest、React Testing Library | anime-board-to-video、comprehensive-testing |
| 自動化・AI | Claude Code、Cursor、Google Apps Script | 業務（AI 駆動開発の導入・GAS による自動化）、claude-plugins、anime-board-to-video |

## 🚀 経歴・チーム開発

### 職歴

| 時期 | 内容 | 主な技術 |
| --- | --- | --- |
| 2024 年〜現在 | IT 企業の Web エンジニア。受託の Web サイト制作・改修・保守、SNS 運用システムの新規開発、AI 駆動開発の導入検証と社内展開 | Next.js、WordPress、Prisma、AWS、Terraform、Claude Code |
| 2023〜2024 年 | 同じ会社でのインターン。GAS による社内業務の自動化と、新人エンジニアへの教育 | Google Apps Script |
| 2022〜2023 年 | プログラミングスクールのメンター。フロントエンドの講義と、受講生チームの開発支援 | JavaScript、Vue.js、Firebase |

主な実績:

- 設計・インフラ構築・実装を 1 人で担当した Web サイトを、予定工数（2 か月）内でリリース
- 開発フローに Claude Code を組み込み、小規模なバグ修正を従来の数倍の速さで対応
- SNS 運用システムの開発で、Prisma のスキーマを複数ファイルに分ける構成を提案・導入
- 6 人チームの研修開発で PM を担当し、期間内に完成

### 個人で参加したチーム開発

| 時期 | プロジェクト | 内容 | 役割・実績 | 技術 |
| --- | --- | --- | --- | --- |
| 2022 年 5〜6 月 | [GSread（sky-app）](https://github.com/webex14-team-3/sky-app) | プログラミングスクールの受講生同士で、学んだ知識を共有するアプリ | 4 人チームでフロントエンドを担当。PR 48 件のうち 17 件を作成 | Vue.js、Firebase |
| 2022 年 11〜12 月 | [team10-original-app](https://github.com/webex16-team-10/team10-original-app) | 謎解きをしながらプログラミングを学べるアドベンチャーゲーム | 4 人チームでクイズ・クロスワードなどの画面を担当。PR 27 件のうち 7 件を作成 | Vue.js、Firebase |

## 📊 統計

> **概要**: 統計情報（リポジトリ数、コミット数、Issues、PR 数）
>
> **集計条件**: プライベートリポジトリを含む全データ、クローズ済みも含む。コミット・Issues・PR は本人が作成したものだけを数え、他のユーザーや組織のリポジトリでの分も含む
>
> **更新頻度**: 1 日 1 回自動更新（GitHub Actions で GitHub API から取得）

<div style="display: flex; column-gap: 16px;">
  <table>
    <tr>
      <td align="center">
        <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FKazu-K0032%2FKazu-K0032%2Fmain%2Fbadge%2Ftotal-repos.json" alt="Total Repos" />
      </td>
      <td align="center">
        <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FKazu-K0032%2FKazu-K0032%2Fmain%2Fbadge%2Fpublic-repos.json" alt="Public Repos" />
      </td>
      <td align="center">
        <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FKazu-K0032%2FKazu-K0032%2Fmain%2Fbadge%2Fprivate-repos.json" alt="Private Repos" />
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FKazu-K0032%2FKazu-K0032%2Fmain%2Fbadge%2Ftotal-commits.json" alt="Total Commits" />
      </td>
      <td align="center">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/Kazu-K0032/Kazu-K0032/main/badge/total-issues.json" alt="Total Issues" />
      </td>
      <td align="center">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/Kazu-K0032/Kazu-K0032/main/badge/total-prs.json" alt="Total PRs" />
      </td>
    </tr>
  </table>
</div>

## 🔗 リンク

<p align="left">
  <a href="https://kuji-server.com/">
    <img src="https://img.shields.io/badge/Portfolio-4CAF50?style=for-the-badge&logo=About.me&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://twitter.com/Cookie_Kazu24">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
</p>

<p align="left">
  <a href="https://github.com/Kazu-K0032">
    <img src="https://komarev.com/ghpvc/?username=Kazu-K0032" alt="Profile views" />
  </a>
</p>
