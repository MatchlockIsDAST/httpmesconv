# HTTPMessageConverter
Goのnet/http系を操作する際に使用する小物集
## tostring
net/httpのRequestやResponseを文字列化する際に利用する。

httputilは自分の想像していた動きとは少し異なっていたので自分で作って自分で使います。
## stringto
string型のHTTP Messageをbet/httpのRequestやResponseに変換する。

BurpSuiteなどのようなリアルタイムにメッセージを書き換えるような動作の際に使うといいです。

ただ、文字列型のHTTP Messageではhttpsなどのアプリケーション層以外の情報を持ち合わせていないので文字列化前のnet/httpを保持し一部流用することをオススメします。

## inmemory
テスト用のデータを抱きかかえています。それ以上でも以下でもない。
