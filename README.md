 🔧 問題 (Problem)

* 1.公司內部網段150區域是測試設備使用的專屬網段,但缺乏類似DHCP的分配方式
* 2.無生命週期管理回收機制,過往會依照申請者回報,但沒有確立時間完整性,造成殭屍vip
* 3.vip使用者名冊未經過整理,無法找到對應的歷史檔案

🚀 解決方案 (Solution)

本專案自動化 Fortigate VIP 設定
* 1.讓python自動抓出可用的內部網段以及對應的port,讓腳本去管理
* 2.可自動填入有效期限,未來可擴充資料庫,建立零信任基礎設施

⚙️ 功能 (Features)
* 1.自動建立 VIP的網段建議
* 2.減少重複的防火牆設定操作
* 3.簡化 IP 映射流程
* 4.提升操作效率

🧠 SRE 概念 (SRE Concept)
* 1.降低重複勞務 (Reduce toil)
* 2.自動化操作 (Automation)
* 3.基礎設施即程式化 (Infrastructure as Code 的概念)


🛠 技術 (Tech)
* .Bash / Python
* .Fortigate CLI / API
