# MxCRner

這個 repo 只放**線上更新用的封裝**，不放原始碼。

更新檔都在 [Releases](../../releases)：

- `manifest.json` — 索引：版本號、每一組的 sha256 與大小
- `app.zip` — 程式
- `panel.zip` — 面板執行檔
- `mob-<地圖ID>.zip` — 各地圖的怪物訓練包

客戶端會自己讀 `releases/latest/download/manifest.json`，比對之後只下載有
變動的那幾組。設定、角色包、序號、錄影都不會被更新動到。
