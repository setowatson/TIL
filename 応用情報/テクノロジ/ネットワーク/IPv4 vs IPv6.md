

| **特徴**                     | **IPv4 (Internet Protocol version 4)**                                                                                         | **IPv6 (Internet Protocol version 6)**                                                                                     |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| **アドレス長**               | 32ビット                                                                                                                     | 128ビット                                                                                                                 |
| **アドレス形式**             | 4つの10進数で表現（例：192.168.1.1）                                                                                           | 8つの16進数で表現（例：2001:0db8:85a3:0000:0000:8a2e:0370:7334）                                                           |
| **アドレスの総数**           | 約43億（2^32）                                                                                                                | 約340澗（2^128）                                                                                                           |
| **アドレス空間**             | 限られたアドレス空間であり、特にIPv4アドレスの枯渇が問題となっている                                                         | 広大なアドレス空間を提供し、将来的なアドレスの枯渇問題を解決                                                             |
| **アドレスの設定方法**       | 手動またはDHCP（Dynamic Host Configuration Protocol）で設定                                                                 | 自動設定（SLAAC: Stateless Address Autoconfiguration）または手動で設定可能                                               |
| **ネットワーク構成**         | NAT（Network Address Translation）を使用して、プライベートネットワークとインターネットを接続                                                                 | NAT不要。IPアドレスが十分に広いため、各デバイスに固有のグローバルIPアドレスを割り当て可能                                    |
| **ヘッダーのサイズ**         | 20バイト（固定）                                                                                                               | 40バイト（固定）                                                                                                           |
| **エラーチェック**           | チェックサムをヘッダ部に含む                                                                                                   | チェックサムなし（通信がより高速）                                                                                           |
| **セキュリティ**             | IPsecをオプションでサポート                                                                                                   | IPsecを必須でサポート（デフォルトでセキュリティ機能が組み込まれている）                                                     |
| **ルーティング**             | 複雑なルーティングとネットワークアドレス変換（NAT）を使用することが多い                                                        | より効率的なルーティングが可能。ヘッダーの簡素化により、ルーターの処理が高速化される                                        |
| **フラグメンテーション**     | 送信元と中継ルーターによってフラグメント可能                                                                                     | 送信元だけがフラグメントを担当（中継ルーターではフラグメントしない）                                                         |
| **IPv4アドレスの分類**       | クラスA、B、C、D、Eなどに分けられており、使用するアドレスが限られている                                                         | アドレスの分類はなく、全てのアドレスが平等に使用可能。特定のアドレス範囲が予約されている                                     |
| **適用範囲**                 | 現在も広く使用されており、ほとんどのインターネット接続はIPv4を使用                                                                | 新しい技術であり、徐々に普及が進んでいるが、IPv4と併用されることが多い                                                      |
| **互換性**                   | IPv6との直接的な互換性はない                                                                                                   | IPv4との直接的な互換性はないが、トンネリングやデュアルスタック（IPv4+IPv6）によって共存が可能                                 |

### 主な違い
1. **アドレス長**:
   - **IPv4**は32ビットで、最大約43億個のアドレスを提供します。現在、IPv4アドレスは枯渇しており、新しいデバイスの接続に困難をきたすことがあります。
   - **IPv6**は128ビットで、非常に多くのアドレス（340澗個）を提供でき、将来的なアドレス枯渇の問題を解決します。

2. **アドレス空間とアドレス設定**:
   - **IPv4**はアドレスが不足しがちで、NAT（ネットワークアドレス変換）を利用して複数のデバイスが1つのIPアドレスを共有することが多いです。
   - **IPv6**は十分に広いアドレス空間を持ち、各デバイスに固有のグローバルIPアドレスを割り当てることができます。

3. **セキュリティ**:
   - **IPv4**ではセキュリティ機能（IPsec）はオプション
   - **IPv6**ではデフォルトでIPsecがサポートされ、セキュリティ機能が強化されています。

4. **ルーティングとフラグメンテーション**:
   - **IPv4**はルーティングが複雑で、中継ルーターでフラグメント処理を行うことがあります。
   - **IPv6**はルーティングが効率的で、フラグメントは送信元デバイスでのみ行い、ルーターはフラグメント処理をしません。
