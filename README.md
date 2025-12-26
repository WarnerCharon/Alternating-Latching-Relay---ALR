
# Alternating-Latching-Relay---ALR

Alternating-Latching-Relay

Sequential Alternating Latching Relay Module

📌 Module Description | 模組說明
中文版本

Alternating-Latching-Relay 模組 提供 依序循環的交替切換輸出功能（Sequential Alternating Output）。
在持續供電狀態下，外部觸點或瞬時控制脈衝每觸發一次，輸出狀態即 依固定順序向下一狀態循環切換，並透過 電磁繼電器所形成的自保持記憶機制 將該狀態穩定保持，直到下一次觸發為止。

其動作行為在功能上等同於 電氣化的棘輪式切換機制，但以繼電器邏輯完成狀態記憶與交替控制。

本模組可 取代傳統機械式棘輪電驛（Mechanical Ratchet Relay），在不改變控制邏輯的前提下，提供清楚、可預期的交替輸出行為，適合整合於現代電氣控制與自動化系統中。

English Version

The Alternating-Latching-Relay Module provides Sequential Alternating Output functionality.
Under continuous power supply conditions, each trigger from an external contact or momentary control pulse causes the output state to cycle sequentially to the next state in a fixed order. The state is then stably maintained through a self-holding memory mechanism formed by electromagnetic relays until the next trigger occurs.

Its operational behavior is functionally equivalent to an electrified ratchet switching mechanism, but achieves state memory and alternating control through relay logic.

This module can replace traditional Mechanical Ratchet Relays while providing clear and predictable alternating output behavior without changing the control logic, making it suitable for integration into modern electrical control and automation systems.

⚙️ Technical Specifications | 技術規格
項目 / Parameter	規格 / Specification
工作電壓 / Operating Voltage	DC 12V
觸發方式 / Trigger Method	瞬時觸點正電壓 / Momentary contact positive voltage
脈衝寬度 / Pulse Width	≥ 15 ms
記憶保持 / Memory Retention	觸發斷路後狀態保持，下一次觸發時交替切換
輸出形式 / Output Form	一組 NO / NC 接點（SPDT）
接點容量 / Contact Rating	5A（阻性負載 / Resistive Load）
觸發輸入型態 / Trigger Input Type	正電壓觸發 / Positive voltage trigger
反應時間 / Response Time	機械轉換時間（狀態切換間隔）
🏭 Application Fields | 應用領域

本模組特別適合應用於 需要交替、輪替或循環控制的設備與系統，包括但不限於：

Industrial Applications | 工業應用

製程設備狀態交替

設備模式循環

輸送系統與機械模組的順序控制

Agricultural Applications | 農業應用

灌溉系統交替控制

通風設備、水循環系統

分區設備輪替運轉

Wastewater & Water Treatment Applications | 污水與水處理

污水幫浦交替運轉（Duty / Standby Alternation）

集水井雙幫浦輪替

排水與回流系統循環控制

平衡設備運轉負載

Home & Building Applications | 家庭與建築設備

照明系統

風扇、水泵

排風與循環設備

Motor & Pump Applications | 馬達與幫浦

馬達交替控制

幫浦輪替運轉

將瞬時控制訊號轉換為 穩定、可保持、可循環的輸出狀態

⭐ Core Features | 核心特性

依序循環的交替切換輸出

電磁繼電器自保持記憶機制

短脈衝觸發（≥15ms）

可取代機械式棘輪電驛

適用於工業、農業、水處理與建築電氣控制

透過 循環交替與繼電器記憶保持功能，本模組可將短暫的控制輸入轉化為 穩定、連續且可重複的輸出狀態序列。

🔁 Comparison with Traditional Solutions
與傳統方案比較
比較項目	Mechanical Ratchet Relay	Alternating-Latching-Relay Module
壽命 / Lifespan	機械磨損，壽命受限	電氣控制，壽命更長
維護 / Maintenance	維護困難，需拆卸	模組化設計，易於更換
動作確定性 / Action Certainty	可能卡死或跳步	清楚可預期的狀態循環
觸發方式 / Trigger Method	機械力驅動	電氣訊號觸發
整合性 / Integration	獨立機械裝置	易整合於現代控制系統
成本 / Cost	較高	經濟實惠
🔌 Wiring Diagram Reference | 接線示意
Basic Wiring | 基本接線

Power Input: DC 12V (+ / −)

Trigger Input: Positive voltage pulse (≥15ms)

Output Contacts: COM / NO / NC (SPDT)

Typical Application | 典型應用
Trigger Source
   ↓
Trigger Input
   ↓
Alternating-Latching-Relay Module
   ↓
Output Contacts (COM / NO / NC)
   ↓
Load (Motor / Pump / Equipment)

⚠️ Important Notes | 注意事項

電源要求 / Power Requirements
確保提供穩定的 DC 12V 電源

觸發訊號 / Trigger Signal
脈衝寬度必須 ≥15ms

接點容量 / Contact Rating
負載電流不應超過 5A（阻性負載）

感性負載 / Inductive Loads
控制馬達或線圈時建議加裝突波吸收器

狀態記憶 / State Memory
模組斷電後將失去狀態記憶，重新上電需重新初始化
模組斷電後將失去狀態記憶，重新上電後需重新初始化 / Module loses state memory after power loss, requires reinitialization after power-on
