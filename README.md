# Alternating-Latching-Relay ALR Module

交替保持繼電器模組

[![License](https://img.shields.io/badge/License-CERN%20OHL%20S%202.0%20%7C%20AGPL%203.0%20%7C%20CC%20BY%204.0-blue)](LICENSE/)
[![OSHWA](https://img.shields.io/badge/OSHWA-Certified-green)]([https://certification.oshwa.org/US000008](https://certification.oshwa.org/tw000008.html))

## Overview 概述

The **Alternating-Latching-Relay Module** provides **Sequential Alternating Output** functionality. Under continuous power supply conditions, each trigger from an external contact or momentary control pulse causes the output state to cycle sequentially to the next state in a fixed order. The state is then stably maintained through a self-holding memory mechanism formed by electromagnetic relays until the next trigger occurs.

本 **Alternating-Latching-Relay 模組** 提供 **依序循環的交替切換輸出功能（Sequential Alternating Output）**。在持續供電狀態下，外部觸點或瞬時控制脈衝每觸發一次，輸出狀態即依固定順序向下一狀態循環切換，並透過電磁繼電器所形成的自保持記憶機制將該狀態穩定保持，直到下一次觸發為止。

## Features 核心特性

- Sequential Alternating Control 依序循環交替控制
- Self-Holding Memory Mechanism 自保持記憶機制
- Replaces Mechanical Ratchet Relays 取代傳統機械式棘輪電驛
- Pure Relay Logic Design 純繼電器邏輯設計
- Simple Integration 易於整合至現代控制系統
- Cost-Effective Solution 經濟實惠的解決方案

## Technical Specifications 技術規格

| Parameter 參數 | Specification 規格 |
|----------------|-------------------|
| Operating Voltage 工作電壓 | DC 12V |
| Trigger Method 觸發方式 | Positive voltage, pulse width ≥0.5s 正電壓，脈衝寬度 ≥0.5s |
| Memory Retention 記憶保持 | State maintained after trigger release 觸發斷路後狀態保持 |
| Output Form 輸出形式 | SPDT (1 set NO/NC contacts) 一組常開/常閉接點 |
| Contact Rating 接點容量 | 2A (resistive load) 2A（阻性負載）|
| Trigger Input Type 觸發輸入 | Positive voltage trigger 正電壓觸發 |
| Response Time 反應時間 | Mechanical switching time 機械轉換時間 |

## How It Works 工作原理

This module functions as an **electrified ratchet switching mechanism**, achieving state memory and alternating control through relay logic. Each momentary trigger pulse (≥0.5s) advances the output to the next state in sequence, which is then held until the next trigger.

本模組的動作行為等同於**電氣化的棘輪式切換機制**，以繼電器邏輯完成狀態記憶與交替控制。每次瞬時觸發脈衝（≥0.5ms）使輸出前進到下一個狀態序列，並保持該狀態直到下次觸發。

**Operation Sequence 動作序列:**
```
Trigger 1 → State A (Held) → Trigger 2 → State B (Held) → Trigger 3 → State A (Cycle Repeats)
觸發 1 → 狀態 A（保持）→ 觸發 2 → 狀態 B（保持）→ 觸發 3 → 狀態 A（循環重複）
```

## Applications 應用領域

### Industrial Applications 工業應用

Process equipment state alternation, equipment mode cycling, sequential control of conveyor systems, mechanical module control.

製程設備狀態交替、設備模式循環、輸送系統順序控制、機械模組控制。

### Agricultural Applications 農業應用

Irrigation systems, ventilation equipment alternating control, water circulation and zone equipment.

灌溉系統、通風設備交替控制、水循環與分區設備。

### Wastewater & Water Treatment 污水與水處理應用

Wastewater pump duty/standby alternation, dual pump rotation in sump wells, drainage and recirculation system control, equipment load balancing.

污水幫浦交替運轉、集水井雙幫浦輪替、排水與回流系統控制、設備運轉負載均衡。

### Home & Building Applications 家庭與建築設備

Lighting control, fan alternating operation, water pump cycling, exhaust equipment rotation.

照明控制、風扇交替運轉、水泵循環控制、排風設備輪替。

### Motor & Pump Applications 馬達與幫浦應用

Motor alternating control, pump duty cycling, control panel integration, automation system installation.

馬達交替控制、幫浦輪替運轉、控制箱整合應用、自動化系統安裝。

## Comparison with Traditional Solutions 與傳統方案比較

| Feature 特性 | Mechanical Ratchet Relay 機械式棘輪電驛 | Alternating-Latching-Relay Module 交替保持繼電器模組 |
|-------------|----------------------------------------|---------------------------------------------------|
| Lifespan 壽命 | Limited by mechanical wear 機械磨損受限 | Longer with electrical control 電氣控制壽命更長 |
| Maintenance 維護 | Difficult, requires disassembly 困難需拆卸 | Modular, easy replacement 模組化易更換 |
| Reliability 可靠性 | May jam or skip steps 可能卡死跳步 | Predictable state cycling 可預期狀態循環 |
| Trigger Method 觸發方式 | Mechanical force 機械力驅動 | Electrical signal 電氣訊號 |
| Integration 整合性 | Standalone device 獨立裝置 | Easy modern system integration 易整合現代系統 |
| Cost 成本 | Higher 較高 | Cost-effective 經濟實惠 |

## Wiring Diagram 接線示意

### Basic Connections 基本接線
```
Power Supply 電源供應:
  (+) DC 12V ────→ Power Input (+)
  (-) GND    ────→ Power Input (-)

Trigger Input 觸發輸入:
  Trigger Signal (+) ──→ Trigger Input
  (Pulse ≥0.5s)

Output Contacts 輸出接點:
  COM ──→ Common
  NO  ──→ Normally Open 常開
  NC  ──→ Normally Closed 常閉
```

### Typical Application 典型應用
```
[Trigger Source] → [Trigger Input] → [Module Logic] → [Output Contacts] → [Load Device]
[觸發源] → [觸發輸入] → [模組處理] → [輸出接點] → [負載設備]
```

## Important Notes 注意事項

**Power Requirements 電源要求**

Ensure stable DC 12V power supply.

確保提供穩定的 DC 12V 電源。

**Trigger Signal 觸發訊號**

Pulse width must be ≥0.5s, shorter pulses may fail to trigger.

脈衝寬度必須 ≥0.5s，過短可能無法正確觸發。

**Contact Rating 接點容量**

Load current should not exceed 2A (resistive load).

負載電流不應超過 2A（阻性負載）。

**Inductive Loads 感性負載**

Surge absorber recommended when controlling motors or coils.

控制馬達或線圈時建議加裝突波吸收器。

**State Memory 狀態記憶**

Module loses state memory after power loss. Requires reinitialization after power-on.

模組斷電後將失去狀態記憶。重新上電後需重新初始化。

## License 授權條款

**Hardware:** CERN Open Hardware Licence Strong Reciprocal Version 2.0 (CERN-OHL-S-2.0)

**Software:** GNU Affero General Public License v3.0 only (AGPL-3.0-only)

**Documentation:** Creative Commons Attribution 4.0 International (CC BY 4.0)

This project is certified as open source hardware by OSHWA.

本專案已通過 OSHWA 開源硬體認證。

## Keywords 關鍵字

Latching Relay, Self-Holding Circuit, Mechanical Relay, Bistable Switch, Relay Logic, Mechanical Latching, Industrial Control, Automation Control, Control Circuit, Switching Circuit, Power Switching, Home Automation

保持電驛, 自保持電路, 機械式繼電器, 雙穩態開關, 繼電器邏輯, 機械鎖存, 工業控制, 自動化控制, 控制電路, 切換電路, 電力開關, 家庭自動化

---

**Last Updated 最後更新:** December 2024
