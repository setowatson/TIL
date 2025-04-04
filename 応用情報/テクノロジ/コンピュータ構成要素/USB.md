

| 転送方法 | 特徴 | 具体的な用途 | データ転送の優先度 | 速度の安定性 |
|---------|------|------------|--------------|------------|
| **制御転送・コントロール転送** | デバイスの設定や制御情報をやり取りする | USBデバイスの認識、設定変更、コマンド送信 | **最優先** | 安定している |
| **割り込み転送・インタラプト転送** | 少量のデータを定期的に高速転送 | キーボード・マウスの入力、ジョイスティック | **高** | 安定している |
| **等時転送・アイソクロナス転送** | 一定の速度で連続的にデータを転送（エラー訂正なし） | 音声・動画ストリーミング、USBマイク | **中** | 一定（エラー発生時の再送なし） |
| **バルク転送** | 大容量データを効率的に転送（空き帯域を使用） | 外付けHDD・USBメモリのデータ転送 | **低** | 不安定（帯域の空き次第） |

### まとめ  
- **制御転送**：USBデバイスの設定や管理用（最優先）  
- **割り込み転送**：キーボードやマウスなどの即時反応が求められるデバイス用  
- **等時転送**：音声や映像などリアルタイム性が重要なデータ用（エラー訂正なし）  
- **バルク転送**：大容量データの転送（空き帯域次第で速度が変わる）


<img width="604" alt="image" src="https://github.com/user-attachments/assets/f971c22a-c131-41c1-8913-ed4c95fe6bb1" />
