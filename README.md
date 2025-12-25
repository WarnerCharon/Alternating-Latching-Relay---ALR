
# Alternating-Latching-Relay---ALR
Alternating Latching Relay

Project Description

This project implements an open source hardware design of a relay module that provides functions similar to a mechanical ratchet or bistable switch, achieving latching and toggle relay behavior using primarily mechanical relays, contact switching, and self-holding circuits. A latching relay (also called a bistable or impulse relay) retains its last switched state without requiring continuous coil power, offering efficient state memory and low power consumption during operation. 

The module’s core functionality involves self-holding relay logic, where an input pulse sets or resets the contact positions, mimicking the toggle or ratchet-like mechanical action found in bistable switches. This approach allows an electrical control system to maintain output states (ON/OFF) until the next control pulse is applied. 

The design is centered on electromagnetic (mechanical) relays and control circuitry, and can be integrated into a wide range of applications including:

Industrial control systems — for robust power switching and automation control of motors, actuators, and machine states.

Automation control and electrical engineering systems — for programmable logic and switching circuit designs.

Lighting control and power switching — maintaining lighting or load state without continuous coil power.

Home automation — remote or automated toggling of system states with minimal energy draw.

Motor and load control circuits — serving as a reliable holding and switching element within control loop designs.

All schematics, BOM, documentation, and mechanical relay design files are published under an open license in a public repository, enabling others to inspect, modify, build, and redistribute the hardware. This project demonstrates practical use of mechanical latching mechanisms in relay technology, bridging relay logic, bistable switch principles, and control circuit engineering into an accessible open source solution.


專案說明

本專案是一個 開源硬體設計，實現類似 棘輪機構或雙穩開關（bistable switch） 功能的繼電器模組，採用 機械繼電器、觸點切換與自保持（self-holding）電路 為核心設計。保持型繼電器（Latching Relay）能在輸入脈衝後維持狀態而無需持續線圈供電，具備良好的狀態記憶與低功耗特性。 

模組的核心功能為 切換與保持繼電器邏輯，透過控制脈衝來設定或重置繼電器觸點位置，類似機械棘輪機構的切換與鎖定行為，使電控系統在收到控制訊號後保持輸出狀態，直到下一次脈衝觸發。 

設計以 電磁（機械式）繼電器和控制電路 為主，並能應用於多種場景，例如：

工業控制系統 — 用於馬達、執行器等設備的電力切換與自動化控制。

自動化控制與電機工程設計 — 支援可程式邏輯與切換電路架構應用。

照明控制與電力切換 — 在無需持續線圈通電情況下維持照明或負載狀態。

居家自動化（Home Automation） — 遠端或自動狀態切換應用，降低能耗。

馬達及負載控制電路 — 作為可靠的保持與切換元件整合於控制迴路設計中。

本專案所有 電路圖、BOM、說明文件與設計檔案已公開於開源授權庫，可供他人檢視、修改、製造與再分發。此設計將 繼電器邏輯、雙穩開關、控制電路工程 等專業機電概念整合為實用的開源硬體方案。
