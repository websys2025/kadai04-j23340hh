## 自動販売機（オブジェクト、DOM、イベント処理）のミニレポート
### Q4-1. Itemクラスのメソッドについて説明せよ。
* showItemListがクラスメソッドである理由を考察せよ。
  * クラスレベルで管理されるものとして扱いたいため。また、商品ごとにオブジェクトがあると一括管理できないため。
* buyItemがインスタンスメソッドである理由を考察せよ。
  * 在庫は商品ごとに独立しているため
### Q4-2. 商品の購入ボタンをクリックすると、どのような処理でセルの値が減少するか説明せよ。
* 購入された商品の在庫数のセルをどのようにして特定するのか説明せよ。
  * id属性を利用してgetElementById()で特定する。
* 特定したセルの値をどのように変更するのか説明せよ。
  * 特定したDOM要素のinnerHTMLプロパティを使って変更する。
### Q4-3. 感想
* 今回の課題で苦労したこと
  * クラスメソッドとインスタンスメソッドの違いや、それぞれの適切な使用場面を理解することに苦労しました。特に、クラスメソッドがインスタンスに依存しない処理を行う点を意識するのが難しかったです。
* 演習を通して理解できたこと
  * クラスを使用することで、商品データの構造化と処理の整理が容易になることを実感しました。
* この自動販売機プログラムの追加機能や課題など
  * UIの改善
