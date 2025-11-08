# 中国産業発展可視化システム
## プロジェクト概要

本プロジェクトは、D3.jsやEchartsなどの可視化フレームワークを活用し、中国の三大産業（農業・工業・第三産業）の発展状況をインタラクティブに可視化するWebシステムです。
ユーザーは平行座標系、多次元円グラフ、地図クリックイベントなどを通じて、データ探索・分析を直感的に行うことができます。
HTML・CSS・JavaScriptを用いて開発され、GeoJSON/TopoJSONによる地理情報表示や動的データ更新、フィルタリング機能も実装しています。

---
## ファイル構成
```text
Industry-Dashboard/
│
├── index.html                 # メインページ
├── README.md                  # プロジェクト説明（このファイル）
│
├── css/                       # スタイルシート
│   ├── style.css              # 全体スタイル
│   ├── d3-tip.css             # D3ツールチップ用スタイル
│   └── earth.css              # 地図表示用スタイル
│
├── js/                        # JavaScriptスクリプト
│   ├── rem.js                 # レスポンシブデザイン対応
│   ├── d3.js                  # D3.jsライブラリ
│   ├── d3-geo-projection.min.js  # 地理座標投影用ライブラリ
│   ├── d3-v6-tip.js           # D3ツールチッププラグイン
│   ├── topojson.min.js        # TopoJSONライブラリ
│   └── china.json             # 中国地図データ
│
└── json/                      # 統計データ
    ├── 第三産業.json          # 第三産業データ
    ├── 工業.json              # 工業データ
    ├── 建筑业.json            # 建設業データ
    └── 农业.json              # 農業データ
```

- URL：https://ichimeikyou.github.io/Industry-Dashboard/
- 最適な閲覧体験のため、ブラウザのズーム率を 75% に設定することを推奨します。


# China Industry Development Visualization System

## Project Overview
This project is a web-based system that visualizes the development of China's three major industries (Agriculture, Industry, and Tertiary Industry) using visualization frameworks such as D3.js and Echarts.
Users can interactively explore and analyze data through parallel coordinates, multidimensional pie charts, and clickable maps.
Developed with HTML, CSS, and JavaScript, the system integrates multiple statistical data sources, supports dynamic updates, geographic visualization via GeoJSON / TopoJSON, and filtering functionalities.

---

## File Structure
```text
Industry-Dashboard/
│
├── index.html                 # Main entry page, loads all CSS and JS files, displays the visualization interface
├── README.md                  # Project description file, includes features and file structure
│
├── css/                       # Folder containing stylesheet files
│   ├── style.css              # Global styles, including page layout and common UI styling
│   ├── d3-tip.css             # Styles for D3.js tooltips
│   └── earth.css              # Styles related to map display, e.g., China map base color and borders
│
├── js/                        # JavaScript script files
│   ├── rem.js                 # Responsive layout script, adjusts root font size (rem) based on screen width
│   ├── d3.js                  # Core D3.js library for data visualization
│   ├── d3-geo-projection.min.js  # Geographic projection library, supports various map projections
│   ├── d3-v6-tip.js           # D3 tooltip plugin for showing interactive information
│   ├── topojson.min.js        # TopoJSON library for handling geographic data
│   └── china.json             # China map geographic data, used to draw the map
│
└── json/                      # Folder containing statistical data in JSON format
    ├── 第三产业.json          # Tertiary Industry statistical data
    ├── 工业.json              # Industrial sector statistical data
    ├── 建筑业.json            # Construction sector statistical data
    └── 农业.json              # Agriculture sector statistical data
```

- URL: https://ichimeikyou.github.io/Industry-Dashboard/
- Note: For the best viewing experience, it is recommended to set the browser zoom level to 75%.

# 中国三大产业可视化系统

本项目旨在通过交互式图表展示中国三大产业（农业、工业、第三产业、建筑业）的发展情况。  
系统使用 D3.js、Echarts 等可视化框架，提供平行坐标系、多维圆图以及地图点击事件等功能，  
用户可以通过网页界面探索和分析各类产业数据，实现跨平台的交互式数据分析体验。  

## 项目文件架构

```text
project-root/
│
├── index.html                 # 主入口页面，加载所有CSS和JS文件，展示可视化界面
├── README.md                  # 项目说明文件，包括功能介绍和文件结构
│
├── css/                       # 存放样式文件的文件夹
│   ├── style.css              # 全局样式，包括页面布局和通用UI样式
│   ├── d3-tip.css             # D3.js提示框样式
│   └── earth.css              # 地图相关样式，例如中国地图底色和边界
│
├── js/                        # JavaScript脚本文件
│   ├── rem.js                 # 响应式布局脚本，根据屏幕宽度调整根元素字体大小(rem)
│   ├── d3.js                  # D3.js核心库，用于数据可视化
│   ├── d3-geo-projection.min.js  # 地理投影库，支持多种地图投影方式
│   ├── d3-v6-tip.js           # D3提示框插件，用于显示交互信息
│   ├── topojson.min.js        # TopoJSON库，用于处理地理数据
│   └── china.json             # 中国地图地理数据，用于绘制地图
│
└── json/                      # 存放统计数据的JSON文件夹
    ├── 第三产业.json          # 第三产业统计数据
    ├── 工业.json              # 工业统计数据
    ├── 建筑业.json            # 建筑业统计数据
    └── 农业.json              # 农业统计数据
```
- URL: https://ichimeikyou.github.io/Industry-Dashboard/
- 提示：为获得最佳浏览体验，建议将浏览器缩放级别设置为75%。
