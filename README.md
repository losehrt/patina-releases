# Patina Releases

Release binaries for [Patina](https://github.com/losehrt/patina) - 跨平台 LDAP 管理工具。

## 關於 Patina

Patina 是一款使用 Tauri v2 + React + Rust 打造的桌面 LDAP 管理工具，提供直覺的圖形介面來管理 LDAP 目錄服務。

### 主要功能

- **連線管理** - 儲存多組 LDAP 伺服器設定檔，支援 TLS / StartTLS / LDAPS
- **目錄瀏覽** - 樹狀結構瀏覽與操作，支援拖放移動 / 複製
- **Entry 管理** - 新增、編輯、刪除、重新命名、複製 LDAP entries
- **進階搜尋** - LDAP filter 建構器，支援 Base / One Level / Subtree 搜尋範圍
- **批次操作** - 批次修改與刪除，附進度追蹤
- **LDIF 匯入匯出** - 支援單筆或整個子樹的 LDIF 匯出入
- **密碼管理** - 變更使用者密碼
- **Schema 檢視** - 瀏覽 object classes 與 attribute types
- **自動更新** - 內建自動更新機制

## 下載安裝

前往 [Releases](https://github.com/losehrt/patina-releases/releases) 頁面下載最新版本。

### macOS (Apple Silicon)

下載 `.dmg` 檔案，拖曳至 Applications 資料夾。

首次開啟若被 Gatekeeper 阻擋，請執行：

```bash
xattr -cr /Applications/Patina.app
```

### Windows

下載 `.msi` 或 `.exe` 安裝程式，依照安裝精靈完成安裝。

## 相關連結

- [Patina 主專案](https://github.com/losehrt/patina)

## License

MIT
