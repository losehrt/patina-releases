# Patina Releases

A cross-platform LDAP management tool.

## About Patina

Patina is a desktop LDAP management tool built with Rust, offering an intuitive GUI for managing LDAP directory services.

### Why Patina?

Most existing LDAP management tools either lack native macOS support or have no Apple Silicon compatibility at all. Finding a reliable, well-designed LDAP client on macOS — especially on M-series Macs — has been a frustrating experience. Patina was born out of that frustration: a tool built from scratch to fill the gap, designed to meet real-world needs with first-class macOS support and cross-platform availability.

### Features

- **Connection Management** - Save multiple LDAP server profiles with TLS / StartTLS / LDAPS support
- **Directory Browsing** - Tree-structured browsing with drag-and-drop move / copy
- **Entry Management** - Add, edit, delete, rename, and copy LDAP entries
- **Advanced Search** - LDAP filter builder with Base / One Level / Subtree search scopes
- **Batch Operations** - Batch modify and delete with progress tracking
- **LDIF Import/Export** - Import and export single entries or entire subtrees
- **Password Management** - Change user passwords
- **Schema Viewer** - Browse object classes and attribute types
- **Auto Update** - Built-in automatic update mechanism

## Installation

Go to the [Releases](https://github.com/losehrt/patina-releases/releases) page to download the latest version.

### macOS

| File | Platform |
|---|---|
| `Patina_x.x.x_aarch64.dmg` | Apple Silicon (M1/M2/M3/M4) |
| `Patina_x.x.x_x64.dmg` | Intel Mac |

Download the corresponding `.dmg` file, open it, and drag Patina.app to the Applications folder.

If blocked by Gatekeeper on first launch, run:

```bash
xattr -cr /Applications/Patina.app
```

### Windows

| File | Description |
|---|---|
| `Patina_x.x.x_x64-setup.exe` | NSIS installer, recommended for most users |
| `Patina_x.x.x_x64_en-US.msi` | MSI installer, suitable for enterprise deployment |

- **`.exe`**: Standard setup wizard with custom install path and desktop shortcut options.
- **`.msi`**: Supports Group Policy silent installation:
  ```bash
  msiexec /i Patina_x.x.x_x64_en-US.msi /quiet
  ```

### Linux

| File | Platform |
|---|---|
| `Patina_x.x.x_amd64.deb` | Debian / Ubuntu |
| `Patina_x.x.x_amd64.AppImage` | Any Linux distribution |

- **`.deb`**:
  ```bash
  sudo dpkg -i Patina_x.x.x_amd64.deb
  # or
  sudo apt install ./Patina_x.x.x_amd64.deb
  ```
- **`.AppImage`**: No installation required, run directly:
  ```bash
  chmod +x Patina_x.x.x_amd64.AppImage
  ./Patina_x.x.x_amd64.AppImage
  ```

---

# Patina Releases

跨平台 LDAP 管理工具。

## 關於 Patina

Patina 是一款使用 Rust 打造的桌面 LDAP 管理工具，提供直覺的圖形介面來管理 LDAP 目錄服務。

### 開發緣由

市面上大多數 LDAP 管理工具缺乏原生 macOS 支援，更不用說 Apple Silicon 的相容性幾乎為零。在 macOS 上——尤其是 M 系列晶片的 Mac——想找到一款可靠、好用的 LDAP 用戶端一直是件令人頭痛的事。Patina 正是為了解決這個痛點而誕生：從頭打造一款符合實際需求的工具，以 macOS 原生支援為核心，同時兼顧跨平台使用。

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

### macOS

| 檔案 | 適用平台 |
|---|---|
| `Patina_x.x.x_aarch64.dmg` | Apple Silicon (M1/M2/M3/M4) |
| `Patina_x.x.x_x64.dmg` | Intel Mac |

下載對應的 `.dmg` 檔案，開啟後將 Patina.app 拖曳至 Applications 資料夾。

首次開啟若被 Gatekeeper 阻擋，請執行：

```bash
xattr -cr /Applications/Patina.app
```

### Windows

| 檔案 | 說明 |
|---|---|
| `Patina_x.x.x_x64-setup.exe` | NSIS 安裝程式，適合一般使用者 |
| `Patina_x.x.x_x64_en-US.msi` | MSI 安裝程式，適合企業環境部署 |

- **`.exe`**：標準安裝精靈，可選擇安裝路徑、建立桌面捷徑。
- **`.msi`**：支援 Group Policy 靜默安裝：
  ```bash
  msiexec /i Patina_x.x.x_x64_en-US.msi /quiet
  ```

### Linux

| 檔案 | 適用平台 |
|---|---|
| `Patina_x.x.x_amd64.deb` | Debian / Ubuntu 系列 |
| `Patina_x.x.x_amd64.AppImage` | 通用 Linux 發行版 |

- **`.deb`**：
  ```bash
  sudo dpkg -i Patina_x.x.x_amd64.deb
  # 或
  sudo apt install ./Patina_x.x.x_amd64.deb
  ```
- **`.AppImage`**：不需安裝，直接執行：
  ```bash
  chmod +x Patina_x.x.x_amd64.AppImage
  ./Patina_x.x.x_amd64.AppImage
  ```

## License

MIT
