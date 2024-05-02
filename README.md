# template-project

<div align="center">
    <img src="logo.png" alt="logo">
</div>

<div align="center">
    <img alt="python versions" src="https://img.shields.io/badge/python-3.12-blue?color=1e94f3">
    <a href="https://opensource.org/licenses/MIT">
        <img alt="MIT License" src="https://img.shields.io/badge/license-MIT-green?color=1e94f3">
    </a>
    <a href="https://github.com/PyCQA/flake8">
        <img alt="ruff" src="https://img.shields.io/badge/code%20style-ruff-000000.svg?color=1e94f3">
    </a>
    <a href="https://github.com/python/mypy">
        <img alt="mypy" src="https://img.shields.io/badge/typing-mypy-blue?color=1e94f3">
    </a>
</div>
<br />

VSCode × Pythonでの開発環境のテンプレート

## Used libraries

- python3.12
- VSCode(devcontainer.json, setting.json, extensions.json)
- docker
- Rye + uv
- Ruff
- Mypy
- mdformat
- pytest

## Environment

### dockerコンテナ ビルド & 起動

```bash
docker compose up -d --build gpu
```

### コンテナにアタッチ

次にVScode左下の`><`ボタンより`コンテナで再度開く`でコンテナにアクセス

### 拡張機能インストール

無事コンテナが開いたら, 「拡張機能の推奨事項があります」という通知が出ると思います.
この通知を許可すると, `.vscode/extensions.json`に記載されている拡張機能が自動的にインストールされます.
もし通知が出なかった場合は, 左のメニューから`拡張機能`を選択し, `フィルターアイコン`->`推奨`‐>`インストールアイコン`を押せば一括インストールできます.

## Appendix

### 全般

<https://github.com/cvpaperchallenge/Ascender> \
<https://qiita.com/edge-m/items/846715217fc3dd481a84> \
<https://zenn.dev/zenizeni/books/a64578f98450c2> \
<https://zenn.dev/alivelimb/articles/20220501-python-env> \
<https://github.com/arrowkato/my_favorite_python_env> \
<https://zenn.dev/jdbtisk/articles/e6ed54b38b6a45> \
<https://qiita.com/ShortArrow/items/f29e4d0df7d836eec770>

### VSCode基本設定 & 拡張機能

<https://qiita.com/yamaguchi2000/items/76060c08764ce4c704f9> \
<https://qiita.com/papi_tokei/items/c639dc7d1e0f5ad68a74> \
<https://qiita.com/nanato12/items/ddf26487eb30714251c3> \
<https://maasaablog.com/integrated-development-environment/visual-studio-code/923/> \
<https://zenn.dev/sayuki_coding/articles/c389d9ad48feaa> \
<https://zenn.dev/yumemi_inc/articles/396265425c9740> \
<https://zenn.dev/yosemat/articles/36638f17e9ded8> \
<https://zenn.dev/necscat/articles/d0946fec7f84be> \
<https://de-milestones.com/vscode-how-to-setup-recommended-tools/>

### linter/formatter

<https://qiita.com/sin9270/items/85e2dab4c0144c79987d> \
<https://qiita.com/fehde/items/723b619013dc86008acc> \
<https://qiita.com/ciscorn/items/bf78b7ad8e0e332f891b>
