# Haskell Notes for Pythonists and Research Code

このリポジトリでは、Haskell に関する個人ノートを PDF として公開しています。

主なテーマは、Python 利用者の視点から Haskell を理解すること、Haskell の型・モジュール・プロジェクト構成を研究コードの整理や概念設計に活かすことです。

TeX ソースは private に管理し、この public リポジトリでは読み物として整えた PDF のみを公開しています。

## Contents

| PDF | Description |
|---|---|
| `Introduction_to_Haskell_for_pythonist.pdf` | Python 利用者向けの Haskell 入門ノート。変数、関数、型、`Maybe`、`Either`、`IO`、代数的データ型などを Python との比較で整理しています。 |
| `Python_and_Haskell.pdf` | Python と Haskell の役割分担についてのノート。Python を実験・可視化・データ処理の道具、Haskell を型・モデル・意味構造の道具として捉えています。 |
| `type-thinking-tool.pdf` | 「思考ツールとしての型」についてのノート。`newtype`、代数的データ型、多相型、型クラス、phantom type、GADT などを、概念整理の観点から扱っています。 |
| `Introduction_to_Haskell_modules.pdf` | Haskell の `module`、`import`、Cabal、`src/app` 構成、研究コードの資産化についてのノートです。 |

## Intended Audience

このリポジトリは、次のような読者を想定しています。

- Python には慣れているが、Haskell にはまだ十分慣れていない人
- Haskell の型や関数型プログラミングに興味がある人
- 研究用コードを長期的に整理・再利用したい人
- ゲーム理論、意思決定理論、TDA、ネットワーク解析などの数理的対象をコードとして構造化したい人
- Haskell を単なる実装言語ではなく、概念整理の道具として捉えたい人

## Status

These documents are personal working notes.

これらの文書は、網羅的な Haskell 教科書ではありません。  
学習・授業準備・研究コード設計・個人的な思考整理のための作業ノートです。

内容は今後も修正・加筆される可能性があります。

## Repository Policy

This repository provides PDF files only.

The original LuaLaTeX sources are maintained privately.  
This is because the documents depend on local font settings and are primarily intended as readable PDFs rather than collaboratively edited source files.

## Notes on Style

これらのノートでは、Haskell を主に次の観点から扱っています。

- Python との対比
- 型による概念整理
- 研究コードの資産化
- 数理モデルの構造化
- 教育用コードと研究用コードの接続
- 動的型付けと静的型付けの役割分担

動的型付けを否定する意図はありません。  
Python は、データ処理、可視化、統計処理、機械学習実験、探索的分析に非常に強い道具です。  
一方で、Haskell は、型、代数的データ型、多相型、型クラス、`Maybe`、`Either`、`IO` などを通して、概念構造を明示するための別種の道具として位置づけています。

## Recommended Reading Order

初めて読む場合は、次の順番を推奨します。

1. `Introduction_to_Haskell_for_pythonist.pdf`
2. `Python_and_Haskell.pdf`
3. `type-thinking-tool.pdf`
4. `Introduction_to_Haskell_modules.pdf`

まず Pythonist 向けの導入で Haskell の基本的な考え方を掴み、次に Python と Haskell の役割分担を読み、その後で型を思考ツールとして捉えるノートへ進むと読みやすいです。最後に、Haskell のモジュール・import・Cabal 構成を読むと、研究コードとして育てるための見通しが立ちます。

## Disclaimer

本リポジトリの内容は個人的な学習・研究メモであり、所属機関の公式見解を示すものではありません。

The views and interpretations in these notes are my own.

## License

Unless otherwise noted, the PDF documents in this repository are licensed under:

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

Code snippets included in the documents may be used under the MIT License.

If you prefer to restrict commercial reuse, replace this section with CC BY-NC 4.0 before publishing.
