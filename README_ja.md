<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&multiline=true&width=800&height=100&lines=%E6%9E%97+%E9%A7%BF%E7%94%AB+%2F+Shunsuke+Hayashi;%E5%90%88%E5%90%8C%E4%BC%9A%E7%A4%BE%E3%81%BF%E3%82%84%E3%81%B3+CEO;39%E4%BD%93%E3%81%AEAI%E3%82%A8%E3%83%BC%E3%82%B8%E3%82%A7%E3%83%B3%E3%83%88%E3%81%A7%E4%BC%9A%E7%A4%BE%E3%82%92%E5%9B%9E%E3%81%99)](https://github.com/DenverCoder1/readme-typing-svg)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=%E6%9E%97%20%E9%A7%BF%E7%94%AB&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=%E5%90%88%E5%90%8C%E4%BC%9A%E7%A4%BE%E3%81%BF%E3%82%84%E3%81%B3%20CEO%20%7C%20AI%20Agent%20Architect&descAlignY=55&descSize=18" width="100%"/>

🌐 **[English](./README.md)** | 🇯🇵 **日本語**

[![Website](https://img.shields.io/badge/miyabi--ai.jp-6366F1?style=for-the-badge&logoColor=white)](https://www.miyabi-ai.jp)
[![X (Twitter)](https://img.shields.io/badge/@The__AGI__WAY-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/The_AGI_WAY)
[![note](https://img.shields.io/badge/note-41C9B4?style=for-the-badge&logo=note.mu&logoColor=white)](https://note.ambitiousai.co.jp)
[![Teachable](https://img.shields.io/badge/Teachable-FF5733?style=for-the-badge&logo=teachable&logoColor=white)](https://shuhayas-s-school.teachable.com)

<img src="https://komarev.com/ghpvc/?username=ShunsukeHayashi&label=Profile+Views&color=6366F1&style=flat-square" alt="Profile Views"/>

</div>

---

## 自己紹介

> *「非エンジニアからAIアーキテクトへ。39体の自律AIエージェントが24時間ビジネスを回している。」*

**林 駿甫（はやし しゅんすけ）** — 愛知県一宮市在住。**合同会社みやび** CEO（2026年4月設立）。

エンジニアリングの正規教育を受けずに、**ゴールシークプロンプトデザイン**という独自の方法論を開発。Claude / OpenAI Codex / Gemini の**マルチモデルオーケストレーション**をプロダクションスケールで実現し、**39体の自律AIエージェント**を**5台の分散マシンクラスター**上で24時間運用しています。

| 指標 | 数値 |
|------|------|
| 🐦 X (Twitter) フォロワー | **38,000+** |
| 📝 note フォロワー | **5,447** |
| 🎓 Teachable 受講者 | **981件 / 9コース** |
| 💬 L-Step アクティブユーザー | **4,771名** |
| 🤖 自律AIエージェント | **39体** / 5台クラスター |
| ⏰ 自動cronジョブ | **59本**が24時間稼働 |
| 📦 公開リポジトリ | **66本**（オリジナル） |

---

## 自律エージェント・アーキテクチャ

```
                    ┌──────────────────────────────────┐
                    │   Windows Gateway (OpenClaw)      │
                    │   39体エージェント · 59 cronジョブ  │
                    │   Tailscale VPNメッシュ            │
                    └───────────────┬──────────────────┘
                                    │
              ┌─────────────────────┼─────────────────────┐
              │                     │                      │
     ┌────────┴───────┐  ┌─────────┴────────┐  ┌─────────┴──────────┐
     │ Worker-Mini1   │  │ Worker-Mini2     │  │ Worker-MacBook Pro │
     │ Mac mini       │  │ Mac mini         │  │ MacBook Pro        │
     │ コア＋開発      │  │ コンテンツ＋PPAL  │  │ SNS＋コーディング   │
     └────────────────┘  └──────────────────┘  └────────────────────┘
              │
     ┌────────┴───────┐
     │ Worker-Mini3   │
     │ Mac mini       │
     │ 3D特化         │
     └────────────────┘
```

**エージェントが24時間やっていること:**
- 🤖 **Discord**: 14体のAIキャラクターがコミュニティを自律運営
- 📝 **コンテンツ**: X・note・Teachable向けの下書き自動生成
- 💻 **開発**: コード生成、レビュー、PR作成、CI/CDデプロイ
- 📊 **経営管理**: 経費処理、KPIモニタリング、スケジュール管理
- 🔒 **セキュリティ**: 自動監査、ファイアウォール監視、脆弱性スキャン

---

## コア哲学: ゴールシークプロンプトデザイン

```
F(ゴール達成) = ∫F(ステップ) = A → Z
```

| フレームワーク | 説明 |
|---------------|------|
| **ゴールシークプロンプトデザイン** | ゴールから逆算してAIエージェントの行動を設計する独自フレームワーク |
| **コンテキストエンジニアリング** | 階層型YAMLによるマルチエージェントコンテキスト管理 |
| **MISO** | Mission Inline Skill Orchestration — Telegram上で動くエージェントUI |
| **θ(シータ)サイクル** | `θ₁→θ₆` 自己改善ループ: 観察→分析→判断→実行→検証→学習 |

---

## 技術スタック

### AI / LLM
![Claude](https://img.shields.io/badge/Claude_Opus_4.6-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_Codex-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.5-4285F4?style=for-the-badge&logo=google&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-FF6B35?style=for-the-badge)
![OpenClaw](https://img.shields.io/badge/OpenClaw-E74C3C?style=for-the-badge)

### 言語 & フレームワーク
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)

### ツール & プラットフォーム
![Claude Code](https://img.shields.io/badge/Claude_Code-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-000000?style=for-the-badge&logo=tailscale&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)

---

## ⭐ 代表プロジェクト

> スター数上位。すべてオリジナル（フォークなし）。

| プロジェクト | 説明 | Stars |
|-------------|------|-------|
| [🔌 miyabi-claude-plugins](https://github.com/ShunsukeHayashi/miyabi-claude-plugins) | Claude Code用 **25+エージェント, 22スキル, 50+コマンド** | ![](https://img.shields.io/github/stars/ShunsukeHayashi/miyabi-claude-plugins?style=social) |
| [🤖 Miyabi_AI_Agent](https://github.com/ShunsukeHayashi/Miyabi_AI_Agent) | マルチエージェントオーケストレーション搭載の自律AIコーディングエージェント | ![](https://img.shields.io/github/stars/ShunsukeHayashi/Miyabi_AI_Agent?style=social) |
| [🧠 context_engineering_MCP](https://github.com/ShunsukeHayashi/context_engineering_MCP) | 階層型YAMLコンテキスト抽出 via MCP | ![](https://img.shields.io/github/stars/ShunsukeHayashi/context_engineering_MCP?style=social) |
| [✍️ Shunsuke-style-PromptDesign](https://github.com/ShunsukeHayashi/Shunsuke-style-PromptDesign) | **ゴールシークプロンプトデザイン** 方法論 | ![](https://img.shields.io/github/stars/ShunsukeHayashi/Shunsuke-style-PromptDesign?style=social) |
| [🎮 rpgmaker-mz-mcp](https://github.com/ShunsukeHayashi/rpgmaker-mz-mcp) | MCPツールだけで完全なRPGを制作 | ![](https://img.shields.io/github/stars/ShunsukeHayashi/rpgmaker-mz-mcp?style=social) |
| [🏯 Miyabi](https://github.com/ShunsukeHayashi/Miyabi) | 経済ガバナンス搭載のオープンソース自律開発フレームワーク | ![](https://img.shields.io/github/stars/ShunsukeHayashi/Miyabi?style=social) |
| [🤖 Auto-coder-agent](https://github.com/ShunsukeHayashi/Auto-coder-agent_Cursor_Roo_code) | Cursor & Roo Code向け自律コーディングエージェント | ![](https://img.shields.io/github/stars/ShunsukeHayashi/Auto-coder-agent_Cursor_Roo_code?style=social) |
| [🍜 miso](https://github.com/ShunsukeHayashi/miso) | MISO — Telegram上で動く自律エージェントUIフレームワーク | ![](https://img.shields.io/github/stars/ShunsukeHayashi/miso?style=social) |

---

## 全オリジナルリポジトリ

<details>
<summary><b>🤖 AIエージェントフレームワーク (11本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [miyabi-claude-plugins](https://github.com/ShunsukeHayashi/miyabi-claude-plugins) | Claude Code用 25+エージェント, 22スキル, 50+コマンド | ⭐30 |
| [Miyabi_AI_Agent](https://github.com/ShunsukeHayashi/Miyabi_AI_Agent) | マルチエージェントオーケストレーション搭載の自律AIコーディングエージェント | ⭐29 |
| [Miyabi](https://github.com/ShunsukeHayashi/Miyabi) | オープンソース自律開発フレームワーク | ⭐16 |
| [Auto-coder-agent_Cursor_Roo_code](https://github.com/ShunsukeHayashi/Auto-coder-agent_Cursor_Roo_code) | Cursor & Roo Code向け自律コーディングエージェント | ⭐16 |
| [Dev_Claude](https://github.com/ShunsukeHayashi/Dev_Claude) | YAMLコンテキストエンジニアリングエージェント | ⭐7 |
| [swml-agent](https://github.com/ShunsukeHayashi/swml-agent) | SWML物理モデルベースのコーディングエージェント | ⭐3 |
| [XinobiAgent_Devin](https://github.com/ShunsukeHayashi/XinobiAgent_Devin) | Devinスタイルの自律開発エージェント | ⭐3 |
| [claude-agent-sdk](https://github.com/ShunsukeHayashi/claude-agent-sdk) | Claude Agent SDK | ⭐2 |
| [XinobiAgent](https://github.com/ShunsukeHayashi/XinobiAgent) | Xinobi自律エージェント | ⭐2 |
| [AI_entrepreneur_Agent](https://github.com/ShunsukeHayashi/AI_entrepreneur_Agent) | 自律ビジネス運用エージェント | ⭐1 |
| [swml](https://github.com/ShunsukeHayashi/swml) | SWMLエージェントオーケストレーター | — |

</details>

<details>
<summary><b>🔗 MCPサーバー (8本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [context_engineering_MCP](https://github.com/ShunsukeHayashi/context_engineering_MCP) | 階層型YAMLコンテキスト抽出 | ⭐28 |
| [rpgmaker-mz-mcp](https://github.com/ShunsukeHayashi/rpgmaker-mz-mcp) | MCPツールでRPG制作 | ⭐21 |
| [miyabi-mcp-bundle](https://github.com/ShunsukeHayashi/miyabi-mcp-bundle) | Claude Desktop向けオールインワンMCPサーバー | ⭐5 |
| [MCP](https://github.com/ShunsukeHayashi/MCP) | MCPサーバー実装集 | ⭐4 |
| [lark-wiki-mcp-agents](https://github.com/ShunsukeHayashi/lark-wiki-mcp-agents) | Lark/飛書 Wiki操作 via MCP | ⭐4 |
| [lark-openapi-mcp-enhanced](https://github.com/ShunsukeHayashi/lark-openapi-mcp-enhanced) | 飛書/Lark OpenAPI MCP強化版 | ⭐4 |
| [tyrano-studio-mcp](https://github.com/ShunsukeHayashi/tyrano-studio-mcp) | ティラノスタジオゲーム開発 via MCP | ⭐2 |
| [voicebox-mcp](https://github.com/ShunsukeHayashi/voicebox-mcp) | VOICEVOX音声合成 via MCP | — |

</details>

<details>
<summary><b>✍️ プロンプトエンジニアリング (5本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [Shunsuke-style-PromptDesign](https://github.com/ShunsukeHayashi/Shunsuke-style-PromptDesign) | ゴールシークプロンプトデザイン方法論 | ⭐21 |
| [hayashi-agent-prompt-generator](https://github.com/ShunsukeHayashi/hayashi-agent-prompt-generator) | AIエージェントプロンプト自動生成 | ⭐1 |
| [plugin-generator](https://github.com/ShunsukeHayashi/plugin-generator) | Claude Codeプラグインスキャフォールディング | ⭐2 |
| [agent-context-study](https://github.com/ShunsukeHayashi/agent-context-study) | モデル間コンテキスト理解比較 | — |
| [sop-generator](https://github.com/ShunsukeHayashi/sop-generator) | AI搭載SOP作成ツール | — |

</details>

<details>
<summary><b>💬 コミュニティ & コミュニケーション (4本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [miso](https://github.com/ShunsukeHayashi/miso) | MISO — Telegram上の自律エージェントUI | ⭐9 |
| [a2a](https://github.com/ShunsukeHayashi/a2a) | Agent-to-Agent通信プロトコル | ⭐3 |
| [miyabi-discord](https://github.com/ShunsukeHayashi/miyabi-discord) | 14体AIキャラによるDiscord自律運営 | — |
| [LINE_Notification_discord](https://github.com/ShunsukeHayashi/LINE_Notification_discord) | LINE→Discord通知ブリッジ | ⭐1 |

</details>

<details>
<summary><b>🚀 AIアプリケーション (7本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [shunsuke-ultimate-ai-platform](https://github.com/ShunsukeHayashi/shunsuke-ultimate-ai-platform) | マルチモデルAI統合プラットフォーム | ⭐5 |
| [shinyu-ai](https://github.com/ShunsukeHayashi/shinyu-ai) | AI占い: タロット＋易経＋占星術 | ⭐5 |
| [AntiGravity_miyabi_edition](https://github.com/ShunsukeHayashi/AntiGravity_miyabi_edition) | 反重力シミュレーション | ⭐3 |
| [hanzo](https://github.com/ShunsukeHayashi/hanzo) | クロスプラットフォームAIアシスタント (Flutter) | ⭐2 |
| [ai-partner-app](https://github.com/ShunsukeHayashi/ai-partner-app) | 人格と記憶を持つAIコンパニオン | ⭐2 |
| [agent-visionary-console](https://github.com/ShunsukeHayashi/agent-visionary-console) | AIエージェントリアルタイム監視ダッシュボード | ⭐2 |
| [3D_Tetris_Engine](https://github.com/ShunsukeHayashi/3D_Tetris_Engine) | 3Dテトリスエンジン | ⭐1 |

</details>

<details>
<summary><b>🦞 OpenClawエコシステム (3本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [openclaw-prod](https://github.com/ShunsukeHayashi/openclaw-prod) | 本番運用: ランブック、ガードレール、アップグレードゲート | ⭐2 |
| [MiyabiDash](https://github.com/ShunsukeHayashi/MiyabiDash) | OpenClaw iOS ダッシュボード — ウィジェット＋Dynamic Island | — |
| [voiceclaw](https://github.com/ShunsukeHayashi/voiceclaw) | OpenClaw向けハンズフリー音声入力 | — |

</details>

<details>
<summary><b>🎙️ 音声 & オーディオ (3本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [byteplus-voice-ai](https://github.com/ShunsukeHayashi/byteplus-voice-ai) | BytePlus音声AI: ASR＋TTS＋ボイスクローン | ⭐1 |
| [voicebox-tts](https://github.com/ShunsukeHayashi/voicebox-tts) | VOICEVOX TTSキューイングシステム | — |
| [VoiceFlow](https://github.com/ShunsukeHayashi/VoiceFlow) | iOS向けAI音声キーボード | — |

</details>

<details>
<summary><b>💼 ビジネス & マーケティング (6本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [gas-executor](https://github.com/ShunsukeHayashi/gas-executor) | Google Apps Script Executor | ⭐7 |
| [mastra-youtube-affiliate](https://github.com/ShunsukeHayashi/mastra-youtube-affiliate) | AI搭載アフィリエイトマーケティング | ⭐3 |
| [Ad_generator](https://github.com/ShunsukeHayashi/Ad_generator) | AI広告コピージェネレーター | ⭐2 |
| [law-api-agent](https://github.com/ShunsukeHayashi/law-api-agent) | 日本法令APIエージェント | ⭐2 |
| [shadow-marketer-lp](https://github.com/ShunsukeHayashi/shadow-marketer-lp) | AIマーケティングLP | ⭐1 |
| [Painting_Estimate_App](https://github.com/ShunsukeHayashi/Painting_Estimate_App) | 塗装工事見積もりアプリ | ⭐1 |

</details>

<details>
<summary><b>🎓 教育 / PPAL (6本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [ppal-skill-library](https://github.com/ShunsukeHayashi/ppal-skill-library) | PPAL SKILL.mdライブラリ | ⭐4 |
| [how-to-use-miyabi](https://github.com/ShunsukeHayashi/how-to-use-miyabi) | 自律開発ガイド | ⭐4 |
| [ppal-mcp-collection](https://github.com/ShunsukeHayashi/ppal-mcp-collection) | PPAL MCPサーバーコレクション | ⭐2 |
| [teachable-webhook-aws](https://github.com/ShunsukeHayashi/teachable-webhook-aws) | Teachable → Discord (AWS Lambda) | ⭐1 |
| [miyabi-ppal-plugin](https://github.com/ShunsukeHayashi/miyabi-ppal-plugin) | Claude Code用コースプラグイン | — |
| [sasaerun-faq](https://github.com/ShunsukeHayashi/sasaerun-faq) | ささえるん FAQ管理 | — |

</details>

<details>
<summary><b>📝 コンテンツ & パブリッシング (5本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [Notion-ChatGPT-streaming-connector](https://github.com/ShunsukeHayashi/Notion-ChatGPT-streaming-connector) | Notion × ChatGPTリアルタイム連携 | ⭐1 |
| [blog-summarizer](https://github.com/ShunsukeHayashi/blog-summarizer) | AI搭載ブログ要約ツール | ⭐1 |
| [note_gen](https://github.com/ShunsukeHayashi/note_gen) | note.comコンテンツジェネレーター | ⭐1 |
| [zenn](https://github.com/ShunsukeHayashi/zenn) | Zenn技術記事 | ⭐1 |
| [NoteWriter](https://github.com/ShunsukeHayashi/NoteWriter) | note.com iOSクライアント | — |

</details>

<details>
<summary><b>🔧 その他 (8本)</b></summary>

| リポジトリ | 説明 | Stars |
|-----------|------|-------|
| [heroui](https://github.com/ShunsukeHayashi/heroui) | HeroUIコンポーネントフレームワーク | ⭐1 |
| [AI_sachiko](https://github.com/ShunsukeHayashi/AI_sachiko) | AIキャラクタープロジェクト | ⭐1 |
| [AI-human-game](https://github.com/ShunsukeHayashi/AI-human-game) | AI vs 人間ゲーム | ⭐1 |
| [translation_app_lao](https://github.com/ShunsukeHayashi/translation_app_lao) | ラオス語翻訳アプリ | ⭐1 |
| [chrome_nanobanana](https://github.com/ShunsukeHayashi/chrome_nanobanana) | AI画像生成Chrome拡張 | — |
| [sanbo-ai-lp](https://github.com/ShunsukeHayashi/sanbo-ai-lp) | 参謀AI LP | — |
| [cc_test](https://github.com/ShunsukeHayashi/cc_test) | Claude Codeテストサンドボックス | — |
| [Plugin-marketplace](https://github.com/ShunsukeHayashi/Plugin-marketplace) | Claude Codeプラグインマーケットプレイス | — |

</details>

---

## GitHub統計

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=ShunsukeHayashi&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=6366F1&icon_color=6366F1&text_color=C9D1D9&locale=ja"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ShunsukeHayashi&layout=compact&langs_count=10&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6366F1&text_color=C9D1D9&locale=ja"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=ShunsukeHayashi&theme=tokyonight&hide_border=true&background=0D1117&stroke=6366F1&ring=6366F1&fire=FF6B35&currStreakLabel=6366F1&sideLabels=C9D1D9&dates=C9D1D9&currStreakNum=FFFFFF&sideNums=FFFFFF&locale=ja)](https://github.com/DenverCoder1/github-readme-streak-stats)

</div>

---

## トロフィー

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=ShunsukeHayashi&theme=tokyonight&no-frame=true&no-bg=true&margin-w=4&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## コントリビューション活動

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=ShunsukeHayashi&bg_color=0D1117&color=6366F1&line=6366F1&point=FF6B35&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

## 合同会社みやびについて

<div align="center">

[![Built by Miyabi AI](https://img.shields.io/badge/Built%20by-合同会社みやび-6366F1?style=for-the-badge&logo=github&logoColor=white)](https://www.miyabi-ai.jp)

**合同会社みやび** — 愛知県一宮市。2026年4月設立。

> *「AIと人間が共に働く世界を、自ら証明し、社会に届ける。」*

3本柱: **Build**（つくる）× **Operate**（まわす）× **Educate**（つたえる）

</div>

---

## つながる

<div align="center">

| プラットフォーム | リンク | 実績 |
|----------------|--------|------|
| 🐦 **X (Twitter)** | [@The_AGI_WAY](https://x.com/The_AGI_WAY) | 38,000+ フォロワー |
| 📝 **note** | [note.ambitiousai.co.jp](https://note.ambitiousai.co.jp) | 5,447 フォロワー |
| 🎓 **Teachable** | [みやびAIスクール](https://shuhayas-s-school.teachable.com) | 981件 / 9コース |
| 🌐 **公式サイト** | [miyabi-ai.jp](https://www.miyabi-ai.jp) | コーポレートサイト |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

*⭐ このプロジェクトが参考になったら、ぜひスターをお願いします！*

</div>
