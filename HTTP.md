### URL
- URIの一種
- URIの構文

  http://www.example.com:80/path/to/myfile.html?key1=value1&key2=value2#SomewhereInTheDocument
  | プロトコル | ドメイン名 | ポート | パス | パラメータ | アンカー |
  | :-: | :-: | :-: | :-: | :-: | :-: |
  | http:// | www.example.com | :80 | path/to/myfile.html | ?key1=value1&key2=value2 | #SomewhereInTheDocument |
### HTTPリクエスト
要求の３ブロック
> 1. 最初の行は、要求メソッドの後に次の引数が続きます。
>    - 文書のパス、すなわち絶対 URL からプロトコル名とドメイン名を除いたものです。
>    - HTTP プロトコルのバージョン。
> 2. 後続の行は HTTP ヘッダーであり、サーバーに対してどの種類 (例えば、言語や MIME タイプ) のデータが適切かを示す情報や、サーバーの動作を変える (例えば、すでにキャッシュされている場合は回答を送信しない) データを与えます。これらの HTTP ヘッダーは空行で終わるブロックを構成します。
> 3. 最後のブロックは省略可能なデータブロックで、主に POST メソッドで使用される追加のデータを含みます。
例１
> GET / HTTP/1.1
> Host: developer.mozilla.org
> Accept-Language: fr
例２
> POST /contact_form.php HTTP/1.1
> Host: developer.mozilla.org
> Content-Length: 64
> Content-Type: application/x-www-form-urlencoded
> 
> name=Joe%20User&request=Send%20me%20one%20of%20your%20catalogue
要求メソッド（HTTP 動詞）
> - GET メソッドは、指定したリソースのデータを要求します。 GET を使用する要求は、データの取り込みに限ります。
> - POST メソッドはサーバーにデータを送信しますので、データの状態を変更できます。これは、 HTML フォーム用によく使用されるメソッドです。
### リクエストヘッダー（メッセージヘッダー）
### リクエストボディ（メッセージボディ）
### HTTPレスポンス
### レスポンスヘッダー（メッセージヘッダー）
### レスポンスボディ（メッセージボディ）
### ブラウザ
### サーバ
### メソッド
### GET
### POST
### ステータスコード
