# ロジスティック回帰分析を行うwebアプリ
webに公開している url: https://hirano.pythonanywhere.com/logit_app/index/

css無料版であるためcssは反映できていないので反映されているバージョンを見たい場合はファイルをダウンロードの上以下の詳細をインストールの上ご確認ください。

# webアプリの詳細
pythonのバージョン: 3.10
webフレームワーク:Django

使用しているライブラリー
pandas,statsmodels

# このアプリで出来ること
ロジスティック回帰分析を行える。

# ロジスティック回帰分析とは
　ロジスティック回帰分析は、いくつかの要因（説明変数）から「はい」(1に置き換える)か「いいえ」(0に置き換える)のように2値の結果（目的変数）が起こる確率を説明・予測することができる統計手法です。例えば、以下のような場面で使われます。

・商品の購買予測

　顧客の年齢、購買履歴、クリック履歴などの要因(説明変数)から、「購入した」、「購入してない」(目的変数)のデータを用いて説明変数が目的変数にどれだけ関係しているか、またどれくらい影響力があるか調べることができる。

# 今後追加したいこと

　まず選択するどのような分析手法を用いるか選択してロジスティック回帰分析以外にも重回帰分析、主成分分析、ランダムフォレストなどやその予測値まで入れていきたい。
