### **📌 WPA、WPA2、WPA3とは？（無線LANセキュリティ）**

WPA（Wi-Fi Protected Access）は、無線LAN（Wi-Fi）のセキュリティを強化するための規格です。

初期の **WEP（Wired Equivalent Privacy）** の脆弱性を補うために開発され、現在では **WPA3** まで進化しています。


### **📌 無線LANのセキュリティ規格の比較表**

| **規格**  | **登場年** | **主な暗号化方式** | **特徴** | **脆弱性** |
|-----------|---------|----------------|------------|------------|
| **WEP（Wired Equivalent Privacy）** | 1999年 | RC4（固定キー） | 初期のWi-Fi暗号方式（40bit/104bit） | **脆弱性多数・すぐに破られる** |
| **WPA（Wi-Fi Protected Access）** | 2003年 | TKIP（一時鍵を使う） | WEPの改善版・一時鍵を使い暗号強化 | TKIPも脆弱性が発見されている |
| **WPA2** | 2004年 | AES（CCMP） | 強力なAES暗号方式を採用、現在も一般的 | KRACK攻撃のリスクあり |
| **WPA3** | 2018年 | SAE（Simultaneous Authentication of Equals） | パスワード盗難やオフライン攻撃に強い | 新技術なので対応機器が少ない |



### **📌 WPAの周辺知識**
#### 🔹 **WPAのセキュリティ方式**
- **TKIP（Temporal Key Integrity Protocol）**：WEPの弱点を補うための一時的な対策（WPAで採用）。
- **AES（Advanced Encryption Standard）**：強力な暗号方式。WPA2で採用。

1. TKIP（旧世代の暗号化技術）
WEPの弱点（固定キー）を改善
パケットごとに異なる暗号鍵を生成（動的鍵交換）
しかし、現在は 脆弱性が発見され非推奨

2. AES（強力な暗号化技術）
政府レベルの暗号標準
**CCMP（Counter Mode Cipher Block Chaining Message Authentication Code Protocol）**と組み合わせて使用
現在の主流技術（WPA2・WPA3で採用）

3. SAE（WPA3の新しい認証方式）
辞書攻撃を防ぐ強固なパスワード認証
パスワードを直接送信せず、より安全に鍵を交換（オフライン攻撃に強い）
WPA3で採用


#### 🔹 **WPAの認証モード**
1. **パーソナルモード（PSK：Pre-Shared Key）**  
   - 事前に共有したパスワードで接続  
   - 家庭用Wi-Fiで一般的  
2. **エンタープライズモード（EAP：Extensible Authentication Protocol）**  
   - 認証サーバー（RADIUS）を使う  
   - 企業や大学などで利用される  



### **📌 WPA3の進化ポイント**
1. **SAE（Simultaneous Authentication of Equals）**
   - **辞書攻撃（パスワード総当たり攻撃）を防ぐ**
   - WPA2のPSK方式の脆弱性を改善
2. **192-bit セキュリティスイート**
   - 重要なネットワーク向けに **更に強化された暗号化**
3. **オープンWi-Fiの暗号化**
   - **カフェなどの無料Wi-Fiでもデータを暗号化**（OWE: Opportunistic Wireless Encryption）


### **📌 WPAの脆弱性**
| **攻撃手法** | **影響を受ける規格** | **概要** | **対策** |
|-------------|----------------|---------|--------|
| **WEPキー解読** | WEP | WEPの脆弱性を利用し、短時間でキーを解読 | **WEPは使用しない** |
| **KRACK攻撃** | WPA2 | 通信を傍受し、鍵を再利用させる攻撃 | **WPA3を使用 or WPA2でパッチ適用** |
| **辞書攻撃** | WPA2-PSK | 簡単なパスワードを総当たり攻撃 | **長く複雑なパスワードを設定** |



### **📌 まとめ**
- **WEPは危険！もう使わない！**
- **WPA2は現在も一般的だが、KRACK攻撃には注意**
- **WPA3は最新で安全だが、まだ普及が進行中**
- **Wi-Fiを安全に使うには、AES＋長いパスワードを設定するのが大事**

WPA3対応機器が増えるまでは **WPA2 + 強いパスワード（AES-CCMP）** が現実的な選択肢！💡


### **📌 WAP（Wireless Application Protocol）はWPAとは別物！**  


### **📌 WAPとは？**
- **WAP（Wireless Application Protocol）** は、**携帯電話やPHSなどのモバイル端末向けにインターネットを利用するための通信プロトコル** です。
- 1990年代後半～2000年代前半にかけて、**ガラケー（フィーチャーフォン）向けのウェブ通信** に使われていました。
- **「iモード」や「EZweb」「Vodafone live!」など** で利用され、軽量なテキストベースのサイトを表示するために最適化されていました。

🔹 **特徴**
- モバイル端末向けに軽量な通信が可能
- HTMLの代わりに「**WML（Wireless Markup Language）**」を使用
- 3G以前の時代に多く使われたが、**スマートフォンの普及とともに廃れた**

---

### **📌 WPAとの違い**
| **項目** | **WAP（Wireless Application Protocol）** | **WPA（Wi-Fi Protected Access）** |
|---------|--------------------------------|--------------------------------|
| **用途** | モバイル端末向けのインターネット通信 | Wi-Fiのセキュリティ強化 |
| **対象** | 携帯電話（フィーチャーフォン時代） | 無線LAN（Wi-Fi） |
| **主な技術** | WML（Wireless Markup Language） | TKIP、AES、SAE（暗号化技術） |
| **現状** | ほぼ使われていない | 現在もWi-Fiで使用中 |
