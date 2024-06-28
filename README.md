# gsi-dem-10b-terrain-rgb
このリポジトリでは、国土地理院の標高タイルをMapLibre GL JSで利用可能なTerrain-RGB形式の標高タイルに変換したデータを公開しています。
なお、本データの利用については、[国土地理院コンテンツ利用規約](https://www.gsi.go.jp/kikakuchousei/kikakuchousei40182.html)に従うものとします。

## 標高タイルについて
標高タイルは、DEM10B PNG形式の標高タイルを使用しています。

標高タイル（基盤地図情報数値標高モデル）  
https://maps.gsi.go.jp/development/ichiran.html#dem

## 標高タイルの変換スクリプト
https://github.com/shi-works/tile-gsi-dem

## Terrain-RGB形式の標高タイル
`https://xs489works.xsrv.jp/raster-tiles/gsi/gsi-dem-terrain-rgb/{z}/{x}/{y}.png`  
(tileSize: 256px zoomLevel: 0-14)

## 上記のTerrain-RGB形式の標高タイルを用いたデモサイト
https://shi-works.github.io/gsi-dem-10b-terrain-rgb/

![image](https://github.com/shi-works/gsi-dem-10b-terrain-rgb/assets/71203808/f3d1c518-6f7b-4fcf-8760-f8d26f15070a)
