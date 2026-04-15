# 養車管家AI — Terms of Service and Privacy Policy

_Last updated: April 15, 2026_

> This document is the authoritative version served at the public URL used in the App Store Connect "Privacy Policy URL" field. It is mirrored inside the app via `LegalDocument.swift`. When editing, update both files in lockstep.

---

## English

### 1. About This Document
This document serves as both the Terms of Service and the Privacy Policy for 養車管家AI (the "App"). By installing or using the App, you agree to these terms.

### 2. What the App Does
The App helps you track vehicle maintenance records by using AI to extract service items and costs from receipts. Recognition is performed by an LLM provider you choose (OpenAI or Groq) using an API key you supply yourself.

### 3. What We Collect
**We collect nothing.** The App has no servers, no accounts, no analytics, no telemetry, and no tracking SDKs. The developer never receives your API keys, receipt contents, vehicle data, or any personally identifiable information.

### 4. Where Your Data Lives
- **API keys** you enter are stored only on your device in the iOS Keychain (`kSecAttrAccessibleWhenUnlockedThisDeviceOnly`). They are not synced to iCloud and are not transmitted anywhere except to the LLM provider you selected when you explicitly tap "Scan".
- **Maintenance records**, including receipt images, vehicle nicknames, and AI-generated insights, are stored only on your device in a local SwiftData database.
- The App does **not** upload any data to a backend controlled by the developer.

### 5. Third-Party Processing
When you scan a receipt:
- **On-Device OCR + AI mode**: Apple Vision runs on-device to extract text, then only the plain text (not the image) is sent to your selected LLM provider for structured extraction.
- **AI Vision mode**: the entire receipt image is sent to your selected LLM provider.

Your data, while in transit to and while being processed by the LLM provider, is subject to that provider's own privacy policy and terms of service:
- OpenAI: https://openai.com/policies/privacy-policy
- Groq: https://groq.com/privacy-policy/

By configuring an API key, you confirm that you have reviewed and agree to the respective third-party provider's terms.

### 6. Camera and Photo Library Permissions
The App requests access to your camera and photo library solely for the purpose of capturing or selecting a receipt image. The App does not read any other photos from your library and does not upload them to any developer-controlled backend.

### 7. No Account, No Identification
The App does not require you to create an account, sign in, or provide any personal information. The only identifier the App tracks is an anonymous UUID used internally to link vehicles and records; this UUID stays on your device.

### 8. Use of the App
You agree to use the App only for its intended purpose — organizing your own vehicle maintenance records. You are responsible for the accuracy of the receipts you scan and the data that ends up in your records. AI insights are informational suggestions and do not constitute professional automotive advice.

### 9. Disclaimer
The App is provided "as is" without warranty of any kind. The developer is not responsible for any direct or indirect damages arising from use of the App, including but not limited to inaccuracies in AI-generated results, charges incurred from third-party API usage, or data loss.

### 10. Changes to This Document
This document may be updated from time to time. Material changes will be reflected here and in the App. Continued use of the App constitutes acceptance of the updated document.

### 11. Contact
For questions about this document, please file an issue at the App's GitHub project: https://github.com/thsiao3000-commits/ServiceSenseAI

---

## 繁體中文

### 一、關於本文件
本文件同時為養車管家AI（以下稱「本 app」）的服務條款與隱私權政策。當你安裝或使用本 app，即表示同意本條款。

### 二、本 app 的用途
本 app 協助你追蹤車輛維護紀錄，透過 AI 辨識保養帳單自動抽出項目與金額。辨識過程由你自行選擇的 LLM 服務商（OpenAI 或 Groq）執行，使用你自己提供的 API Key。

### 三、我們收集什麼資料
**我們不收集任何資料。** 本 app 沒有自己的伺服器、沒有帳號系統、沒有使用分析、沒有遙測、沒有任何追蹤 SDK。開發者完全不會接收你的 API Key、帳單內容、車輛資料或任何個人識別資訊。

### 四、資料儲存位置
- **API Key**：僅儲存於你的裝置上，透過 iOS Keychain 保護（`kSecAttrAccessibleWhenUnlockedThisDeviceOnly`）。金鑰不會同步到 iCloud，也不會傳送到任何地方，除非你主動點擊「掃描」時傳給你選定的 LLM 服務商。
- **保養紀錄**（包含帳單影像、車輛暱稱、AI 分析建議）：僅儲存於你的裝置的本地 SwiftData 資料庫。
- 本 app **不會**將任何資料上傳到開發者控制的後端。

### 五、第三方處理
當你掃描帳單時：
- **本地 OCR + AI 模式**：Apple Vision 在本機執行文字辨識，只將純文字（非圖片）送到你選擇的 LLM 服務商進行結構化整理。
- **AI 視覺辨識模式**：整張帳單圖片會送到你選擇的 LLM 服務商。

你的資料在傳輸至 LLM 服務商及之後的處理，適用於該服務商自身的隱私權政策與服務條款：
- OpenAI：https://openai.com/policies/privacy-policy
- Groq：https://groq.com/privacy-policy/

當你配置 API Key 時，即代表你已審閱並同意該第三方服務商的條款。

### 六、相機與相簿權限
本 app 請求相機與相簿權限，僅用於拍攝或選擇帳單照片。本 app 不會讀取你相簿中的其他照片，也不會將它們上傳到任何開發者控制的後端。

### 七、無帳號、無身分識別
本 app 不要求你建立帳號、登入或提供任何個人資訊。唯一的識別碼是內部用於車輛與紀錄關聯的匿名 UUID，此 UUID 僅存在於你的裝置上。

### 八、使用規範
你同意僅以本 app 的預期用途（整理你自己的車輛維護紀錄）使用本 app。你有責任確認所掃描帳單的準確性以及進入紀錄的資料。AI 分析建議為資訊性參考，不構成專業汽車維修建議。

### 九、免責聲明
本 app 依「現狀」提供，不附帶任何形式的擔保。開發者不對使用本 app 所衍生的任何直接或間接損害負責，包括但不限於 AI 結果的不準確、使用第三方 API 產生的費用，或資料遺失。

### 十、本文件的變更
本文件可能隨時更新。重大變更會反映在本文件與 app 內。繼續使用本 app 即視為接受更新後的內容。

### 十一、聯絡方式
若對本文件有疑問，請至本 app 的 GitHub 專案回報：https://github.com/thsiao3000-commits/ServiceSenseAI
