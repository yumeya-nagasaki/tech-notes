---
layout: default
title: プロジェクトの作成
breadcrumbs:
    - title: Django
      url: /django/
---

<img src="../assets/images/django-logo-positive.svg" width="80" alt="Djangoのロゴ">

{% include breadcrumbs.html %}

# プロジェクトの作成

## コマンド実行

Djangoのプロジェクトを作成するには以下のコマンドを実行します。

```bash
django-admin startproject 【プロジェクトの名前】 【プロジェクトを入れるフォルダの名前】
```

例

```bash
django-admin startproject mysite djangotutorial
```

## 作成されるファイル

例のようにコマンドを実行すると、以下のようなフォルダ構成でファイルが作成されます。

```
djangotutorial/          ← 第2引数：プロジェクト全体をまとめるフォルダ
├── manage.py            ← 管理コマンドを実行するためのスクリプト
└── mysite/              ← 第1引数：プロジェクト名（設定ファイル群）
    ├── __init__.py
    ├── settings.py      ← データベースやアプリ登録などの設定
    ├── urls.py          ← URLルーティングの定義
    ├── asgi.py
    └── wsgi.py
```
