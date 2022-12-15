# Djangoチュートリアル

## 目次
1. [はじめに](#はじめに)
1. [環境](#環境)
1. [環境設定]()

### はじめに
この記事では、PythonのDjangoというライブラリを使って、Webアプリを作成する方法を紹介します。

### 環境
- Python 3.8.10
- Django 4.1.3

### 環境設定
  1. 仮想環境の構築
    Windows
    ```
    python -m venv myvenv
    ```
    Linux and OS X
    ```
    python3 -m venv myvenv
    ```
  2. 仮想環境の起動
    Windows
    ```
    myvenv\Scripts\activate
    ```
    Linux and OS X
    ```
    source myvenv/bin/activate
    ```
  3. pipコマンドのアップデート
    ```
    python -m pip install --upgrade pip
    ```
  4. ライブラリのインストール
    ```
    pip install Django
    ```

### Djangoでアプリ作成

