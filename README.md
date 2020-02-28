# create.js - FlowChart

Canvasに、create.jsを使ってフローチャートを書いてみました。

## ローカル環境
dockerでnginxを起動してwebサーバを構築します。
```
$ docker-compose build
$ docker-compose up -d
```

## 動作確認
ブラウザで閲覧してみる。
```
$ open http://localhost:8080
```

## 参考サイト
- [CreateJSとは](https://ics.media/tutorial-createjs/basic/)
- [公式ドキュメント(英語)](https://createjs.com/docs/easeljs/classes/Graphics.html)
- [フローチャートが作れるミニマルなJavaScriptライブラリ「Flowy」](https://itnews.org/news_contents/oss-flowy)
- [flowchart.js - SVGのフローチャートを生成するJavaScriptライブラリ](https://www.moongift.jp/2015/10/flowchart-js-svg%E3%81%AE%E3%83%95%E3%83%AD%E3%83%BC%E3%83%81%E3%83%A3%E3%83%BC%E3%83%88%E3%82%92%E7%94%9F%E6%88%90%E3%81%99%E3%82%8Bjavascript%E3%83%A9%E3%82%A4%E3%83%96%E3%83%A9%E3%83%AA/)
- [GoJS](https://www.nwoods.com/products/gojs/)
- [プロ直伝 業務システム開発のためのHTML5攻略ガイド](https://www.amazon.co.jp/%E3%83%97%E3%83%AD%E7%9B%B4%E4%BC%9D-%E6%A5%AD%E5%8B%99%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E9%96%8B%E7%99%BA%E3%81%AE%E3%81%9F%E3%82%81%E3%81%AEHTML5%E6%94%BB%E7%95%A5%E3%82%AC%E3%82%A4%E3%83%89-%E6%96%B0%E6%97%A5%E9%89%84%E4%BD%8F%E9%87%91%E3%82%BD%E3%83%AA%E3%83%A5%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%82%BA%E6%A0%AA%E5%BC%8F%E4%BC%9A%E7%A4%BE-%E3%82%B7%E3%82%B9%E3%83%86%E3%83%A0%E7%A0%94%E7%A9%B6%E9%96%8B%E7%99%BA%E3%82%BB%E3%83%B3%E3%82%BF%E3%83%BC-hifive%E9%96%8B%E7%99%BA%E3%83%81%E3%83%BC%E3%83%A0/dp/482223763X)
- [CreateJSで、複数の点を滑らかな曲線でつなぐ](https://www.streakimage.jp/createjs/wave_line/index.html)
- [HTML5のcanvasに直線や曲線でパスを描画する](https://kudox.jp/html-css/html5-canvas-path)

以上
