# gta5-addon-part-xml-builder
GTA 5 車輛與摩托車改裝部位生成器


這是一個基於網頁的工具，用於創建 GTA 5 車輛改裝部件的 XML 配置文件。該工具支持汽車和摩托車，幫助模組開發者生成格式正確的 XML 文件，可用於車輛改裝開發。

## 功能特點

- 為汽車和摩托車改裝部件生成 XML 配置
- 輕鬆切換汽車和摩托車模式
- 全面的車輛部件類型選項
- 詳細的骨骼結構選擇，實現精確部件放置
- 適當的碰撞骨骼配置
- XML 語法高亮，便於閱讀
- 每個 XML 標籤及其用途的詳細描述
- 用戶友好的界面，採用深色主題，提供舒適的編輯體驗

## 工作原理

該工具提供基於表單的界面，您可以：

1. 選擇車輛類型（汽車或摩托車）
2. 輸入您的改裝部件的模型名稱
3. 選擇部件類型（尾翼、保險桿、排氣管等）
4. 選擇適當的附著骨骼
5. 配置碰撞設置
6. 設置重量、音效屬性和其他參數
7. 生成格式正確的 XML 代碼，可直接用於您的模組文件

## XML 標籤說明

該工具提供了所有 GTA 5 車輛改裝 XML 標籤的說明：

- `<modelName>`：內部模型名稱標識符
- `<modShopLabel>`：改裝商店顯示的標籤名稱
- `<linkedModels />`：與此部件一起加載的關聯模型
- `<turnOffBones>`：安裝此部件時需要禁用的骨骼列表
- `<type>`：部件類型類別（VMT_SPOILER、VMT_BUMPER_F 等）
- `<bone>`：此部件的附著骨骼
- `<collisionBone>`：用於碰撞檢測的骨骼
- `<cameraPos>`：在改裝商店中查看時的相機位置
- `<audioApply>`：音效應用值
- `<weight>`：影響車輛物理特性的重量值
- `<turnOffExtra>`：是否關閉額外的視覺組件
- `<disableBonnetCamera>`：是否禁用引擎蓋相機
- `<allowBonnetSlide>`：是否允許引擎蓋滑動動畫

## 使用方法

1. 在任何現代網頁瀏覽器中打開 HTML 文件
2. 選擇汽車或摩托車模式
3. 填寫必要的字段
4. 點擊「生成 XML 代碼」
5. 將生成的 XML 代碼複製到您的車輛改裝文件中

## 支持的部件類型

### 汽車部件
- 尾翼
- 前/後保險桿
- 側裙
- 排氣管
- 防滾架
- 格柵
- 引擎蓋
- 擋泥板
- 車頂
- 引擎
- 剎車
- 變速箱
- 喇叭
- 懸掛
- 裝甲
- 車身彩繪

### 摩托車部件
- 車架
- 整流罩
- 前/後擋泥板
- 排氣管
- 油箱
- 座椅
- 引擎
- 剎車
- 變速箱
- 車把
- 懸掛
- 車身彩繪

## 安裝

無需安裝。只需下載 HTML 文件，並在任何現代網頁瀏覽器中打開。

## 貢獻

歡迎提交改進工具的貢獻！請隨時提交拉取請求。

## 許可證

該項目採用 MIT 許可證 - 詳情請參閱 LICENSE 文件。

## 致謝

- 本工具專為教育和模組開發目的而設計
- 與 Rockstar Games 或 Take-Two Interactive 沒有從屬關係
- GTA 5 和 Grand Theft Auto 是 Take-Two Interactive 的註冊商標

## 作者

- 您的姓名
- GitHub：[您的GitHub用戶名](https://github.com/您的GitHub用戶名)
