# Izu-Ohsima_2019_11
2019ねん11がつ、いずおおしまきょうどううちあげじっけんの親リポジトリだよ

# 概要
最強のロケット電装のプロトタイプ。前哨戦

## コンセプト
* 信頼性のあるGSシリーズを使用した電装キャリア
* 3月大島用アビオニクスのテスト
* CANで殴る

# 構成
| 名称 | 役割 | 担当 | 備考 |
|:----:|:----:|:----:|:----:|
|[Tanba28/GS-8_Motion_Logger](https://github.com/Tanba28/GS-8_Motion_Logger)|2000Hzで6軸センサのロギング|Niwa||
|[ringo156/GS-8_ACCLRM_Board](https://github.com/ringo156/GS-8_ACCLRM_Board)|200Gレンジ加速度センサのロギング|ringo||
|[takamasavvv/RCT-X_Logger](https://github.com/takamasavvv/RCT-X-Logger)|GPSのロギング|vvv||
|[Tanba28/GS-8_Barometer](https://github.com/Tanba28/GS-8_Barometer)|気圧のロギング・頂点検知|Niwa||
|[Tanba28/GS-8_PD_Board](https://github.com/Tanba28/GS-8_PD_Board)|パラシュートの展開|Niwa||
|[takamasavvv/RCT-X-Telemetry](https://github.com/takamasavvv/RCT-X-Telemetry)|ダウンリンク|vvv||
|[Tanba28/GS-8_PM_Board](https://github.com/Tanba28/GS-8_PM_Board)|電源管理・アンビリカル・OBC|Niwa||
|https://github.com/takamasavvv/RCT-G-MainStation|ダウンリンクデータの可視化|vvv||

 * すべてのモジュールをCANで統合
 * CANバスに流れてくるデータをOBCが記録
 * CANバスに流れてくるデータをダウンリンク
  
# TODOリスト
- [ ] TODOリストを作る
