
| 規格 | 名称 | 概要 | 代表的な技術・特徴 |
|------|------|------|----------------|
| **IEEE 802.1** | LANアーキテクチャ | LANの標準規格の管理全般 | VLAN（802.1Q）、スパニングツリープロトコル（STP, 802.1D） |
| **IEEE 802.2** | LLC（Logical Link Control） | データリンク層の上位サブレイヤー | フレームのエラーチェック、フロー制御 |
| **IEEE 802.3** | 有線LAN（Ethernet） | 一般的な有線LAN規格 | 10BASE-T, 100BASE-TX, 1000BASE-T（ギガビットEthernet） |
| **IEEE 802.5** | トークンリング | IBMが開発したリング型ネットワーク | トークンパッシング方式（現在ほぼ使用されていない） |
| **IEEE 802.11** | 無線LAN（Wi-Fi） | 無線通信の規格 | 802.11a/b/g/n/ac/ax（Wi-Fi 6） |
| **IEEE 802.15** | PAN（Personal Area Network） | 近距離無線通信 | Bluetooth（802.15.1）、ZigBee（802.15.4） |
| **IEEE 802.16** | 無線MAN（Wireless MAN） | 広域無線通信技術 | WiMAX（Worldwide Interoperability for Microwave Access） |

### **特に覚えるべきポイント**
1. **IEEE 802.3（Ethernet）**：有線LANの標準規格  
   - **10BASE-T**（10Mbps）、**100BASE-TX**（100Mbps）、**1000BASE-T**（1Gbps）  
   - CSMA/CD（Carrier Sense Multiple Access with Collision Detection）を使用（現在はほぼフルデュプレックス通信で不要）  

2. **IEEE 802.11（Wi-Fi）**：無線LANの標準規格  
   - **802.11a**（5GHz, 最大54Mbps）  
   - **802.11b**（2.4GHz, 最大11Mbps）  
   - **802.11g**（2.4GHz, 最大54Mbps）  
   - **802.11n**（2.4GHz/5GHz, 最大600Mbps, MIMO対応）  
   - **802.11ac**（5GHz, 最大6.9Gbps, ビームフォーミング対応）  
   - **802.11ax（Wi-Fi 6）**（2.4GHz/5GHz, 最大9.6Gbps, OFDMA対応）  

3. **IEEE 802.1（LAN管理）**  
   - **802.1Q**（VLANのタグ付け）  
   - **802.1D**（スパニングツリープロトコル、ループ防止）  

4. **IEEE 802.15（Bluetooth, ZigBee）**  
   - **802.15.1（Bluetooth）**：短距離通信（マウス、イヤホンなど）  
   - **802.15.4（ZigBee）**：低消費電力、IoT向け  

### **試験対策ポイント**
- **有線LAN → IEEE 802.3（Ethernet）**  
- **無線LAN → IEEE 802.11（Wi-Fi、特にn, ac, ax）**  
- **VLAN → IEEE 802.1Q**  
- **Bluetooth → IEEE 802.15.1**  
