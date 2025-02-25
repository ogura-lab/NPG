# ファイルの実行方法・詳細
```
シミュレーションを行いたいD,Tの組み合わせに対応するディレクトリを選び，case1.ipynbからcase40.ipynbまでそれぞれシミュレーションを行うことでレジームシフトが起こる頻度を計算する。各コードの詳細に関してはtest-codeディレクトリにあるコメントアウトを参照。
```

## ライブラリのバージョン
```
python: 3.10.12
torch: 2.4.0
numpy: 1.26.4
matplotlib: 3.9.2
```

## ディレクトリ構成
```
NPG
├── jikken-40sim
│   ├── D=0.1-19step
│   │   ├── case1.ipynb
│   │   ├── case2.ipynb
│   │   ├── ...
│   │   ├── case40.ipynb
│   ├── ...
│   ├── D=0.05-301step
│   │   ├── case1.ipynb
│   │   ├── case2.ipynb
│   │   ├── ...
│   │   ├── case40.ipynb
├── test-code
│   ├── D=0.2-T=113.ipynb
│   ├── D=0.3-T=113.ipynb
│   ├── D=0.4-T=113.ipynb
│   ├── D=0.5-T=113.ipynb
```
