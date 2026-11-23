# 3D 臺北

用開放資料做的臺北市 3D 模型，在瀏覽器裡就能看。

- 成果整理：https://lsxx20.github.io/taipei_3d/
- 3D 臺北：https://lsxx20.github.io/taipei_3d/map/

`index.html` 和 `img/` 是成果整理頁；`map/` 是 3D 網頁（v49），資料都在 `map/data/`，網頁載入時才讀。
地圖用 MapLibre GL JS 4.7.1 和 deck.gl 9.3.12，從 jsDelivr 載入。打開一次大約要下載 40 MB。

## 資料來源與授權

- 建照套繪圖、使用執照摘要：臺北市建築管理工程處
- 不動產成交案件實際資訊（實價登錄）：內政部
- 20 m 數值地形模型：內政部
- 國土利用現況調查、正射影像、通用版電子地圖：內政部國土測繪中心
- 行道樹、公園樹木、道路、人行道、路燈和街道設施：臺北市資料大平臺
- 建物、道路車道數、地標部件：OpenStreetMap（© OpenStreetMap 貢獻者，ODbL）

政府開放資料依各提供機關的授權條款使用。地標的材質從 Wikimedia Commons 的照片取樣，作者和授權列在網頁上各地標的出處裡，
改作的貼圖以 CC BY-SA 4.0 釋出。
