# 漫画風画像生成プロンプト

## 全体像（2つの事業を1枚で表現）

### プロンプト1: 全体像（横長レイアウト）

```
Japanese manga style illustration, business professional self-introduction, split panel layout, left side: publishing business scene with teacher/entrepreneur character holding a book, right side: caregiving app development scene with small care facility staff using tablet, modern clean manga art style, professional color scheme with blue and purple gradients, white background, detailed character expressions, business casual clothing, technology elements (smartphone, tablet, laptop), book publishing symbols (Amazon logo, book covers), caregiving symbols (clipboard, care plan), dynamic composition, high quality, 16:9 aspect ratio, --style raw --ar 16:9
```

### プロンプト2: 全体像（縦長レイアウト）

```
Japanese manga style illustration, business self-introduction poster, two main sections, top section: publishing business with flow diagram showing advertising → landing page → LINE → video → consultation → book publishing → Amazon bestseller, bottom section: custom app development for care facilities showing automation tools and time-saving benefits, modern manga art style, professional business illustration, clean line art, vibrant colors, white background, detailed panels, 9:16 aspect ratio, --style raw --ar 9:16
```

---

## ① 出版プロデュースビジネス専用

### プロンプト3: 出版プロデュースビジネス（フロー図）

```
Japanese manga style illustration, publishing business service flow, step-by-step visual guide: 1) advertising creative and inquiry form, 2) landing page connection, 3) LINE registration, 4) video viewing on LINE, 5) consultation booking, 6) customer analysis, 7) professional scriptwriter and designer supporting book publishing, 8) Amazon bestseller achievement, modern manga art style, business professional characters (teachers, small business owners), technology elements (smartphone with LINE app, laptop, video camera, book covers, Amazon logo), flow arrows connecting steps, clean composition, professional color scheme, white background, detailed panels, high quality, --style raw --ar 16:9
```

### プロンプト4: 出版プロデュースビジネス（シンプル版）

```
Japanese manga style illustration, publishing business support service, teacher/entrepreneur character transforming into published author, before and after comparison, left: struggling small business owner, right: successful author with book on Amazon bestseller list, supporting elements: advertising creative, LINE app, consultation video, professional book design, modern manga art style, professional business illustration, clean line art, vibrant colors, motivational atmosphere, white background, --style raw --ar 16:9
```

### プロンプト5: 作成ツール紹介

```
Japanese manga style illustration, AI automation tools for publishing business, four tool panels: 1) YouTube consultation video customer analysis tool, 2) automated book creation tool, 3) successful advertising creative analysis tool, 4) advertising creation tool, modern manga art style, technology and AI elements, dashboard interfaces, data visualization, professional business illustration, clean design, blue and purple color scheme, white background, detailed panels, --style raw --ar 16:9
```

---

## ② 介護事業者向けオーダーメイドアプリ作成専用

### プロンプト6: 介護アプリ作成サービス（メイン）

```
Japanese manga style illustration, custom app development service for small care facilities, care facility staff (50 employees or less) using custom mobile app, before and after comparison, left: staff overwhelmed with paperwork and repetitive tasks, right: staff using tablet app with automated workflows, time-saving benefits visualized, modern manga art style, realistic care facility setting, professional business illustration, warm and approachable atmosphere, technology elements (tablet, smartphone, cloud services), caregiving symbols (clipboard, care plan, medication), clean composition, white background, --style raw --ar 16:9
```

### プロンプト7: 介護アプリ作成サービス（成果報酬型）

```
Japanese manga style illustration, results-based monthly subscription service for care facilities, visual representation of "cost = time saved × hourly wage × 1/3", care facility staff with reduced workload, automated document processing, time tracking visualization, modern manga art style, professional business illustration, clear value proposition, technology and automation elements, positive atmosphere, clean design, blue and green color scheme, white background, --style raw --ar 16:9
```

### プロンプト8: 現状と今後の展開

```
Japanese manga style illustration, two-panel comparison for care app service, left panel "Current": direct consultation and custom development, engineer and care facility manager in discussion, right panel "Future": automated requirement definition and app release bot, AI and automation elements, modern manga art style, professional business illustration, technology progression visualization, clean composition, white background, --style raw --ar 16:9
```

---

## 使用上の注意

### 推奨画像生成サービス
- **Midjourney**: 上記プロンプトをそのまま使用可能
- **DALL-E 3**: `--style raw --ar` などのパラメータを削除して使用
- **Stable Diffusion**: プロンプトを調整して使用

### カスタマイズポイント
- **アスペクト比**: `--ar 16:9`（横長）または `--ar 9:16`（縦長）を変更可能
- **スタイル**: `--style raw` を削除するとよりアーティスティックに
- **色調**: カラースキームを変更したい場合は、色に関する記述を追加

### 日本語プロンプト版（必要に応じて）

各プロンプトの英語部分を日本語に置き換えることも可能です。ただし、多くの画像生成AIは英語プロンプトの方が精度が高い傾向があります。

---

## プロンプトの構造説明

1. **スタイル指定**: `Japanese manga style illustration` - 日本の漫画風スタイル
2. **主題**: 各事業の内容を具体的に記述
3. **視覚要素**: キャラクター、技術要素、シンボルなどを明記
4. **構成**: レイアウトやパネル構成を指定
5. **技術パラメータ**: アスペクト比、スタイル、品質などの指定

