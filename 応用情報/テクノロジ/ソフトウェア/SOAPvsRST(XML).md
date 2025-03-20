
# SOAPとRESTの違い

(Simple Object AccessProtocol)
SOAP は、XML ベースのプロトコルで、Webサービス間の通信に使用されます。


(Representational StateTransfer)
REST は、HTTP の仕組みを活用したAPI設計のスタイルで、Web サービス間の通信に使わ

| 項目            | SOAP                         | REST                          |
|---------------|----------------------------|------------------------------|
| **プロトコル**   | 独自（HTTP, SMTP, TCP など） | HTTP                          |
| **データフォーマット** | XML のみ                     | JSON, XML, YAML など           |
| **設計の柔軟性**   | 固定的（WSDL で定義）         | 柔軟（リソース指向）           |
| **処理の軽量性**   | 重い（XML パースが必要）      | 軽い（JSON を使えばシンプル）  |
| **セキュリティ**   | WS-Security による強固なセキュリティ | HTTPS + OAuth など          |
| **状態管理**     | ステートフルも可能            | ステートレス                  |
| **主な用途**     | 企業システム、金融、決済サービス | Web API、マイクロサービス    |
