# texlive-devcontainer-template

dev containerを利用した、LaTeX環境を簡単に構築するテンプレート

Docker Image: [latex-docker](ghcr.io/being24/latex-docker)

詳しい使い方は[VSCodeとDockerでLaTeXを用いた多機能論文執筆環境を整える](https://zenn.dev/being/articles/how-to-use-my-latex)を参照
(ファイル構成だけ変更しています)

(**Dockerが必要です**)

## setup

1. テンプレートをclone
1. VS Codeで開く
2. 拡張機能[Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)を追加する
3. 左下の`><`アイコンを押して、`Rebuild Container`を実行する
4. 待つ
5. ワークスペースが開いたら、terminalを開き、`latexmk sample.tex`を実行する
6. `out`内に`sample.pdf`が出来たらsetup完了！

## build

```bash
latexmk sample.tex
```
