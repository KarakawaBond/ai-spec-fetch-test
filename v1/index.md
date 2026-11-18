# AI向け仕様書インデックス（テスト用ダミー v0.1）

これは実現可能性調査のための仮ファイルです。本番仕様ではありません。

## 読む順番

1. このファイル（index.md）
2. spec.md … 制作ルールと専用形式（テスト用に簡略化したもの）\
   &#x20;  [https://raw.githubusercontent.com/KarakawaBond/ai-spec-fetch-test/main/v1/spec.md](https://raw.githubusercontent.com/KarakawaBond/ai-spec-fetch-test/main/v1/spec.md)
3. sample.md … 形式に適合したサンプルシナリオ\
   &#x20;  [https://raw.githubusercontent.com/KarakawaBond/ai-spec-fetch-test/main/v1/sample.md](https://raw.githubusercontent.com/KarakawaBond/ai-spec-fetch-test/main/v1/sample.md)

※参照先は必ず完全なURLで記載すること。ファイル名だけだと、URLを推測して開けないAI（Claude等）が取得できない（2026-11-18 の調査で判明）。

## 重要ルール（要約）

- 制作に必要な情報が不足していれば利用者に質問する。ただし、この会話ですでに判明していることは聞き直さない
- 構成案を利用者に提示し、確認が取れてからシナリオを生成する
- 利用者が文章をそのまま渡した場合は、言い換えずにそのままシナリオへ入れる
- 最終成果物は spec.md の専用形式どおりに、JSONのみをコードブロックで出力する
- このファイルが読めない・途中で読めなくなった場合は、推測で進めず、利用者にファイルの添付を依頼する

## 版

- 仕様版： test-0.1
- 対応する成果物の formatVersion は "test-0.1" とすること
