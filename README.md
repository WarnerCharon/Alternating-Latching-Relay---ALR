
# Alternating-Latching-Relay---ALR

The Alternating-Latching-Relay Module provides Sequential Alternating Output functionality. Under continuous power supply conditions, each trigger from an external contact or momentary control pulse causes the output state to cycle sequentially to the next state in a fixed order. The state is then stably maintained through a self-holding memory mechanism formed by electromagnetic relays until the next trigger occurs. Its operational behavior is functionally equivalent to an electrified ratchet switching mechanism, but achieves state memory and alternating control through relay logic.
This module can replace traditional Mechanical Ratchet Relays while providing clear and predictable alternating output behavior without changing the control logic, making it suitable for integration into modern electrical control and automation systems.
Technical Specifications
ParameterSpecificationOperating VoltageDC 12VTrigger MethodMomentary contact positive voltage, pulse width ≥15msMemory RetentionState maintained after trigger release, alternates on next triggerOutput FormOne set of NO/NC contacts (SPDT)Contact Rating5A (resistive load)Trigger Input TypePositive voltage triggerResponse TimeMechanical switching time (interval between state transitions)
Application Fields
This module is particularly suitable for equipment and systems requiring alternating, rotating, or cyclic control, including but not limited to:
Industrial Applications
Process equipment state alternation, equipment mode cycling, sequential control of conveyor systems and mechanical modules.
Agricultural Applications
Irrigation systems, ventilation equipment, water circulation and zone equipment alternating operation control.
Wastewater & Water Treatment Applications
Wastewater pump alternating operation (Duty/Standby Alternation), dual pump rotation in sump wells, drainage and recirculation system cyclic control, ensuring balanced equipment operation load.
Home & Building Applications
Lighting, fans, water pumps, exhaust equipment, and other control scenarios requiring cyclic or alternating output.
Motor & Pump Applications
Serves as an alternating control component for motors and pumps, converting momentary control signals into stable, maintainable, and cyclable output states, suitable for installation in control boxes and automation panels.
Core Features
Through cyclic alternation and relay memory holding functions, this module converts brief control inputs (≥15ms) into stable, continuous, and repeatable output state sequences, widely applicable in industrial, agricultural, water treatment, and building electrical control systems.


Alternating-Latching-Relay 模組 提供 依序循環的交替切換輸出功能（Sequential Alternating Output）。在持續供電狀態下，外部觸點或瞬時控制脈衝每觸發一次，輸出狀態即 依固定順序向下一狀態循環切換，並透過 電磁繼電器所形成的自保持記憶機制 將該狀態穩定保持，直到下一次觸發為止。其動作行為在功能上等同於 電氣化的棘輪式切換機制，但以繼電器邏輯完成狀態記憶與交替控制。
此模組可 取代傳統機械式棘輪電驛（Mechanical Ratchet Relay），在不改變控制邏輯的前提下，提供清楚、可預期的交替輸出行為，適合整合於現代電氣控制與自動化系統中。
技術規格
項目規格工作電壓DC 12V觸發方式瞬時觸點正電壓，脈衝寬度 ≥15ms記憶保持觸發斷路後狀態保持，下一次觸發時交替切換輸出形式一組常開/常閉接點（SPDT）接點容量5A (阻性負載)觸發輸入型態正電壓觸發反應時間機械轉換時間（兩組狀態切換間隔）
應用領域
本模組特別適合應用於 需要交替、輪替或循環控制的設備與系統，包括但不限於：
工業應用（Industrial Applications）
製程設備狀態交替、設備模式循環、輸送系統與機械模組的順序控制。
農業應用（Agricultural Applications）
灌溉系統、通風設備、水循環與分區設備的交替運轉控制。
污水與水處理應用（Wastewater & Water Treatment Applications）
污水幫浦交替運轉（Duty/Standby Alternation）、集水井雙幫浦輪替、排水與回流系統的循環控制，確保設備運轉負載均衡。
家庭與建築設備（Home & Building Applications）
照明、風扇、水泵、排風設備等需要循環或交替輸出的控制場景。
馬達與幫浦應用（Motor & Pump Applications）
作為馬達與幫浦的交替控制元件，將瞬時控制訊號轉換為 穩定、可保持、可循環的輸出狀態，適合安裝於控制箱與自動化盤內。
核心特性
透過 循環交替與繼電器記憶保持功能，本模組能將短暫的控制輸入（≥15ms）轉化為 穩定、連續且可重複的輸出狀態序列，廣泛應用於工業、農業、水處理與建築電氣控制系統。

與傳統方案比較
Comparison with Traditional Solutions
比較項目機械式棘輪電驛Alternating-Latching-Relay 模組ComparisonMechanical Ratchet RelayAlternating-Latching-Relay Module壽命 / Lifespan機械磨損，壽命受限 / Limited by mechanical wear電氣控制，壽命更長 / Longer lifespan with electrical control維護 / Maintenance維護困難，需拆卸檢修 / Difficult, requires disassembly模組化設計，易於更換 / Modular design, easy replacement動作確定性 / Action Certainty可能卡死或跳步 / May jam or skip steps清楚可預期的狀態循環 / Clear and predictable state cycling觸發方式 / Trigger Method機械力驅動 / Mechanical force driven電氣訊號觸發 / Electrical signal triggered整合性 / Integration獨立機械裝置 / Standalone mechanical device易整合於現代控制系統 / Easy integration with modern control systems成本 / Cost較高 / Higher經濟實惠 / Cost-effective

接線示意
Wiring Diagram Reference
基本接線
Basic Wiring:

Power Input: DC 12V (+/-)
Trigger Input: Positive voltage pulse (≥15ms)
Output Contacts: COM, NO, NC (SPDT configuration)

典型應用
Typical Application:
觸發源 → 觸發輸入 → 模組處理 → 輸出接點 → 負載設備
Trigger → Trigger Input → Module → Output Contacts → Load

注意事項
Important Notes

電源要求 / Power Requirements:
確保提供穩定的 DC 12V 電源 / Ensure stable DC 12V power supply
觸發訊號 / Trigger Signal:
脈衝寬度必須 ≥15ms，過短可能無法正確觸發 / Pulse width must be ≥15ms, shorter pulses may fail to trigger
接點容量 / Contact Rating:
負載電流不應超過 5A（阻性負載）/ Load current should not exceed 5A (resistive load)
感性負載 / Inductive Loads:
控制馬達或線圈時建議加裝突波吸收器 / Surge absorber recommended when controlling motors or coils
狀態記憶 / State Memory:
模組斷電後將失去狀態記憶，重新上電後需重新初始化 / Module loses state memory after power loss, requires reinitialization after power-on
