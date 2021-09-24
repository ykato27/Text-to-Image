# Text-to-Image

テキストからの画像生成するモデルのexample リポジトリです。

## リポジトリ構成

```
.
├── Dockerfile
├── README.md
├── data
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── Aleph2Image_(Delta)_CLIP+DALL_E_decoder.ipynb
│   ├── BigSleep
│   │   ├── BigSleep.ipynb
│   │   └── The_Big_Sleep_BigGANxCLIP.ipynb
│   ├── DALL-E
│   │   ├── Afiaka_DALL_E_Generation.ipynb
│   │   ├── DALL_E.ipynb
│   │   └── DALL_E_demo.ipynb
│   └── Text2Image_CLIP.ipynb
├── pyproject.toml
├── requirements.txt
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
```

## 環境詳細

- Python : 3.9.6

## 事前準備

- Docker インストール

## 環境構築

- Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/Text-to-Image）

```
cd Desktop/Text-to-Image
```

- Dockerによる環境構築（フォルダをマウント：Desktop/Text-to-Image）

```
docker-compose up --build
```

- ブラウザーを立ち上げてlocalhost:8888へアクセス
- ローカルフォルダがマウントされている

## 動作環境

マシンスペック（Mac)

- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
